---
title: 'Unit 2: Web Programming Basics'
layout: post
unit: '2'
date: 2025-06-27 00:00:00
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

## Unit Readings
### Developer Tools
- Read [How to Use Your Browser’s Inspect Element Tool to Edit Webpages](https://kinsta.com/blog/inspect-element/) and/or Watch [How to Use Inspect Element to Edit Webpages](https://www.youtube.com/watch?v=TYYB8s4uUI4)
	- Note: If you use Safari, you'll first have to enable "Show Develop menu in menu bar" under the "Advanced" tab of your Safari Settings/Preferences.

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

### Accessibility [new!]
- Read [Accessibility Inspectors: A Basic Guide](https://www.sitepen.com/blog/accessibility-inspectors-a-basic-guide)
- [The Ultimate Web Accessibility Checklist](https://www.accessiblemetrics.com/wp-content/uploads/2018/10/Accessible-Metrics-Campaign-Content-Offer.pdf)
- [The 6 Simplest Web Accessibility Tests Anyone Can Do](https://karlgroves.com/2013/09/05/the-6-simplest-web-accessibility-tests-anyone-can-do)
- [How I do an accessibility check](https://www.youtube.com/watch?v=cOmehxAU_4s)
 (video)

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
Below are some additional resources specific to this unit. Even more additional resources are available under the "Resources" tab of our site.

### Dev Tools
- Read [How to use Inspect Element in Chrome, Safari, and Firefox](https://zapier.com/blog/inspect-element-tutorial/)
- Watch [6 Useful Inspect Element Tips](https://www.youtube.com/watch?v=9od4IEiCfOo) 

### HTML & CSS
#### General Reference
- Review W3School's [HTML Tutorial](https://www.w3schools.com/html/default.asp)
- Review W3School's [CSS Tutorial](https://www.w3schools.com/css/default.asp)
- Review Khan Academy's course on [HTML and CSS](https://www.khanacademy.org/computing/computer-programming/html-css)
- Read [Learn to style HTML using CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)

#### Navigation Bars (NavBars)
- Read [How TO - Top Navigation](https://www.w3schools.com/howto/howto_js_topnav.asp)
- Read [How TO - Clickable Dropdown](https://www.w3schools.com/howto/howto_js_dropdown.asp) and [How TO - Dropdown Navbar](https://www.w3schools.com/howto/howto_css_dropdown_navbar.asp) and/or Watch [this Navbars playlist](https://www.youtube.com/playlist?list=PLzn-iGwKeXib0e-A7QUZnFCljfgUgKKkK)

#### Lists
- Read [Creating Lists](https://learn.shayhowe.com/html-css/creating-lists) and/or Watch [Ordered and Unordered lists](https://www.youtube.com/watch?v=09oErCBjVns)

#### Tables
- Read [Organizing Data with Tables](https://learn.shayhowe.com/html-css/organizing-data-with-tables) and/or Watch [Creating a table](https://www.youtube.com/watch?v=wvR40su_XBM)

#### Forms
- Read: [Building Forms](https://learn.shayhowe.com/html-css/building-forms/) and [How to create a form and make it email its content to your mailbox](http://www.chami.com/tips/internet/010597I.html) and/or Watch [this Forms playlist](https://www.youtube.com/playlist?list=PLzn-iGwKeXiZsHr2_61yjnXg-2N3CM182)

<!-- 
FEEDBACK

adding exercises

One suggestion that I have for the course material this week is on the ordering of the reading material. For example in the "Adding Media" reading, many of the examples showed CSS styling and referencing classes and ids (for example ".teaser img") before we had even read about CSS and selectors. This made the reading confusing and caused me to become stuck and overthink the material. It would be better if there were notes on the course page mentioning how the reading contains material that will be covered later on. Similarly, another suggestion I have for the course material is on how it may be helpful to include notes mentioning which big sections or to where we are to read in the assigned readings. This is because I found myself becoming confused in the HTML and CSS lessons because they were long and went into dense material that I did not end up needing when creating my webpage. 

a cheat sheet with the different gotcha's, when to use what semantic HTML element, and some basic css snippets to do things like organize things side by side. 

The only thing that may have been confusing is that if a student did pursue the "only video" method, then I think it can be very confusing. I went through all of the resources so it was not an issue, but there was a pretty high jump into difficulty in EJ Media's videos; the explanation about id's and classes was omitted from the playlist. Rather than having these resources be an alternative, I think it should be required to look at both 

I thought this unit was really strong with the accessibility and features in general. I would've liked to see a case study with the inspection tool on a good and bad website just to get a better feel for what we should be aiming for.

Something that could've been improved was how to test for accessibility on chromium browsers. I looked into some of the websites that were listed in the unit and they didn't have clear instructions for testing on chromium browsers, but focused more on firefox and internet explorer. 

 Maybe the structing could be slightly different. because i ended up watching the box model videos before the introductory css video. It might have been more useful having those first.

-->

