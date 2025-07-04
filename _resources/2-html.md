---
title: HTML Guide
layout: post
ordering: 3
permalink: /html-reference
date: 2025-06-23 00:00:00
---

HyperText Markup Language, commonly abbreviated as HTML, is the standard markup language used to create web pages and web applications. It is typically used in conjunction with CSS (for styling and layouts), and JavaScript (for interactivity).

HTML files control the content and structure of a web page. These files are text files that gets interpreted by a web browser (such as Safari, Chrome, and Firefox). For example, when you surf the web in your daily life and open a new web page, your browser pulls an HTML text file down from a server, interprets it, and then renders (draws) the resulting web page on the screen, according to the instructions in the HTML file (Source: [ASP Overview](https://learn.microsoft.com/en-us/previous-versions/iis/6.0-sdk/ms524929(v=vs.90)?redirectedfrom=MSDN)).

As you begin writing your own HTML files, keep in mind that what you're really doing is writing *browser instructions* in one of the languages (HTML) a browser can understand. Therefore, you have to understand the *rules* and *vocabulary* of the language in order to create effective HTML browser instructions (files). In many ways, learning HTML is a lot like learning any other language, and is best learned "in context," and through practice – much like many language immersion programs (Spanish, Chinese, French, etc.) are taught.

Learning HTML requires three main kinds of knowledge:
1. An understanding of the general rules for using the language, including understanding how to use ***tags***, ***attributes***, ***values***, and ***content*** (text and/or nested HTML tags) correctly. Think of these skills as **HTML grammar.**
2. An understanding of some of the core tags of the language, and what they do. Think of these skills as **HTML vocabulary**.
3. Finally, an understanding of **how to seek out and effectively use information and resources**.

---

{% for section in site.html_reference %}
{{ section.content }}

---

{% endfor %}

This reference guide [sourced from Dr. Sarah Van Wart](https://github.com/cs396-web-dev).
