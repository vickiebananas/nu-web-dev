---
title: CSS Reference
layout: post
permalink: /css-reference
ordering: 4
date: 2025-06-23 00:00:00
---

CSS (Cascading Style Sheets) is a language that helps designers to control the look-and-feel of a website. CSS can be used to create layouts, font assignments, color schemes, margins and spacing, and even animations. Don't feel like you have to memorize all of these properties: the CSS vocabulary is expansive, and is best learned as you design your own creations. That said, knowing the rules that govern the CSS vocabulary is important to being able to use the language, so do take some time to ensure that you understand the *prose*.

---

{% for section in site.css_reference %}
{{ section.content }}

---

{% endfor %}

This reference guide [sourced from Dr. Sarah Van Wart](https://github.com/cs396-web-dev).
