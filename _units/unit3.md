---
title: 'Unit 3: Modern Development'
layout: post
unit: 3
---

<!-- SCSS, Optimization, & Responsive Design | Lab 2 Due <br> Lab 3 Out <br> Final Project Out | -->
<!-- resp dsign: 272 unit 10 -->
<!-- incl cookies and image optimization -->

## Unit Essential Questions
You should use the questions below to assess your own learning and understanding of course material. These questions are also a good method of organization if you're taking notes.

### Image Optimization
- What is image optimization?
- What does optimizing the images on my site accomplish?

### Responsive Design
- What is responsive design?
- Why is it important for a website to be responsive?
- How can I check if my site is responsive?
- What are some guidelines to ensure a site is responsive?

#### Bootstrap
- What is Bootstrap?
- What are some benefits of using Bootstrap?
- How do I use Bootstrap?

## Unit Readings
### Image Optimization
- Read [5 Reasons Visitors Leave Your Website](https://www.websitemagazine.com/blog/5-reasons-visitors-leave-your-website)
- Read [Optimizing Images for the Web (Speed & Size)](https://webeminence.com/optimizing-images-resize-for-website/) and/or Watch [Optimize Images for Website - WHY and HOW](https://www.youtube.com/watch?v=oi5SCqS-7xw)

### Responsive Design
- Read [Responsive Web Design](https://learn.shayhowe.com/advanced-html-css/responsive-web-design/) and/or Watch [this Responsive Design playlist](https://www.youtube.com/playlist?list=PLzn-iGwKeXiaj1l3y9sF38twYpmZ8SoPe)
- Read [CSS Units](https://www.w3schools.com/cssref/css_units.asp) and/or Watch [Learn CSS Units In 8 Minutes](https://www.youtube.com/watch?v=-GR52czEd-0)

#### Bootstrap
- Read [Bootstrap 5 Getting Started](https://www.w3schools.com/bootstrap5/bootstrap_get_started.php) and/or Watch [Bootstrap Tutorial for Beginners - Introduction](https://www.youtube.com/watch?v=bPuyoVh9U3g) and [Bootstrap v5.3 Introduction: Getting Started](https://www.youtube.com/watch?v=iMoGa-et7PM)
- Read [Bootstrap 5 Grid Basic](https://www.w3schools.com/bootstrap5/bootstrap_grid_basic.php) and/or Watch [Bootstrap 5 Crash Course Tutorial - Grid Layout (part 1)](https://www.youtube.com/watch?v=irfbn103AzE)

> ##### SCSS
> You may notice some unique-looking CSS as you explore Bootstrap and that's because they use SASS— specifically SCSS— which extends CSS by offering cool features such as variables, nesting, and more. You can learn more about SCSS by reading [What is the difference between SCSS and SASS](https://www.geeksforgeeks.org/what-is-the-difference-between-scss-and-sass/) and/or watching [Sass in 100 Seconds](https://www.youtube.com/watch?v=akDIJa0AP5c)

> ##### Bootstrap Versions
> There are three versions of Bootstrap-- to minimize the overhead of having to learn jQuery, we'll be working with Bootstrap 5.
>
> - **Bootstrap 3**: Released in 2013, this was the original version of Bootstrap. It's considered to be "the most stable version of Bootstrap, and it is still supported by the team for critical bugfixes and documentation changes."
> - **Bootstrap 4**: Released in 2018, this was the first major upgrade to Bootstrap. It included "new components, faster stylesheet and more responsiveness. However, Internet Explorer 9 and down is not supported."
> - **Bootstrap 5**: Released in 2021, this is the newest version of Bootstrap. While Bootstrap 3 & 4 used jQuery, Bootstrap 5 has switched over to vanilla JavaScript (i.e., plain JavaScript). "Bootstrap 5 supports the latest, stable releases of all major browsers and platforms. However, Internet Explorer 11 and down is not supported."
> 
> **Note:** Bootstrap 3 and Bootstrap 4 is still supported by the team for critical bugfixes and documentation changes, and it is perfectly safe to continue to use them. However, new features will NOT be added to them.
>
> Source: [W3Schools](https://www.w3schools.com/bootstrap/bootstrap_ver.asp)

{% for section in site.assignments %}
{% if section.unit == page.unit %}
## Unit Lab
{{ section.content }}
{% endif %}
{% endfor %}

## Additional Resources
### HTML & CSS
- Read [Handling common HTML and CSS problems](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/HTML_and_CSS)
### Image Formats
- Read [The 5 Types of Digital Image Files: TIFF, JPEG, GIF, PNG, and Raw Image Files, and When to Use Each One](https://www.ivanexpert.com/blog/2010/05/the-5-types-of-digital-image-files-tiff-jpeg-gif-png-and-raw-image-files-and-when-to-use-each-one/) and/or Watch [Image File Formats - JPEG, GIF, PNG](https://www.youtube.com/watch?v=ww12lImOJ38)

### Bootstrap
- [Official Bootstrap 5 Documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- Check out [W3School's Bootstrap 5 Tutorial](https://www.w3schools.com/bootstrap5/index.php)
- List of all [Bootstrap classes](https://www.w3schools.com/bootstrap/bootstrap_ref_all_classes.asp)
	- **Note:** While this is from W3School's Bootstrap 3 tutorial, the same classes apply for Bootstrap 5.
- Playlist: [EJ Media's Bootstrap Tutorial](https://www.youtube.com/playlist?list=PLr6-GrHUlVf-gjvHuzCnVmeuaeAjRGltv)
	- **Note:** While his videos are for Bootstrap 3, the same principles apply and many students like his tutorial style which we've watched in the past.
- Playlist: [Net Ninja's Bootstrap 5 Tutorial](https://www.youtube.com/playlist?list=PL4cUxeGkcC9joIM91nLzd_qaH_AimmdAR)
	- **Note:** He uses [Visual Studio Code](https://code.visualstudio.com) as his IDE which has a lot of bells and whistles. This IDE is is available for free for Windows and Mac, but does have a bit of a steeper learning curve than the basic text editors I previously suggested.