---
layout: page
title: Heap
category: index
permalink: articles/heap/
---
    
## {{ page.title }}

A heap is a kind of tree. It offers both insertion and deletion
in `O(logN)` time.
Thus, it’s not quite as fast for deletion, but much faster for insertion.
It’s the method of choice for implementing priority queues where speed is
important and there will be many insertions.

### Examples in this chapter:

{% assign articles = site.articles | where:"category","heap" %}
<ol>
    {% for post in articles %}
      <li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
    {% endfor %}
</ol>