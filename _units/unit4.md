---
title: 'Unit 4: Basic Dynamic Sites'
layout: post
unit: 4
date: 2025-07-11 00:00:00
---

> Given that this course has CS pre-requisites, we're assuming you're comfortable with progamming basics such as variables, loops, and functions. If you'd like to review some programming basics within the context of JavaScript, you may refer to the material below:
- Read [Hello, World!](https://javascript.info/hello-world) and [Code Structure](https://javascript.info/structure)
- Read [Pop-up Boxes](https://www.learn-js.org/en/Pop-up_Boxes)
- Read [Variables and Types](https://www.learn-js.org/en/Variables_and_Types) and [Operators](https://www.learn-js.org/en/Operators)
- Read [Conditions](https://www.learn-js.org/en/Conditions) and [Loops](https://www.learn-js.org/en/Loops)
- Read [Functions](https://www.learn-js.org/en/Functions)
- Watch [this Intro to JavaScript playlist](https://www.youtube.com/playlist?list=PLzn-iGwKeXiZfMY45TJ962-qBP4wLxdNK)
{: .block-tip }

## Unit Essential Questions
You should use the questions below to assess your own learning and understanding of course material. These questions are also a good method of organization if you're taking notes.

### JavaScript
- How can I use JavaScript to modify websites?
- How can I use JavaScript to make sites interactive?
- What are event handlers and how are they used?
- How do I ensure the addition of JavaScript doesn't negatively impact the accessibility of my site?

### jQuery [optional]
- What’s the difference between JavaScript (JS) and jQuery (JQ)?
- How does the syntax of JQ differ from that of JS?
- What are JQ pseudo-selectors and how do they work?
- How do event handlers work in JQ?
- How do animations work in JQ?

## Unit Readings
### JavaScript
- Read [DOM tree](http://javascript.info/dom-nodes) and/or Watch [Document Object Model](https://www.youtube.com/watch?v=sWUT97Ne7V4)
- Read Accessible JavaScript [Overview of Accessible JavaScript](https://webaim.org/techniques/javascript/) and [Other Issues](https://webaim.org/techniques/javascript/other)
- Read [Searching: getElement*, querySelector*](http://javascript.info/searching-elements-dom) and/or Watch:
	- [getElementById method](https://www.youtube.com/watch?v=h4-6JOQX9v4)
	- [getElementsByTagName method](https://www.youtube.com/watch?v=SwMgOMfelC8) 
	- [getElementsByTagName Part 2](https://www.youtube.com/watch?v=DzBmQbcr1ls) 
	- [getElementsByClassName](https://www.youtube.com/watch?v=ChLd2yFp-lA)
- Read [Interaction: alert, prompt, confirm](http://javascript.info/alert-prompt-confirm)
- Read [Accessible JavaScript: JavaScript Event Handlers](https://webaim.org/techniques/javascript/eventhandlers)
- Read [Mouse events basics](http://javascript.info/mouse-events-basics) and/or Watch [Intro to events](https://www.youtube.com/watch?v=0VYuk9uqu04)
- Read [Moving the mouse](http://javascript.info/mousemove-mouseover-mouseout-mouseenter-mouseleave) and/or Watch [The mouseover event](https://www.youtube.com/watch?v=Ka033dkRJi0)

> #### Check your understanding
> This optional exercise will have you practice with JavaScript before you start working on your assignment. 
> Complete the three functions for this [fish site JSFiddle](https://jsfiddle.net/vcchavez_uri/5s2bvcxa/).
>
> Make sure you don’t change anything in the HTML or CSS! You only need to add code to the JavaScript box-- there are 3 functions you need to complete, each associated with one of the three buttons on the fish site.
>
> **Note:** JSFiddle is a 'coding playground' that automatically links the HTML, CSS, and JS windows together so you don't have to. It's great for small code examples and similar to [CodePen](https://codepen.io) and many other 'coding playgrounds'
{: .block-tip}

### jQuery [optional]
> While not required, you will likely encounter jQuery syntax in the wild (especially on older BootStrap tutorials/videos) so it's helpful to at least be familiar with its syntax. Additionally, jQuery offers some nice built-in functions that in JavaScript would require your own manual implementation, so it's really useful for minimizing programming effort.
{: .block-tip }
- Read [Difference Between JavaScript And jQuery](https://www.c-sharpcorner.com/article/javascript-vs-jquery-difference-between-javascript-and-jquery/)
- Read [How jQuery Works](https://learn.jquery.com/about-jquery/how-jquery-works/)
- Read [Selecting Elements](https://learn.jquery.com/using-jquery-core/selecting-elements/)
- Review jQuery's [Events Documentation](https://learn.jquery.com/events/)
- Review jQuery's [Effects Documentation](https://learn.jquery.com/effects/)
- Watch [jQuery playlist](https://www.youtube.com/playlist?list=PLzn-iGwKeXiaJjtJ5IU92iiB0epgLv3Lu)

> #### Check your understanding
> This optional exercise will have you practice with jQuery before you start working on your assignment. 
> Complete the three functions for this [fish site JSFiddle](https://jsfiddle.net/vcchavez_uri/sac094n2/).
>
> Make sure you don’t change anything in the HTML or CSS! You only need to add code to the JavaScript box-- there are 3 functions you need to complete, each associated with one of the three buttons on the fish site. Make sure to use jQuery rather than JavaScript to complete these functions.
{: .block-tip}

{% for section in site.assignments %}
{% if section.unit == page.unit %}
## Unit Lab
{{ section.content }}
{% endif %}
{% endfor %}

## Additional Resources
### JavaScript
- Review [JavaScript CheatSheet](https://htmlcheatsheet.com/js/)
- Review W3School's [JavaScript Tutorial](https://www.w3schools.com/js/default.asp)
- Watch [Web Programming with JavaScript](https://www.youtube.com/playlist?list=PLzn-iGwKeXibCU8GJ5LZUzwWPvDxCeUT2) (YouTube Playlist, with some repeats from above)
- Read [Handling common JavaScript problems](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/JavaScript)

### Accessible JavaScript
- Read [CSS and JavaScript accessibility best practices](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/CSS_and_JavaScript)
- Read [Handling common [JavaScript] accessibility problems](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/Accessibility#javascript)
- Read [Handling common accessibility problems](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/Accessibility)

### jQuery
- Review [jQuery Cheat Sheet](https://htmlcheatsheet.com/jquery/)
- Review [jQuery Cheat Guide](https://websitesetup.org/wp-content/uploads/2017/01/wsu-jquery-cheat-sheet.pdf)
- Review [TutorialsPoint jQuery Tutorial](https://www.tutorialspoint.com/jquery/index.htm)
- Refer to [jQuery Docs](https://api.jquery.com/)
- Watch [JQuery Tutorial for Beginners playlist](https://www.youtube.com/playlist?list=PLr6-GrHUlVf_RNxQQkQnEwUiHELmB0fW1) 

<!-- FEEDBACK
There were a lot of resources, which was great, but it also felt overwhelming at times to go through them all and then spend several hours on website implementations.
There could be simplified resources streamlining the resources or providing a more guided approach to using them could improve the learning experience.
I think it would be good to have more examples of different things you can do with JavaScript. But the existing ones were very good examples.
I think additional guidance on debugging and common pitfalls in JavaScript coding would be beneficial for practical application.
it would've been helpful to have more information on how to test the websites without styling in different browsers and maybe on an example readme text.
I think it would be a little less overwhelming if we had less scattered readings and more information consolidated in one place. 
Maybe more demonstration of different JavaScript events/listeners would have been helpful? Like I found the document. the querySelector function was something I found helpful, and I wish that had been demonstrated in addition to the getElementsById or TagName functions.
I would've like some more direction/instruction in the assignment description on how to disable CSS, JavaScript, and images on certain common browsers and how to disable automatic animations.
I think what could improve is having more real life applications of JQuery usage. Even if its optional, it would be cool to see that.
I enjoyed the readings, but I would have liked to have more examples for pure JavaScript accessibility examples. There were a couple of things that I was unsure of how to implement and whether or not my eventual implementation was acceptable.
it would be better if the recorded lecture went through each of the requirements for the lab, as some of the requirements are a little unclear as posted on the course page.
-->
