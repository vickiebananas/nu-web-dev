---
title: 'Unit 6: Frameworks & Libraries'
layout: post
unit: 6
---

## Unit Essential Questions
You should use the questions below to assess your own learning and understanding of course material. These questions are also a good method of organization if you're taking notes.

### Client-Side Frameworks
- What is a client-side framework and what purpose does it serve?

### NodeJS and Asynchronous Programming
- What’s the difference between sync vs async code?
- What is NodeJS and how can it be used?
- What’s the difference between blocking vs non-blocking code and sync vs async code?

### React (a.k.a. ReactJS)
- What is ReactJS and how can it be used?

### Jekyll
- What is Jekyll and how can it be used?

## Unit Readings
### Client-Side Frameworks
Before we try to use any frameworks, we should clarify what a framework actually is and what purposes it serves.
- Read [Introduction to client-side frameworks](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/Introduction) and/or Watch [JavaScript frameworks explained in 90 seconds](https://www.youtube.com/watch?v=VbvMJUpY0a4)
	- Note that while some folks, including the video above, include jQuery as a 'framework', it's technically a *library*. BootStrap, which we've also learned about, is also a library. Knowing the distinction between libraries and frameworks isn't too important but when in doubt, refer to documentation and use the language the developers of the library or framework use. To learn more about 'inversion of control', which is the technical determining factor between libraries and frameworks, read [The Difference Between a Framework and a Library](https://www.freecodecamp.org/news/the-difference-between-a-framework-and-a-library-bd133054023f/).

### NodeJS and Asynchronous Programming
So far, we've been focusing exclusively on client-side programming. Client-side programming enables us to display pre-created content on a browser-- think of how you have to fully code your site line by line for it to show up on your browser. With client-side programming, even if you add dynamic behaviour to your site such as a dark mode, for example, you have to code exactly what that means before it's actually available to the user. Server-side programming allows us to dynamically create and receive content-- not just display it. That means that not only can we change what the user has access to, but the user can also communicate with us and our code. Using APIs is an example of server-side programming, which is why if you try to perform an API call locally by simply opening your code file, you'll get an error; to successfully make an API call from a local page, you have to run a local server. 

Given that many frameworks, including NodeJS, make use of asynchronous programming, it's helpful to have a basic understanding of what asynchronous programming is and how to utilize it correctly. That being said, you don't need to be an expert on asynchronous programming. However, the more comfortable you are with these ideas, the easier debugging will be. We've actually already used async JavaScript: when we worked with `fetch()` for connecting to APIs.
- Read [Introducing asynchronous JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Introducing) and/or Watch [Asynchronous Vs Synchronous Programming](https://www.youtube.com/watch?v=Kpn2ajSa92c)

NodeJS, a popular JS framework, allows us to create a server environment. NodeJS is especially popular-- and powerful-- because of its use of non-blocking asynchronous programming which make it particularly memory efficient and fast. If you're familiar with threading, the concept of blocking and non-blocking code may be familiar. As we learned above with asynchronous programming, sometimes we want our code to perform multiple actions at once. However, if a task is taking up all the available bandwidth of our computer, we won't be able to simultaneously perform another task. Here is where NodeJS is especially impressive: it uses a single thread and still performs non-blocking asynchronous programming!
- Read [Explain non-blocking I/O like I’m five](https://blog.codecentric.de/en/2019/04/explain-non-blocking-i-o-like-im-five/) (stop reading after finishing “Benefits of non-blocking I/O”) and [Overview of Blocking vs Non-Blocking](https://nodejs.org/en/docs/guides/blocking-vs-non-blocking/) and/or Watch [Non-blocking I/O and how Node uses it, in friendly terms](https://www.youtube.com/watch?v=wB9tIg209-8)

### React (a.k.a ReactJS)
React is a library (though many refer to it as a framework) that allows you create *components* or parts of a webpage that can be reused across your site. React is very popular as a means of reducing code repetition.
- Read [Getting started with React](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/React_getting_started) and/or Watch [What Is React (React js) & Why Is It So Popular?](https://www.youtube.com/watch?v=N3AkSS5hXMA)

### Jekyll
Similar to React, Jekyll also allows you to break up your HTML into subparts that can be reused across a site. Rather than using JS like React does, it relies on Ruby. However, web developers don't need to know Ruby to program their pages and can use Markdown, HTML, CSS, and Liquid to develop their sites. Additionally, Jekyll is fully supported by Github Pages which allows you to host a site for free. 
- Read [What is Jekyll? - A Complete Guide by Tiiny Host](https://tiiny.host/blog/what-is-jekyll-a-complete-guide-by-tiiny-host/) and/or Watch [Introduction Jekyll - Static Site Generator](https://www.youtube.com/watch?v=T1itpPvFWHI)

{% for section in site.assignments %}
{% if section.unit == page.unit %}
## Unit Lab
{{ section.content }}
{% endif %}
{% endfor %}

## Additional Resources
### Node
- [Node.js Documentation](https://nodejs.org/api/)
- [Node.js Notes for Professionals book](https://books.goalkicker.com/NodeJSBook/)

### React
- [React Documentation](https://react.dev/learn)
- [ReactJS Notes for Professionals book](https://books.goalkicker.com/ReactJSBook/)

### Jekyll
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [Liquid Documentation](https://shopify.github.io/liquid/)

<!-- FEEDBACK
Everything worked well. However more examples with various libraries would be great.

. I felt that a weakness of this unit was the lack of clarity in instructions. I was not entirely sure how in-depth I should be going into when recording the video going over my project and was also unsure of what counts as showing our setup and installation. I think more clear guidelines for the submission would've been more helpful.

For weakness, I think I had some initial setup challenges, such as resolving dependency issues or configuring the development environment. Maybe more detailed setup instructions or troubleshooting tips can help.

Regarding weaknesses, I think it would be helpful to have some demos or optional exercises for different libraries, as most of them are new to me.


I loved the flexibility with the frameworks and libraries, but the videos I watched for React only really scratched the surface of what I was looking for. That was probably for the better so I could go and learn a lot more about React, but I was really reliant on outside sources.
	I only posted very introductory videos but the channels I choose videos from have more in-depth videos so that's a great place to start!

I thought this unit was helpful and allowed room for exploration. I think the lab could have been more structured as I felt it didn’t exactly necessitate the thorough usage and implementation of the frameworks. 

I really enjoyed the tutorial videos for NodeJS, they really helped me implement NodeJS with my website. I didn't find the videos on ReactJS to be as helpful and had to find other videos and tutorials.

I wish there had been more information on how to install Node.js, but overall, the workload was manageable.

I found the unit as a well-rounded introduction to essential frameworks and libraries, covering both client-side and server-side technologies, which is crucial for full-stack development (something I didn't find in other classes at Northwestern). Moreover, the inclusion of readings, videos, and tutorials caters to different learning styles and provides multiple avenues for understanding complex concepts. However, the unit covers a lot of ground, which might be overwhelming for beginners. In my opinion, it needs to be broken down into more digestible parts or focus on fewer topics in more depth. 

I think a support video can be useful for students. This support video could be for React because its the most popular framework. The video could be a walkthrough implementing an example feature on a website. Students could then gain inspiration or learn how to implement their own features based on this example.

Weakness: I would've appreciated more text resources on React.

Live demo of installation or direct links to installation demo would be helpful

Some of the material, especially around asynchronous programming, could have been explained in more depth for those who are newer to the concepts.

I think that resources could've been more informative on how to download and use the frameworks. I tried with both Jekyll and React, and I couldn't find information on the resources given on how to properly install or operate them. I had to ask friends for help. 

1. More practical assignments would’ve been appreciated. The links are helpful, but i do learn a bit less.

2. I think picking a framework and going more in-depth on it would’ve been helpful. The links to all the different frameworks felt a bit overwhelming.

What made it initially confusing to me was that we could just choose whatever library we wanted and I didn't know what to pick or why to pick it but again, with some research it was fine.
	idea: add a comparison table or a TLDR of "if you want to do X, Y might be a good fit"

I usually like the lecture walk throughs, but we did not have a specific lecture walk through this unit.

I really liked the explanations given to all the topics of the lab, not just from the linked resources, but also the in-lab paragraphs, such as the one for NodeJS and Asynchronous Programming. Another strength was the variety of libraries and frameworks that were mentioned, as well as the tutorials for some of the main ones. Can't think of a weakness,

One thing that could improve is maybe learning about frameworks and libraries early - a lot of them have cool applications that would've been nice to take into consideration earlier.

I think maybe starting to work on these frameworks and libraries last week would have been a good idea? Because this was kind of a lot of information to process in a week. That being said, I found all of the supplementary videos provided by the professor to be super helpful. I really loved how she broke it down that way, as opposed to making one long lecture video

Weaknesses - wish there was more walk through on how to integrate react/next with an already created html repo because the tutorials emphasized "create react app"

I really enjoyed this unit, because I think it gave us a lot of freedom to implement what we thought to be most helpful for our sites. However, I think a little more direction could have been nice, as I know that some of these tools are more industry standard than others, and even if they wouldn't necessarily be our top choice for our personal sites, could still be worth practicing. 

I feel better tutorials could have been given for going from HTML and CSS to a framework

I wish we had the option to scrap and restart our website designs For example, mid-way through the unit labs, I wanted to do a personal portfolio instead, but there wasn't enough time in the week for me to restructure my entire website. If I had known from the beginning that the website we were developing was going to be used throughout the entire quarter, I would've thought more carefully about what kind of website I wanted to create. 

I had to spend a lot of time learning what each of the libraries/frameworks could be used for. For instance, I was not initially familiar with Jekyll.

The unit readings and videos given this week did a good job explaining to me the chosen frameworks and libraries. However, it took me a while to figure out how I was suppose to implement them to my website.

One thing that worked well for this unit is the detailed notes that came before each of the unit readings. They provided somewhat of a brief overview that allowed me to anticipate the content and identify key points to focus on. This really helped me to better understand the content and material from the readings. One thing from this unit that can be improved upon is that many of the provided materials such as the React support videos and the Express Handlebars playlist show examples using old/outdated versions or nonexistent platforms such as the Glitch React Start Kit. This made it difficult for me to follow along with those videos as I was doing my unit lab. It would be nice if in later units the materials can be reviewed to ensure they discuss and show examples on existing and recent versions before being posted on the course page.
	I spend a lot of time going through videos to find appropriate ones and unfortunately, sometimes the ones that have the best explanations are a bit outdated.

I had a little difficulty following along with the Node.js demos because of the lack of contrast on the page. I ended up using express and following along with those demos which worked better. But overall thought the demos did a good job of walking us through how to setup. I also thought the NodeJS notes for professionals pdf was helpful.

I like the reading of explaining non-blocking I/O like I am five, it is really vivid and helps me to pick this up quickly. I also know more useful libraries/framworks by reading through the unit reading. It was good overall but could be better if we have more step by step guides for integrating curret code into React.

I think more explanation within the module or a video from the instrucotr could've been helpful.

IDEAS:
	- It's difficult finding the right balance between throwing y'all into the deep end and making sure you all know how to swim!
	- detail importance about learning to do research and follow documentation to implement specific featues and do downloads and installs
-->
