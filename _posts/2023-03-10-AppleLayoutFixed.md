### Fixed Layout Requires a Minor Fix

Yesterday, we made the fluid layout ready, but it somewhere looked a bit hard coded. But still, I carried the task forward to fit in the components - header, footer, main, etc. After this, we noticed there's a vertical as well as horizontal bar and the content is looking a bit bigger than expected as per the design. So, I decided to wipe all the stuff again and create a layout again. This time we kinda succeeded since it was working fine on both the mobile and the desktop. The changes I made this time was that I used a new container for the whole content and made it flex rather than directly making the body element flex. Also, I used '%' unit to set the amount of space to be given to each flex-item rather than using 'px'. 

Now, everything went well but 100vh wasn't working as expected since the browser tab in every mobile caused an issue and due to this the vertical scroll bar appears. We looked for solutions -

1. CSS - [https://css-tricks.com/css-fix-for-100vh-in-mobile-webkit/](https://css-tricks.com/css-fix-for-100vh-in-mobile-webkit/)
2. Javascript - [https://dev.to/rachelg/a-javascript-fix-for-the-100vh-problem-on-mobile-screens-9im](https://dev.to/rachelg/a-javascript-fix-for-the-100vh-problem-on-mobile-screens-9im)

So, I'll try these two and figure out a possible solution asap.

Till then byee!
