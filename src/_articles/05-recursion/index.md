---
layout: page
title: Recursion
category: index
permalink: articles/recursion/
---
    
## {{ page.title }}

Recursion is a programming technique in which a method (function) calls itself.

### Examples in this chapter:

{% assign articles = site.articles | where:"category","recursion" %}
<ol>
    {% for post in articles %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ol>