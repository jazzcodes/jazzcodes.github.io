### Task Done Finally

Today, I worked on the refinement of the task I've been doing since a few days. 
I worked on the following issues -

1. Vewport Issues

Since I used `height:100vh` in the main body of the site, it behaved a bit abnormally on different mobile browsers, leading to a vertical scroll as discussed earlier. So, the CSS fix I talked about came handy over here.

`html,body{
    height: -webkit-fill-available;

}`

The main idea is to place `height: -webkit-fill-available;` in the html, body and any required element (in my case `page` element) so that it takes the browser url tab into consideration while calculation.

2. Search Field

There were notable icon overlapping issues, so fixed them. Also, the on clicking, the header seemed to shift by a few pixels, the issue was resolved by making the height of the collapsible container same as that of the header contents(the menu).

3. Vertical Menu

Making it visibile on tablet and the clicking area controlled by placing the `collapsible__icon` class in the right container.

4. Larger Screens

Centered the content on the larger screens, so that the elements tsappear closer to each other.

Overall, I have learnt a lot of things during this task and most importantly, I would like to thank my mentor to encourage me to take up this task again (since it seemed horrible the last time I attempted it) and to carefully review my progress, giving me constant necessary feedbacks for improvement.
 
Design can be found [here](https://www.figma.com/file/lVV0fvZhp0x5fS5ZQk8M9Q/Apple-Watch-Store-Landing-Page-Design-(Community)?node-id=0%3A1&t=bKCloTEIrD5i2x1f-0).
Code can be found [here](https://github.com/jazzcodes/Apple).
Site is live [here](https://fluffy-taffy-a8575f.netlify.app/#).

Byees!
