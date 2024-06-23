---
title: 'Unit 2: Web Programming Basics'
layout: post
unit: 2
---

<!-- HTML, CSS, & JavaScript | 
Lab 1 Due 
Lab 2 Out |-->

## Unit Essential Questions
You should use the questions below to assess your own learning and understanding of course material. These questions are also a good method of organization if you're taking notes.

### Dev Tools
- What are browser developer tools?
- What can I do with developer tools?
- How can I better develop sites through trial and error?

### HTML
- What role does HTML play in creating sites?
- How do I program a basic website using HTML?

### CSS
- How do HTML and CSS work *together* to create sites?
- How do I program a basic website using HTML *and* CSS?
- What is the CSS box model and why is it useful?
- What are different ways to group and position my HTML elements?

<!-- ### JavaScript
- How can I use JavaScript to modify websites?
- How can I use JavaScript to make sites interactive?
- What are event handlers and how are they used? -->

## Unit Readings
### Developer Tools
- Read [How to Use Your Browser’s Inspect Element Tool to Edit Webpages](https://kinsta.com/blog/inspect-element/) and/or Watch [How to Use Inspect Element to Edit Webpages](https://www.youtube.com/watch?v=TYYB8s4uUI4)
	- Note: If you use Safari, you'll first have to enable "Show Develop menu in menu bar" under the "Advanced" tab of your Safari Settings/Preferences.
- Read [Accessibility Inspectors: A Basic Guide](https://www.sitepen.com/blog/accessibility-inspectors-a-basic-guide)

### HTML
- Read [Getting to Know HTML](https://learn.shayhowe.com/html-css/getting-to-know-html) and/or Watch [Intro to HTML](https://www.youtube.com/playlist?list=PLzn-iGwKeXiaek2pqBoTMlNn1tYZThS7u)
- Read [Adding Media](https://learn.shayhowe.com/html-css/adding-media) and/or Watch [Adding a image to a web page](https://www.youtube.com/watch?v=Zy4KJeVN7Gk) and [Resizing and sizing images](https://www.youtube.com/watch?v=dM12ctixdT4)

### CSS
- Read [Getting to Know CSS](https://learn.shayhowe.com/html-css/getting-to-know-css/) and/or Watch [CSS Tutorial for Beginners - Introduction to CSS](https://www.youtube.com/watch?v=qKoajPPWpmo)
- Read [Building Your First Web Page](https://learn.shayhowe.com/html-css/building-your-first-web-page) and/or Watch [Get Started With HTML & CSS](https://www.youtube.com/watch?v=pm5OVxpul48) and [How to link to a stylesheet using HTML](https://www.youtube.com/watch?v=4OMdzHnys9o)

#### CSS Box Model
- Read [Opening the Box Model](https://learn.shayhowe.com/html-css/opening-the-box-model/), [Positioning Content](https://learn.shayhowe.com/html-css/positioning-content/), and [Detailed Positioning](https://learn.shayhowe.com/advanced-html-css/detailed-css-positioning/) and/or Watch [this CSS Box Model playlist](https://www.youtube.com/playlist?list=PLzn-iGwKeXibPat_y_WcgWFcMouvL7Ecn)

#### CSS Basics
- Read [Working with Typography](https://learn.shayhowe.com/html-css/working-with-typography/), [Setting Backgrounds & Gradients](https://learn.shayhowe.com/html-css/setting-backgrounds-and-gradients/), and [Complex Selectors](https://learn.shayhowe.com/advanced-html-css/complex-selectors/) and/or Watch [this CSS Basics playlist](https://www.youtube.com/playlist?list=PLzn-iGwKeXiaeYd84vvM8AiGOyzZ0VGE_)

<!-- ### JavaScript
- Read [DOM tree](http://javascript.info/dom-nodes) and/or Watch [JavaScript Tutorial for Beginners - Document Object Model](https://www.youtube.com/watch?v=sWUT97Ne7V4)
- Read [Searching: getElementById](http://javascript.info/searching-elements-dom#document-getelementbyid-or-just-id) (stop once the section ends) and/or Watch [JavaScript Tutorial for Beginners - getElementById method](https://www.youtube.com/watch?v=h4-6JOQX9v4)
- Read [Searching: getElementsBy\*](http://javascript.info/searching-elements-dom#getelementsby) (stop once the section ends) and/or Watch [JavaScript Tutorial for Beginners - getElementsByTagName method](https://www.youtube.com/watch?v=SwMgOMfelC8), [JavaScript Tutorial for Beginners - getElementsByTagName Part 2](https://www.youtube.com/watch?v=DzBmQbcr1ls) and [JavaScript Tutorial for Beginners - getElementsByClassName](https://www.youtube.com/watch?v=ChLd2yFp-lA)
- Read [Interaction: alert, prompt, confirm](http://javascript.info/alert-prompt-confirm)
- Read [Mouse events basics](http://javascript.info/mouse-events-basics) and/or Watch [JavaScript Tutorial for Beginners - Intro to events](https://www.youtube.com/watch?v=0VYuk9uqu04)
- Read [Moving the mouse: mouseover/out, mouseenter/leave](http://javascript.info/mousemove-mouseover-mouseout-mouseenter-mouseleave) and/or Watch [JavaScript Tutorial for Beginners - The mouseover event](https://www.youtube.com/watch?v=Ka033dkRJi0) -->

> ### Preparing for JavaScript
Given that this course has CS pre-requisites, we're assuming you're comfortable with progamming basics such as variables, loops, and functions. We'll start talking about JavaScript soon so if you'd like to review some programming basics within the context of JavaScript, you may refer to the material below:
- Read [Hello, World!](https://javascript.info/hello-world) and [Code Structure](https://javascript.info/structure)
- Read [Pop-up Boxes](https://www.learn-js.org/en/Pop-up_Boxes)
- Read [Variables and Types](https://www.learn-js.org/en/Variables_and_Types) and [Operators](https://www.learn-js.org/en/Operators)
- Read [Conditions](https://www.learn-js.org/en/Conditions) and [Loops](https://www.learn-js.org/en/Loops)
- Read [Functions](https://www.learn-js.org/en/Functions)
- Watch [this Intro to JavaScript playlist](https://www.youtube.com/playlist?list=PLzn-iGwKeXiZfMY45TJ962-qBP4wLxdNK)
{: .block-tip }


{% for section in site.assignments %}
{% if section.unit == page.unit %}
## Unit Lab
{{ section.content }}
{% endif %}
{% endfor %}

## Additional Resources
### Dev Tools
- Read [How to use Inspect Element in Chrome, Safari, and Firefox](https://zapier.com/blog/inspect-element-tutorial/)
- Watch [6 Useful Inspect Element Tips](https://www.youtube.com/watch?v=9od4IEiCfOo) 

### HTML & CSS
#### General Reference
- Review W3School's [HTML Tutorial](https://www.w3schools.com/html/default.asp)
- Review W3School's [CSS Tutorial](https://www.w3schools.com/css/default.asp)
- Review Khan Academy's course on [HTML and CSS](https://www.khanacademy.org/computing/computer-programming/html-css)

#### Navigation Bars (NavBars)
- Read [How TO - Top Navigation](https://www.w3schools.com/howto/howto_js_topnav.asp)
- Read [How TO - Clickable Dropdown](https://www.w3schools.com/howto/howto_js_dropdown.asp) and [How TO - Dropdown Navbar](https://www.w3schools.com/howto/howto_css_dropdown_navbar.asp) and/or Watch [this Navbars playlist](https://www.youtube.com/playlist?list=PLzn-iGwKeXib0e-A7QUZnFCljfgUgKKkK)

#### Lists
- Read [Creating Lists](https://learn.shayhowe.com/html-css/creating-lists) and/or Watch [Ordered and Unordered lists](https://www.youtube.com/watch?v=09oErCBjVns)

#### Tables
- Read [Organizing Data with Tables](https://learn.shayhowe.com/html-css/organizing-data-with-tables) and/or Watch [Creating a table](https://www.youtube.com/watch?v=wvR40su_XBM)

#### Forms
- Read: [Building Forms](https://learn.shayhowe.com/html-css/building-forms/) and [How to create a form and make it email its content to your mailbox](https://www.chami.com/tips/internet/010597I.html) and/or Watch [this Forms playlist](https://www.youtube.com/playlist?list=PLzn-iGwKeXiZsHr2_61yjnXg-2N3CM182)

<!-- ### JavaScript
- [JavaScript CheatSheet](https://htmlcheatsheet.com/js/)
- Review W3School's [JavaScript Tutorial](https://www.w3schools.com/js/default.asp)
- Watch [Web Programming with JavaScript](https://www.youtube.com/playlist?list=PLzn-iGwKeXibCU8GJ5LZUzwWPvDxCeUT2) (YouTube Playlist, with some repeats from above) -->
