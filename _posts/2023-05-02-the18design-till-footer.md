# Long Time No See! 😛 

Finally, back after a few days and feeling good about getting my schedule back on track again. I've been struggling a bit in this but yes finally getting things sorted one by one.. 

So yes, yesterday and today's work is combined. Following are the things I've been working on - 

1. **Pricing**

-> made the top part of pricing already 
-> worked on price cards inner items -> lists, buttons, prices, etc.

PR can be found [here](https://github.com/jazzcodes/the18Design/pull/5).

2. **FAQ Accordion**

Used Javascript to add functionality to accordion

        const q1Plus=document.getElementById("q1-plus");
        const q2Plus=document.getElementById("q2-plus");
        const q3Plus=document.getElementById("q3-plus");
        const q4Plus=document.getElementById("q4-plus");
        const q5Plus=document.getElementById("q5-plus");
        const a1=document.getElementById("a1");
        const a2=document.getElementById("a2");
        const a3=document.getElementById("a3");
        const a4=document.getElementById("a4");
        const a5=document.getElementById("a5");
        const q1Minus=document.getElementById("q1-minus");
        const q2Minus=document.getElementById("q2-minus");
        const q3Minus=document.getElementById("q3-minus");
        const q4Minus=document.getElementById("q4-minus");
        const q5Minus=document.getElementById("q5-minus");



    q1Plus.addEventListener("click", function(){
    
   
    a1.style.display="flex";
    q1Minus.style.display="initial";
    q1Plus.style.display="none";
    console.log("a1 expanded");
    });

    q2Plus.addEventListener("click", function(){
    
    a2.style.display="flex";
    q2Minus.style.display="initial";
    q2Plus.style.display="none";
    console.log("a2 expanded");
    });

    q3Plus.addEventListener("click", function(){
    
    a3.style.display="flex";
    q3Minus.style.display="initial";
    q3Plus.style.display="none";
    console.log("a3 expanded");
    });

    q4Plus.addEventListener("click", function(){
    
    a4.style.display="flex";
    q4Minus.style.display="initial";
    q4Plus.style.display="none";
    console.log("a4 expanded");
    });

    q5Plus.addEventListener("click", function(){
    
    a5.style.display="flex";
    q5Minus.style.display="initial";
    q5Plus.style.display="none";
    console.log("a5 expanded");
    });

    q1Minus.addEventListener("click", function(){
    
    a1.style.display="none";
    q1Minus.style.display="none";
    q1Plus.style.display="initial";
    console.log("a1 hidden");
    });

    q2Minus.addEventListener("click", function(){
    
    a2.style.display="none";
    q2Minus.style.display="none";
    q2Plus.style.display="initial";
    console.log("a2 hidden");
    });

    q3Minus.addEventListener("click", function(){
    
    a3.style.display="none";
    q3Minus.style.display="none";
    q3Plus.style.display="initial";
    console.log("a3 hidden");
    });

    q4Minus.addEventListener("click", function(){
    
    a4.style.display="none";
    q4Minus.style.display="none";
    q4Plus.style.display="initial";
    console.log("a4 hidden");
    });

    q5Minus.addEventListener("click", function(){
    
    a5.style.display="none";
    q5Minus.style.display="none";
    q5Plus.style.display="initial";
    console.log("a5 hidden");
    });
    
PR can be found [here](https://github.com/jazzcodes/the18Design/pull/6).

3. Footer

Worked on footer for the mobile version. DEsktop part needs to be worked on and is a bit tricky as I need to study about `order` property of flex-items once.
PR can be found [here](https://github.com/jazzcodes/the18Design/pull/7).


site is active [here](https://jazzcodes.github.io/the18Design/).

Rest I'll do tomorrow.
Till then byes! 

