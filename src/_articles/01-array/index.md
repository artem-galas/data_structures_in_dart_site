---
layout: page
title:  "Array"
category: index
permalink: articles/array/
nextpage: 
    url: 1-low_array
    title: Low Array
---

## {{ page.title }}

The array is the most commonly used data storage structure; it’s built into most programming languages. 
Because arrays are so well known, they offer a convenient jumpingoff
place for introducing data structures and for seeing
how object-oriented programming and data structures
relate to one another.

We’ll examine a special kind of array, the ordered
array, in which the data is stored in ascending (or descending)
key order.
This arrangement makes possible a fast way of searching for a data item: the binary search.

### Examples in this chapter:

{% assign articles = site.articles | where:"category","array" %}
<ol>
    {% for post in articles %}
      <li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
    {% endfor %}
</ol>

### Tasks:
{% assign articles = site.articles | where:"category","array_task" %}
<ol>
    {% for post in articles %}
        {% assign title = post.title | split:"| " %}
      <li><a href="{{ post.url | prepend: site.baseurl }}">{{ title.last }}</a></li>
    {% endfor %}
</ol>
