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