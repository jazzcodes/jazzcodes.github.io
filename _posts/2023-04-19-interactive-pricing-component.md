# Interactive Pricing Component 

Today, we added responsiveness to the JS-30 Task3 done yesterday and further continued with the Interactive Pricing Component FEM task that we started yesterday.

Following is the process followed and the points learned:

1. Followed mobile first approach as I mentioned yesterday
2. the complicated components I came across -> range slider, toggler
3. the toggler was something new to make and there I learned how to use a checkbox and utilise its `checked` property for DOM
4. range slider was the most tough part for today not bcz of it's functionality/JS but for setting its appearance
5. could style it after searching and trying various code snippets, finally was able to work out with one and then I understood the code and used it in my task according to my requirements
6. however, the surprising thing is that some styling works perfectly fine in chrome while other doesn't show up here in chrome but works perfectly fine in mozilla and vice versa. so, this is the reason that it's a tricky part for me and that is why just one feature is yet to be styled-> progress bar of range (this is working fine in mozilla, we can open and check too)
7. made it desktop responsive
8. next, added JS which would be clear in the followig steps
9. took range inputs and added an eventlistener for change in range and mousemove over the range component
10. uses the current range value to display the corresponding `page views` on the pricing component
11. added event listener on the checkbox of the toggler (switch)
12. if its `checked` property is `true` then 25% discount is given as per the problem statement
13. else the prev values are displayed as it is
14. however, once the checkbox is checked and range slider is moved, it's gonna show the discounted values only 

That's it for the task and tomorrow I'd start JS30 T4.

code can be found [here](https://github.com/jazzcodes/interactive-pricing-component/tree/initial).
site is active [here](https://jazzcodes.github.io/interactive-pricing-component/).

Byee, Byee! =)

