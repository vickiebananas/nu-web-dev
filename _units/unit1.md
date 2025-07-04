---
title: 'Unit 1: Intro'
layout: post
unit: '1'
date: 2025-06-23 00:00:00
---

## Unit Essential Questions
You should use the questions below to assess your own learning and understanding of course material. These questions are also a good method of organization if you're taking notes.

### Design & Accessibility
- What is good design?
- What are the basic principles of design?
- What should I keep in mind as I design and develop my site?
- Why is it important my sites are accessible to *everyone*?

### Web Development Setup 
- What is the process for designing and developing a site?
- What is a wireframe and why is it important?
- What's the difference between a webpage and a website?
- What is a URL made up of?
- What is a domain name registrar?
- What is web hosting?
- What is domain privacy?


## Unit Readings
### Design Principles
- Read [The Principles of Design and Their Importance](https://www.toptal.com/designers/ui/principles-of-design)
 and/or watch [The Principles of Design](https://www.youtube.com/watch?v=ZK86XQ1iFVs)
- Watch: [5 Website Design Hints. Web Design Tutorial For Beginners](https://www.youtube.com/watch?v=j2G1IUpRiPY)

### Accessibility
- Read: [UX and the Importance of Web Accessibility](https://www.toptal.com/designers/ui/importance-web-accessibility)
- Watch: [Introduction to Web Accessibility and W3C Standards](https://www.youtube.com/watch?v=20SHvU2PKsM)
- Read: [Supreme Court allows blind people to sue retailers if their websites are not accessible](https://www.latimes.com/politics/story/2019-10-07/blind-person-dominos-ada-supreme-court-disabled)
- [The Ultimate Web Accessibility Checklist](https://www.accessiblemetrics.com/wp-content/uploads/2018/10/Accessible-Metrics-Campaign-Content-Offer.pdf)
- [Accessibility posters](https://ukhomeoffice.github.io/accessibility-posters/)


### Web Development Setup 
#### Wireframes
- Read [What is wireframing?](https://www.experienceux.co.uk/faqs/what-is-wireframing/) and/or watch [What is a Wireframe?](https://www.youtube.com/watch?v=T0vt3nLZKks)
- Read [Sketch, Wireframe, Mockup, and Prototype: Why, When and How](https://uxplanet.org/sketch-wireframe-mockup-and-prototype-why-when-and-how-29a25b3157c4)
- Review: [Sample wireframe](https://justcoded.com/wp-content/uploads/2019/02/difference-between-mockups-wireframes-and-prototypes.png)

#### Domains
- Read [Anatomy Of A URL](https://web.archive.org/web/20240615100723/https://websitebuilders.com/how-to/web-at-a-glance/url-anatomy/) and/or watch [Parts of the URL](https://www.youtube.com/watch?v=3ytQJvqzKu8)
- Watch: [What Is The Difference Between A Domain Name And A Website?](https://www.youtube.com/watch?v=BVoxVX__AdU)
- Read [What is domain privacy and do I really need it?](https://hostpapa.blog/security/domain-privacy-really-need/) and/or watch [What is Domain Privacy?](https://www.youtube.com/watch?v=UTcf0ryy3F0) (ignore the sales pitch)

#### Hosting
- Read [Web Hosting Explained for Beginners](https://www.hostinger.com/tutorials/what-is-web-hosting/) and/or watch [What is Web Hosting?](https://www.youtube.com/watch?v=qaMf4hHR2hg) (ignore the sales pitch)
- Read: [What’s the Difference Between Domain Name and Web Hosting (Explained)](https://www.wpbeginner.com/beginners-guide/whats-the-difference-between-domain-name-and-web-hosting-explained/)


{% for section in site.assignments %}
{% if section.unit == page.unit %}
## Unit Lab
{{ section.content }}
{% endif %}
{% endfor %}

## Additional Resources
Below are some additional resources specific to this unit. Even more additional resources are available under the "Resources" tab of our site.

- Read [27 Research-Backed Web Design Tips: How to Design a Website That Works](https://www.orbitmedia.com/blog/web-design-tips/)
- Read [Prototyping 101: The difference between low-fidelity and high-fidelity prototypes and when to use each](https://blog.adobe.com/en/publish/2017/11/29/prototyping-difference-low-fidelity-high-fidelity-prototypes-use)
- Read [How to Choose a Domain Name](https://websitesetup.org/choose-domain-name/) and/or watch [8 Rules for Choosing a Domain Name](https://www.youtube.com/watch?v=8r4Z3PizZ9g)
- Some Example Interface Builders:
	- [Sketch](https://www.sketch.com)
	- [Origami](https://origami.design)
	- [Proto](http://proto.io)
	- [Marvel](https://marvelapp.com)
	- [Figma](http://figma.com)
	- [Balsamiq](https://balsamiq.com)
	- [Adobe XD](https://www.adobe.com/products/xd/learn/get-started/what-is-adobe-xd-used-for.html)
	- [PowerPoint / Google Slides](https://medium.com/@keynotopia/how-to-use-powerpoint-as-a-ui-prototyping-tool-cca0491b2be5)

<!-- FEEDBACK
one more resource on wireframes-- perhaps of how to actually make one
 
However, this was a huge breadth of knowledge and I found it difficult to fit together the ideas of domain privacy and registrar with the design principles material. Perhaps a one page unit guide that shows how the pieces fit together would help me understand the material more deeply. In addition, I found the Web Hosting explanation articles to be pretty similar — curating one link for the concept would help with learning. 

In the essential questions, I noticed a couple questions are combined together like "What is a wireframe and why is it important?" Breaking these questions down into separate prompts would help me reflect on my learning more clearly.

For what could use improvement, we had resources on what to use for wireframing but there were no resources on how best to use them. I think because of this, most people would resort to hand-drawn wireframes as they would spend time learning how to use the suggested wireframing tools.
	For the assignment, I think directing us towards a certain wireframing tool or quickly highlighting differences between tools may have been helpful.

there was a lot of information and I think one unifying paragraph/page could've helped synthesize it

More concrete wireframe examples

I would have appreciated more concrete/direct resources to aid with the lab, as I feel like effective wireframing is perhaps not as intuitive as is implied by the current resources. Maybe a recorded demo of doing partial wireframing would be helpful, showing how some common tools are used and some frequently occurring challenges people encounter when wireframing.

The content on web hosting / domains felt a little too surface-level to be useful. I know it's not the focus of the course, but I would've appreciated more details (or at least links to more details).

a FAQ-type sections to address commonly-asked questions which may help for future iterations of the class.

timeline / ETA for completion 

I think it would be cool if there was a bookmark list or table of contents in the lecture so that we knew what each part of the video entailed and we can go to those parts for future reference.

Another suggestion that I have is how in the recorded lecture, it would be especially helpful if there could be a demo similar to what we'll do for the unit lab. For instance, demoing how wireframes are drawn and connected between each other would allow me to have a better understanding of what to do and get out of the labs for each unit.
-->

<!-- ### Testing Accessibility

- How can I ensure my sites are accessible to everyone?

- Read: [The 6 Simplest Web Accessibility Tests Anyone Can Do](https://karlgroves.com/2013/09/05/the-6-simplest-web-accessibility-tests-anyone-can-do)
- Watch: [How I do an accessibility check -- A11ycasts #11](https://www.youtube.com/watch?v=cOmehxAU_4s)
- Check out [W3C's Markup Validation Service](http://validator.w3.org/) -->
