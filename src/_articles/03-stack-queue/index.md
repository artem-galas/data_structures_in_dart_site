---
layout: page
title: Stack Queue
category: index
permalink: articles/stack-queue/
---
    
## {{ page.title }}

We’ll examine three data storage structures:
- stack
- queue
- priority queue.

### Examples in this chapter:

{% assign articles = site.articles | where:"category","stack-queue" %}
<ol>
    {% for post in articles %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ol>