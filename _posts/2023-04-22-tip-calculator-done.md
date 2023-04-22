# If Your Fear Change, Leave it Here :) - Tip Calculator it is!

Today, I finally completed the tip calculator task. Adding functionality was a fun as well as a challenging part again. I feel these tasks would lead me somewhere as I feel so satisfied after solving a problem...

So, the way I solved:

1.  Added all the neccessary dsicount buttons, reset button, text inputs and lastly the result text.

         const bill=document.querySelector("#bill-input");
         const p5=document.querySelector("#p5");
         const p10=document.querySelector("#p10");
         const p15=document.querySelector("#p15");
         const p25=document.querySelector("#p25");
         const p50=document.querySelector("#p50");
         const custom=document.querySelector("#custom-input");
         const people=document.querySelector("#people-input");
         const resetBtn=document.querySelector(".reset");
         const tipResult=document.querySelector(".tip-amount__result");
         const totalResult=document.querySelector(".total-amount__result");
         const errorPeople=document.querySelector(".people__error");

2. Printed the values to see the current status

         console.log(bill.value);
         console.log(people.value);
         console.log(tipResult.innerText);
         console.log(totalResult.innerText);
         
3. Added event listeners for `click` on all discount buttons

              p5.addEventListener("click",function(e)
              {   
                if(people.value=="")                             -> to check if people field is empty, no amount would be displayed
                {
                  tipResult.innerText="$0.00";
                  totalResult.innerText="$0.00";
                  console.log("working");
  
                }
                
              else{
                  const tipAmount = 0.05*bill.value;
                  tipResult.innerText=`$${tipAmount}.00`;
                  totalResult.innerText=`$${people.value*tipAmount}.00`;
                  custom.value="";     -> if buttons clicked in midst of using custom discount -> empty custom field
                  e.preventDefault();
                }
              })
              
   Similarly, added for all 5 discount buttons.
              
4. Added event listeners for `input` in custom discount field


        custom.addEventListener("input", function(e)
        {   
          if(people.value=="")
          {
            tipResult.innerText="$0.00";
            totalResult.innerText="$0.00";
          }

          else{
            const tipAmount = (e.target.value*bill.value)/100;                     -> for any value inside the input field
            tipResult.innerText=`$${tipAmount}.00`;
                    totalResult.innerText=`$${people.value*tipAmount}.00`;
          }
        });
        
        
                      
6. If bill as well as person field is empty -> reset button has a grayish appearance


        if(bill.value=='' && people.value=='')
        {
         resetBtn.style.opacity="0.3";
        
        }
        

7. Bill Input


         bill.addEventListener("input", function(e)
        {
        console.log(e.target.value);
        if(e.target.value!=="")
        {
   
        resetBtn.style.opacity="1";

        }
        else{

       resetBtn.style.opacity="0.3";
       }

       });
       
       
8. People Input

       people.addEventListener("input", function(e)
       {
         console.log(e.target.value);
         if(e.target.value!=="")
         {
           resetBtn.style.opacity="1";
           if(e.target.value==0)
           {
       errorPeople.innerText="Can't be zero";                          -> handles error when number of people = 0
       people.style.borderColor="rgb(224, 61, 61)";
       }

     
        }
   
         else{
           tipResult.innerText="$0.00";
           totalResult.innerText="$0.00";
              resetBtn.style.opacity="0.3";
        errorPeople.innerText="";
           people.style.borderColor="var(--accent)";
         }
        });
        
 9.   Reset Button's functinality
     
     resetBtn.addEventListener("click",function()
      {
        tipResult.innerText="$0.00";
        totalResult.innerText="$0.00";
        resetBtn.style.opacity="0.3";

      });

     console.log(resetBtn.disabled);
     
     
 That's it for this task. This is combined day of 21st April, 2023 & 22nd April, 2023. 

Code is available [here](https://github.com/jazzcodes/tip-calculator-app/pull/3)
Site is active [here](https://jazzcodes.github.io/tip-calculator-app/?custom=)

Will start with JS30 T5 on Monday..
Till then Bye Bye! :D 
        
