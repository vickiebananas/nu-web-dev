---
title: 'Unit 5: Third-party Services'
layout: post
unit: 5
---

<!-- :** <br> JSONs, AJAX, APIs | Lab 4 Due <br> Lab 5 Out | -->

<!-- maybe have them host their sites and post link in a piazza thread to get feedback from each other? -->

## Unit Essential Questions
You should use the questions below to assess your own learning and understanding of course material. These questions are also a good method of organization if you're taking notes.

### AJAX
- What is AJAX?
- How does AJAX work?
- Why would one use AJAX?

### JSON
- What is JSON?
- How does JSON work?
- Why would one use JSON?

### APIs
- What is an API?
- How do APIs work?
- Why would one use APIs?

## Unit Readings

### AJAX
- Read [AJAX Introduction](https://www.w3schools.com/xml/ajax_intro.asp) and/or Watch [JavaScript and AJAX tutorial: What is AJAX?](https://www.youtube.com/watch?v=RDo3hBL1rfA)
- Read [AJAX: Getting Started](https://developer.mozilla.org/en-US/docs/Web/Guide/AJAX/Getting_Started) and/or Watch [Learn XML HTTP Requests in JavaScript: AJAX Tutorial](https://www.youtube.com/watch?v=rjmtYkRK1nM)

### JSON & APIs
- Read [Working with JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON) and [Introduction to web APIs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Introduction) and/or watch [Learn JSON in 5 minutes](https://www.youtube.com/watch?v=KgGIm6A9Tx0)
- Read: [Third-party APIs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Third_party_APIs)
	- Play close attention to the “[An approach for using third-party APIs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Third_party_APIs#an_approach_for_using_third-party_apis)" section! I **strongly recommend** you follow along with the tutorial and add in comments to your code to develop a better understanding of what the code is doing and why.

### Recorded Lecture
The lecture below provides additional information on working with APIs which you may find particularly useful for completing the exercise below. However, if you feel comfortable with the material already, you may choose to skip watching this lecture. You can access a [copy of the slides presented here](https://docs.google.com/presentation/d/18ZM0EBSRj4RztLgW2rgFNGd9IMe5v1OafCsNeNouVR4/).

<iframe width="560" height="315" src="https://www.youtube.com/embed/lg7Fp14TEUQ?si=M2wBmmC_pkOj73zL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

> ### Check your understanding
> This optional exercise will have you practice working with an API to create a dynamic image gallery. 
>
> Complete the two functions for this [Image Gallery JSFiddle](https://jsfiddle.net/vcchavez_uri/srhntbu2/) using [Unsplash's API](http://unsplash.com/developers). Make sure you don’t change anything in the HTML or CSS! You only need to add code to the JavaScript box-- there are 2 functions you need to complete, one for making the call to the API and the other for populating the data onto the site.
{: .block-tip}

### Additional Resources
- Review Mozilla's [Client-side web APIs Guides](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs)
- Review W3School's [Web APIs Tutorial](https://www.w3schools.com/js/js_api_intro.asp)
- Review W3School's [JSON Tutorial](https://www.w3schools.com/js/js_json_intro.asp)
- Review W3School's [AJAX Tutorial](https://www.w3schools.com/js/js_ajax_intro.asp)
- Review [Github's list of Public APIs](https://github.com/public-apis/public-apis)

{% for section in site.assignments %}
{% if section.unit == page.unit %}
## Unit Lab
{{ section.content }}
{% endif %}
{% endfor %}