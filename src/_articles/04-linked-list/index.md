---
layout: page
title: Linked List
category: index
permalink: articles/linked-list/
---
    
## {{ page.title }}

We’ll look at a data storage structure that solves some of these problems: the linked list.

**Linked lists** are probably the second most commonly used general-purpose
storage structures after arrays.
The linked list is a versatile mechanism suitable for use in
many kinds of general-purpose databases. 
It can also replace an array as the basis for other storage structures
such as **stacks** and **queues**.

In fact, you can use a linked list in many cases in which you use an array, unless you need frequent random access to individual items using an index

### Examples in this chapter:

{% assign articles = site.articles | where:"category","linked-list" %}
<ol>
    {% for post in articles %}
      <li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
    {% endfor %}
</ol>