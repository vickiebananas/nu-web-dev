---
title: 'Unit 8: Preserving state'
layout: post
unit: 8
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


<!-- FEEDBACK
Everything worked well. However it would be great to have a project due this week in order to implement minor changes with the things learned in this Unit.

I think a strength of the unit was how concise and targeted the information was. The information focused solely on state management and did not deviate from that topic. In other units, the amount of topics covered could be overwhelming (unit 7 covering three different frameworks and many libraries), so this unit covering important information that was not overwhelming was a huge strength. One weakness of this unit could be the lack of coding assignment-related tasks. I find it helpful when learning concepts to get hands-on practice and I feel like having a task for implementing this into our sites could've been a great way to learn.

One weakness is that some of the concepts, like the differences between session management techniques and the future of cookies, were a bit complex and could have benefited from more detailed explanations or additional examples.

I found all the reading materials to be very helpful. These articles are highly relevant to the unit's topic and provide a thorough explanation of specific subjects, such as the different types of cookies. The "Check Your Understanding" section and the programming exercises were particularly useful in testing my understanding and allowing me to apply the concepts in real-world scenarios. Overall, I believe this unit is clear and effective, and I can't think of any improvements at the moment.

I think a lab would’ve been helpful to try out these concepts and check my understanding, but I also appreciated having extra time for the final project. Maybe there could be an optional lab to check understanding. 

The videos were really helpful in understanding the topics. How do I choose if I should use local or session for things like a shopping cart?

The unit provided clear explanations of key concepts like cookies and sessions, but it could benefit from more practical exercises to reinforce the learning.

This unit had some strong points, particularly in allowing us the flexibility to explore concepts without the pressure of a graded assignment. This freedom helped me engage more deeply with the material on my own terms. However, I feel that the learning experience could have been enhanced by including more hands-on resources, like sample code, for us to experiment with.

I think we needed more information on related tools and technologies such as management libraries or browser tools for storage inspection would have been better in terms of the practicality of the unit.

As always, the readings were easily digestible. The timeline you provided on canvas for where we should be in terms of our final project was also very helpful. 

Weaknesses: no practice outside of self-driven, not necessarily applicable to all or even most students' project situations, potentially overload of information if it's all unfamiliar (SQL alone can be annoying to learn/understand, and databases seemed pretty thrown in on top of the unit)

I don't really have any suggestions for improvement,  but I feel like in the final weeks, having one on ones with maybe TAs/instructors could be useful for helping us with our final project. Since we are focusing on that now for the last couple weeks, and even though OH exist, I feel like those one on ones could really help us hone in on ways that we could make our website great and stand out. But it is just a suggestion as I don't really have feedback as this unit was chill but very informational.

For a weakness, I struggled with creating interactive contact page so it took me a while to learn and make it functional. 

I think the unit was great at explaining all the topics that I need to know for browser storage. It would have been cool to have a deeper discussion on privacy concerns of cookies and storage APIs though. 

This unit was interesting because I have always been curious what cookies were! The readings were very digestible. I am glad I got to use this week to work on my final. It would be great if you could provide more resources on other features besides logging in like displaying data on a map for a website or something like that.

I think this unit was really well structured, and I understood that we didnt necessarily need a specific lab. Most people's choices about their websites dictated the need for storage here, and while it was important to learn for all of us, it perhaps wasnt necessary to implement for everyone.

One improvement could be adding more programming examples on deploying cookies.

- Besides this participation quiz, there’s really no benchmark, or checkpoint, for the final project. If you’re not managing your time well, you will definitely struggle.

I liked this unit overall. I think one thing that I found interesting that I wish had more clarification was the GDPR and how policy is affecting cookies (and how that’s even the case, eg. advertising data).

I think this unit could use more content that shows specifically how databases are used in websites. Otherwise, I enjoyed learning form the provided content.

One thing that could be used for improvement is if there could be for example, additional videos in the additional resources section that provide coding demos on the more in-depth coding examples given in the readings such as the "Using the Web Storage API" article. This would allow for visuals to also be provided for the more advanced examples given in the readings so that we can better explore those more advanced examples if we have time and are interested.

I thought the reading on web security was interesting. I think it would have been nice to do some sort of exercise that involved some of the things it talked about like xss or implementing cookies. But I liked the check your understanding and programming exercise. It was a nice way to do a hands on with the info we learned

I think the material was explained well this week but still could've benefited from visual aids.
-->
