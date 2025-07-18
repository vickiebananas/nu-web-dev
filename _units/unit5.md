---
title: 'Unit 5: Third-party Services'
layout: post
unit: '5'
date: 2025-07-18 00:00:00
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

### JSON 
- Review W3School's [JSON Tutorial Intro](https://www.w3schools.com/js/js_json_intro.asp)
- Read [Working with JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON) and/or watch [Learn JSON in 5 minutes](https://www.youtube.com/watch?v=KgGIm6A9Tx0)

### APIs
- Read [Introduction to web APIs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Introduction) and/or Watch [What is an API and how does it work? (In plain English)](https://www.youtube.com/watch?v=Yzx7ihtCGBs)
- Read [Third-party APIs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Third_party_APIs) and/or Watch [Fetch API - JavaScript Tutorial for beginners](https://www.youtube.com/watch?v=ubw2hdQIl4E)
	- I **strongly recommend** you follow along with the tutorial and add in comments to your code to develop a better understanding of what the code is doing and why.
	- If doing the reading, pay close attention to the “[An approach for using third-party APIs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Third_party_APIs#an_approach_for_using_third-party_apis)" section! 


### Recorded Lecture
The lecture below provides additional information on working with APIs which you may find particularly useful for completing the exercise below. However, if you feel comfortable with the material already, you may choose to skip watching this lecture. You can access a [copy of the slides presented here](https://docs.google.com/presentation/d/18ZM0EBSRj4RztLgW2rgFNGd9IMe5v1OafCsNeNouVR4/).

<iframe width="560" height="315" src="https://www.youtube.com/embed/lg7Fp14TEUQ?si=M2wBmmC_pkOj73zL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

> ### Check your understanding
> This optional exercise will have you practice working with an API to create a dynamic image gallery. 
>
> Complete the two functions for this [Image Gallery JSFiddle](https://jsfiddle.net/vcchavez_uri/srhntbu2/) using [Unsplash's API](http://unsplash.com/developers). Make sure you don’t change anything in the HTML or CSS! You only need to add code to the JavaScript box-- there are 2 functions you need to complete, one for making the call to the API and the other for populating the data onto the site.
{: .block-tip}

### Additional Resources
Below are some additional resources specific to this unit. Even more additional resources are available under the "Resources" tab of our site.

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

<!-- FEEDBACK

I think one of the biggest strengths of this unit was the ability to look at and see our peers' sites. This helped inspire me to think of new ideas and functionalities to add to my site. Another strength of this unit could be the content it covers specifically JSON objects. JSON objects are a ubiquitous tool used by all developers. A weakness in this unit is that it did not prompt us to use what we learned to further code our sites. While it is nice to have a break from the coding assignments, I really would've loved to dive deeper into an assignment where we use JSON and APIs and can put what we learned in the readings to practice.
I think it would've been nice to have another example of calling an API, because this part of the content this week was technically challenging for me.
Additionally, instructions about hosting our website on a server locally would've be helpful.
	Thanks for the feedback! I did share some resources on hosting a server locally but it was on Piazza. I'll make sure to add them as resources for the unit.
I think I maybe could've used a little more information about JSON
I think it was nice to have a little bit of a break from coding our webpages, but after doing the tutorials I still feel like I didn't have a full understanding of how to make use of the capabilities AJAX provides, but the tutorial for the API was definitely helpful for my understanding.
For improvements, I think including more examples of real-world API integrations could help us see the practical applications and challenges of using third-party APIs.
I did want more resources on different ways to use ajax (w/ examples)
However, I wish we had been given more examples of how to host our websites for free, such as on GitHub. I ended up relying on my classmates to learn about hosting options.
The one thing I didn't like was the limited interaction with diverse hosting options. I think more detailed comparisons and tutorials on alternative hosting options could provide a broader understanding of deployment strategies. In addition, the peer review process could be more effective with more structured guidelines or rubrics, ensuring that feedback is consistent and comprehensive.
More practice or super simple examples of APIs and AJAX would have furthered my understanding; AJAX especially is a bit hard to understand, since it's so wordy, so getting more exposure to its common patterns helps it be less overwhelming.
I did appreciate the units that we were given an example schedule, it helped me stay on track.
I would have liked either a video option for third party API's or a reading that was easier to follow through/comprehend. Sometimes the readings have a lot of CS lingo I do not know because I am not a CS major and they get super hard to comprehend and follow.
The readings this week were a little hard for me to read. I think they just didn't capture my attention as much as others had so seemed like it was just a lot of memorizing definitions. 
Don't think there are any weaknesses, really enjoyed the example API showcased, having more examples would be cool!
One thing that could've been better was assigning us specific people's sites to look at - that way, everyone gets a good amount of feedback.
One area of improvement could be more visuals of examples of websites using those technologies.
I was not familiar at all with AJAX before this unit, so having a recorded lecture demoing AJAX would have been helpful.
I thought the content was good, but I would've liked to see more expansion on free hosting services (even though it wasn't the focus of the unit).
However, the unit could improve by providing more detailed tutorials on using APIs with AJAX and troubleshooting common deployment issues from the hosting services.
The only part of the unit that could use improvement is to possibly put in some notes about the big ideas from the denser readings beforehand so that it can allow me better grasp the material as I read through them.
-->
