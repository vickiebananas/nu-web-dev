---
title: 'Unit 9: Preserving state'
layout: post
unit: 9
---

<!-- **** | Final Project Presentations |-->

## Unit Essential Questions
You should use the questions below to assess your own learning and understanding of course material. These questions are also a good method of organization if you're taking notes.

### Cookies and Sessions
- What are cookies and what purpose do they serve?
- What are sessions and what purpose do they serve?
- What’s the difference between a persistent cookie and a session cookie and when should each be used?
- What're some legal considerations developers should be aware of when their sites use cookies?

### Future of cookies
- What might be the future of cookies? 

## Unit Readings

### Cookies and Sessions
- Read [All About Cookies](https://www.allaboutcookies.org/cookies/) and/or Watch [What Are Cookies? And How They Work](https://www.youtube.com/watch?v=rdVPflECed8)
- Read [Web security essentials](https://www.sohamkamani.com/web-security-basics/#sessions-and-cookies)(only read the 'Sessions and Cookies' sections) and/or Watch [Cookies vs Sessions Explained: What You Need to Know](https://www.youtube.com/watch?v=K4UKj5htg-E)
- Read [Using the Web Storage API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API/Using_the_Web_Storage_API) and/or Watch [JavaScript Cookies vs Local Storage vs Session Storage](https://www.youtube.com/watch?v=GihQAC1I39Q)

> #### Check your understanding
> If I store data on MyFakeSite.com using localStorage, close the browser, and then open a new window to visit MyFakeSite.com, will my data still be in my browser?
> <details>
>    <summary>Click here to reveal the answer!</summary>
>    Yes! localStorage has no default expiration so the data is stored even after you close the tab/window/browser. On the other hand, sessionStorage expires after a tab/window/browser is closed.
> </details>
##### Programming Exercise
> This optional exercise will have you practice with localStorage and sessionStorage.
>
> Complete the code in [this fiddle](https://jsfiddle.net/vcchavez_uri/s6b4c1j2/) to store the inputs to the browser and then display the results. You should only need to update the JS code inside the `saveInfo()` and `updateScreen()` functions. Notice the difference when using localStorage vs sessionStorage:
> - When using localStorage, the most recently used name and job should appear when you open the same fiddle in a new tab/window 
> - When using sessionStorage, `null` will show up in lieu of a name and job when you open the same fiddle in a new tab/window
>
> **Note:** While localStorage normally stores data indefinitely, because we're working through JSFiddle's servers (which for security clear out our storage) if you were to quit your browser completely and then re-open the fiddle, you wouldn't have the local data stored anymore. Hence, when testing your fiddle, make sure to simply open a new tab or window with the same link rather than closing the browser completely.
{: .block-tip}

### Future of cookies
- Read [Cookie Consent Requirements: Are You Doing Enough?](https://www.osano.com/articles/cookie-consent-requirements)
- Read [GitHub says goodbye to cookie banners](https://techcrunch.com/2020/12/17/github-says-goodbye-to-cookie-banners/)
- Read [Charting a course towards a more privacy-first web](https://blog.google/products/ads-commerce/a-more-privacy-first-web/)

### ExpressJS and Cookies [optional]
> The readings below might be particularly useful if you're planning on using NodeJS and working with something like user logins for your final project.
{: .block-tip}
- Read [ExpressJS - Cookies](https://www.tutorialspoint.com/expressjs/expressjs_cookies.htm) and/or Watch [ExpressJS Tutorial - Cookies](https://www.youtube.com/watch?v=eaVTbtRipjM)
- Read [ExpressJS - Sessions](https://www.tutorialspoint.com/expressjs/expressjs_sessions.htm)

{% for section in site.assignments %}
{% if section.unit == page.unit %}
## Unit Lab
{{ section.content }}
{% endif %}
{% endfor %}

## Additional Resources
### Cookies and Sessions
- Read [What are session cookies used for?](https://www.allaboutcookies.org/cookies/session-cookies-used-for.html)
- Read [What are persistent cookies used for?](https://www.allaboutcookies.org/cookies/persistent-cookies-used-for.html)
- Read [Using HTTP cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)
- Read [Window: localStorage property](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)
- Read [Window: sessionStorage property](https://developer.mozilla.org/en-US/docs/Web/API/Window/sessionStorage)
- Watch [Difference between cookies, session and tokens](https://www.youtube.com/watch?v=GhrvZ5nUWNg)

### ExpressJS and Cookies
- Watch *Learn how to create a simple login app using ExpressJS + sessions*: [Part 1](https://www.youtube.com/watch?v=BnLOTQP5tZk) and [Part 2](https://www.youtube.com/watch?v=DJSTXlbVGw4)