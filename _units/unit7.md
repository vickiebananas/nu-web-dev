---
title: "Unit 7: Frameworks & Libraries, cont'd"
layout: post
unit: 7
date: 2025-08-01 00:00:00
---

## Unit Essential Questions
You should use the questions below to assess your own learning and understanding of course material. These questions are also a good method of organization if you're taking notes.

### Server-Side Programming
- What is server-side programming and what purpose does it serve?
- Which frameworks require server-side programming and how can you tell?

## Unit Readings
### Server-Side Programming
If you're using React, Node, or an API, you might already be familiar with setting up a local server to test your site. However, let's dive more deeply into the uses and purposes of server-side programming.
- Read [What is a web server?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/What_is_a_web_server) and/or Watch [Servers: What are they?](https://www.youtube.com/watch?v=toLnp3PJVVA)
- Read [Introduction to the server side](https://developer.mozilla.org/en-US/docs/Learn/Server-side/First_steps/Introduction) and/or Watch [Static vs Dynamic Websites](https://www.youtube.com/watch?v=4sP7fp3cp24)
- Read [Client-Server Overview](https://developer.mozilla.org/en-US/docs/Learn/Server-side/First_steps/Client-Server_overview) and/or Watch [Client Server Architecture](https://www.youtube.com/watch?v=h-n_gyyNly8)
- Read [Server-side web frameworks](https://developer.mozilla.org/en-US/docs/Learn/Server-side/First_steps/Web_frameworks)

{% for section in site.assignments %}
{% if section.unit == page.unit %}
## Unit Lab
{{ section.content }}
{% endif %}
{% endfor %}

## Additional Resources
### Internet Basics & Servers
- Read [How the Web works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
- Read [Internet Basics - What is the Internet?](https://edu.gcfglobal.org/en/internetbasics/what-is-the-internet/1/) and/or Watch [What is the Internet](https://www.youtube.com/watch?v=Dxcc6ycZ73M)
- Read [Internet Basics](https://fcit.usf.edu/internet/chap1/chap1.htm) and/or Watch [Where does the Internet come from?](https://www.youtube.com/watch?v=jKA5hz3dV-g) and [The Internet: IP Addresses & DNS](https://youtu.be/5o8CwafCxnU)
- Read [What is the Internet Protocol?](https://www.cloudflare.com/learning/ddos/glossary/internet-protocol/) and/or Watch [The Internet: IP Addresses & DNS](https://www.youtube.com/watch?v=5o8CwafCxnU)

### Server Side Programming
- Read [Client-Side vs. Server-Side](https://skillcrush.com/2012/07/30/client-side-vs-server-side/)
- Read [Static v Dynamic Website Design](https://www.spiderwriting.co.uk/static-dynamic.php)

<!-- FEEDBACK
I would add the example on how to post on github (readme guide or something like that)

The biggest strength of this unit would be the content that it covered. Knowing how to use cloud computing platforms for hosting is pretty essential for many positions in the tech industry. Another big strength would be the support resources listed at the bottom of the unit page. I found that these resources were helpful in understanding the fundamentals of how hosting works which helped with debugging many issues. One weakness I would say is that the recorded lecture only shows how to upload to google cloud platform using node. I found that to be less helpful for me specifically and ended up running into many issues when reproducing the Professor's steps. I think having more video walkthroughs for this process would very helpful

For the lab guide, we didn't get in-depth guidance for more advanced deployment scenarios. For example, students using server-side technologies or more complex frameworks may have found the instructions less helpful. Including more advanced topics such as continuous deployment pipelines, server management, and handling domain registrations could further help our learning experience

The only thing I think it can improve it that maybe have more troubleshooting guidance for common issues during deployment even it has already have some debug explanation in video.

One weaknesses of this unit is that when setting up my server, I was a little confused about the purpose of the updates we were making to the package.json and I didn't really feel like that was explained. 

The video lecture was helpful, but I wish it showed the actual folders and makeup of the project being deployed. When i tried to find resources online, I felt like there was a lot of general advice, when I felt like I had a specific issue. Overall, it was a steep learning curve, but reading through many documentations and watching different youtube tutorials helped explain the concepts and my issues.

I think I prefer it when there are more essential questions at the beginning so I know what to look for and what's most important

I thought the unit was good. It was difficult trying to get it deployed but each case is unique so there isn't much more resources that could be provided.

It provides diverse learning resources, such as readings, videos, and lectures, to accommodate various learning styles. However, some concepts may be challenging for beginners, and the unit could benefit from including more advanced topics, like security practices. 

The biggest strength of this unit was the recorded lecture for me; it helped me.a good amount with understanding what should be done and how. The biggest weakness of this unit, which could be a strength for others, was that I prefer a more structured goal for what to accomplish in the given week. Once we began using API's and different libraries it felt a little daunting to come up with various ways to implement what we learned into our project. However, this open ended aspect could also be looked at as a positive, so maybe just more resources on what examples might look like could've been helpful. 

The unit lacked the ability to download example code snippets or complete projects. Having downloadable code would be extremely beneficial for learning and troubleshooting, allowing students to compare their work with working examples.

There were limited resources and tips for troubleshooting common issues encountered during the hosting process. A dedicated troubleshooting guide would help students resolve issues more efficiently.

The recorded lectures and video tutorials for hosting on platforms like Google Cloud were not sufficient. The video tutorial, in particular, was not helpful. 

The hands-on assignments, such as finishing the framework/library integrations and hosting the site, were instrumental in applying theoretical knowledge. 

I think the readings were very prompt and in depth, but as someone who is personally more visual. I really wish that there were more videos. 

The nature of the assignment allowed for hands-on experience by creating a real-world application. Offering multiple hosting options (InfinityFree, GitHub Pages, Google Cloud, AWS, Azure) allowed for flexibility and exposure to various platforms. However, there was no detailed way of telling which platform was better. In addition, more detailed guidance on troubleshooting common deployment issues could be helpful. In general, this unit would be better if we had it as a group project rather than an individual one.

This unit felt like a totally necessary continuation of the previous one, but at the same time, mostly feels like just extra information. I understand that we're supposed to be working on the site or our final projects, but our sites have been basically finished or nearly finished for weeks, it seems. This course feels overly compressed and condensed - not a bad way to get a fast taste of web dev, but it would be much more impactful as a multi-course sequence for those interested in actually learning the material fully. 

I liked that the unit introduced me to a bunch of different frameworks, rather than just one (eg, just React). It was a useful exercise in picking the right tool. I don't think the unit had any weaknesses!

Weakness: There was no example integration with a framework in the lecture. 

Could include more hands-on exercises or step-by-step guides for common hosting scenarios

i would have liked more specific and updated resources on the frameworks we could've used. like a step by step thing.

Again, I think more specific lecture goals and things to do accompanying the lecture would've been helpful.

A strength was the flexibility of where I could host my website, I used Github Pages but there were many options available, with lots of helpful discussion and suggestions on Piazza. Another strength was the resources, especially the bonus resources that talked about the Internet, they were very interesting. 

I think some more guidance on the different services to use like AWS, Azure, etc would be a bit more helpful. However, I liked the readings - they were short, simple, and useful.

Weaknesses - at this point work was very individual (i.e. we got to choose which frameworks we used, weren't following a "syllabus" as much anymore) so it may have been hard for students to get individualized help

- I loved the freedom we had. We were able to freely pick what was best for us, and managed to polish up our websites. However, for this unit we did not have any aspect of storage or some way to store our user's preferences, which I imagine some people may have anticipated they need when we started the quarter and made decisions for what websites to make.

I thought that this unit was helpful, but if anything, it could have included slightly more content. I think it would have been nice if we were introduced to only the most common Frameworks (Node, React, etc.) last week, and then were given the freedom to explore whichever frameworks we wanted to this week. 

what could have improved would be setting it up using github pages. I saw a video on it but i think a tutorial could have been linked there

It was confusing that this lab asked us to host our website when Unit 5 Lab already had us do that. I simply had to commit my changes to my existing repository to have Github Pages update my website.

This unit taught me a lot about the differences between static and dynamic sites. I wish there was more information about how to implement dynamic features.

I thought this lab was not as clear as previous labs, meaning what we supposed to actually do. It seemed really similar to last lab.

One thing that worked well for this unit was the accompaniment of shorter YouTube videos after the longer and denser readings. The videos acted like summaries and allowed for me to better understand and grasp the material. On the other hand, one thing that could use improvement is that I may have been more helpful if the "Additional Resources" section could be more related to the unit lab and be more on additional resources about platforms that we can deploy our websites on so that there is the same amount of guidance if we do not choose to use Google Cloud as in this week's recording. 

This unit talked mostly about web vs client servers which gave me some more useful background on how they work. However, I think I was still trying to implement some functionalities so I was looking more at libraries and packages to help. For example, I included an image carousel and ended using bootstrap styling

I think there could've been a little more guidance on the specifics of hosting a website
-->
