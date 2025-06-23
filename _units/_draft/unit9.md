---
title: 'Unit 9: User Authentication & Databases'
layout: post
unit: 9
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