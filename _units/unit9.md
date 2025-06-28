---
title: 'Unit 9: User Authentication & Databases'
layout: post
unit: '9'
date: 2025-08-15 00:00:00
---

## Unit Essential Questions
You should use the questions below to assess your own learning and understanding of course material. These questions are also a good method of organization if you're taking notes.

### User Authentication & Authorization
- How do sessions help keep track of users and their logins?
- What's the difference between user authentication and user authorization?

### Databases
- What's a database?
- What's a relational database management system?
- How are databases used to store user logins and sessions?

## Unit Readings
### User Auth
- Read [Understanding User Authentication in your Web App and how to implement it](https://medium.com/@albert.kim/understanding-user-authentication-in-your-web-app-and-how-to-implement-it-part-1-the-high-level-ab91336ab77c)
	- As a refresher, it might be helpful to Read [Cookies-Based Authentication Vs Session-Based Authentication](https://dev.to/emmykolic/cookies-based-authentication-vs-session-based-authentication-1f6)
- Read [Authentication vs Authorization – What's the Difference?](https://www.freecodecamp.org/news/whats-the-difference-between-authentication-and-authorisation/) and/or Watch [Auth Does NOT Have To Be Hard](https://www.youtube.com/watch?v=mL8EuL7jSbg)


### Databases
- Watch [What is a Database?](https://www.youtube.com/watch?v=hRulZhTtUTg)
- Read [SQL vs MySQL: A Simple Guide to the Differences](https://www.dataquest.io/blog/sql-vs-mysql/)
	- For a more in-depth reading with additional database technologies, Read [SQL vs. MySQL: Differences, Similarities, Uses, and Benefits](https://www.coursera.org/articles/sql-vs-mysql)

> Note: While large companies often maintain their own authentication systems and databases, for most daily purposes you'll likely find it much easier (and safer) to use existing authentication tools for your web apps. Some tools of interest may include:
> - [Auth0](https://auth0.com)
> - [Sign in with Google for Web](https://developers.google.com/identity/gsi/web/guides/overview)
> - An [SSO Provider](https://en.wikipedia.org/wiki/List_of_single_sign-on_implementations)
> - [8 Open Source Authorization/Authentication (OAuth) Solutions for Your Next Project](https://geekflare.com/open-source-oauth-solutions/)
> - [13 User Authentication Platforms](https://geekflare.com/user-authentication-platforms/)
> - [The 10 Best Free and Open-Source Identity Management Tools](https://solutionsreview.com/identity-management/the-best-free-and-open-source-identity-management-tools/)
{: .block-tip}

{% for section in site.assignments %}
{% if section.unit == page.unit %}
## Unit Lab
{{ section.content }}
{% endif %}
{% endfor %}

## Additional Resources
### User Auth
- Read [Secure User Authentication Methods – 2FA, Biometric, and Passwordless Login Explained](https://www.freecodecamp.org/news/user-authentication-methods-explained/)
- Read [How to Authenticate Users in Your Node App with Cookies, Sessions, and Passport.js](https://www.freecodecamp.org/news/authenticate-users-node-app/)
- Review [Web App Security/Authentication Playlist](https://www.youtube.com/playlist?list=PLZlA0Gpn_vH9yI1hwDVzWqu5sAfajcsBQ)
- Watch [React Authentication in 5 Minutes](https://www.youtube.com/watch?v=vFHGDaMO-0M)

### Databases
- Review [Tutorial - An Introduction to Queries in MySQL](https://www.digitalocean.com/community/tutorials/introduction-to-queries-mysql)
- Review [(My)SQL Cheat Sheet](https://cusack.hope.edu/ShowFiles/SQL/CheatSheet/SQLCheatSheet.html)

<!-- FEEDBACK
A weakness on the other hand would be the lack of hands-on learning, specifically for databases. This unit contains extremely useful information which is why having a dedicated assignment for this would be super helpful to learn more.

I think it could've been good to have maybe an extra credit exercise or a lecture to motivate people to look into the material - I read about it a lot because I'm interested in web dev but maybe that would be nice!

I loved that this unit wasn't too long, and discussed key topics (especially authentication and authorization)! In terms of databases though, I think more sources can be provided on databases beyond MySQL.

However, since this is my first time learning about these topics, I think it would be even better to have more hands-on activities to practice what I’ve learned. Interactive exercises or practice problems would make it easier to understand and remember the information.

Although I appreciated the break from a lab assignment, I think a lab could’ve been good practice for this week’s assignments instead of just reading content. 

The unit's strengths include its wide range of resources and focus on practical application. The different readings, videos, and tutorials help us understand user authentication and databases. However, the long list of resources can be overwhelming, making it hard to know which ones are most important. Also, the unit could improve by adding more interactive elements, like quizzes or coding exercises, to better reinforce the material.

It was good. One suggestion I have is it would be better to show the importance of proper user authentication.

On the other hand, I think we needed more hands-on exercises by including the implementation in one of the lab assignments. It might have been beneficial to dive deeper into modern authentication tools. 

I think this unit was good, could use some more examples of databases and their uses.

I liked this unit's topics a lot; I found user login and authentication to be a very interesting topic. An issue I had was that I didn't quite grasp the information in this topic and I thought a lot of the resources given were surface-level, and had to resort to a lot of other resources, such as ones other classmates posted in Piazza to quite understand what was going on.

While SQL and MySQL were covered, the unit could have benefited from more information on NoSQL databases for comparison.

The information was good for learning about user authentication and databases, but it may have been helpful to have more hands-on experience with the material as we have had in previous units.

The topics are good, but I think practical examples would be helpful again. Also some of the resources seem a bit questionable/high level. (like is SQL vs MySQL really a confusion?)

    I liked the readings and videos that were provided for this unit. I actually took a course that used a little SQL and we didn't have time to get into MySQL so I liked that in this lab the difference between the two were explained. 

I don't think much could use improvement but maybe a live demo would be nice. 

However, I wish we could have maybe had a more in depth tutorial on how to apply this stuff to a website.

I do feel like the final project makes it tough to apply some of this stuff

My one critique is that I think there could have been more practice with SQL, because I think the language starts to make much more sense when you start working with practice databases. Other than that, everything was great. 

I think one improvement could be adding more tutorials on authentication through different frameworks.

Not really a weakness but having a class lecture relating to the content would have been a nice plus.

One thing that could use improvement, is that for the entire course, it would be nice if the course included a series showing how an example site is gradually improved each week. New concepts from each unit, like user authentication for this week, could be added to the site step by step. This would make the material feel more concrete and help solidify my understanding through practical examples, rather than just abstract explanations.

I liked the topics of this week's unit. However, I wish there was more hands on practice with them like a demo, especially since my app didn't need a database or user authentication functionality  so I would not get to implement them in my final project. 

I liked that there are many checkpoints to ensure that we stay up to date with our website. The discussion page to post website was also very helpful to hear what others have to say about my current website. 

It is good to see the material involves some backend work to make the website more functional and robust, but I feel it may not be enough if some students really want to integrate this into their projects as backend is kind of out of scope and may requires more-than-one-week work. But still good to see them mentioned.
-->
