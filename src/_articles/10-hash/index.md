---
layout: page
title: Hash
category: index
permalink: articles/hash/
---
    
## {{ page.title }}

A hash table is a data structure that offers very fast insertion and searching.
When you first hear about them, hash tables sound almost too good to be true. No matter how many data items there are, insertion and searching (and
sometimes deletion) can take close to constant time: `O(1)`. 
In practice this is just a few machine instructions.

### Examples in this chapter:

{% assign articles = site.articles | where:"category","hash" %}
<ol>
    {% for post in articles %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ol>