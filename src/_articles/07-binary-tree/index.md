---
layout: page
title: Binary Tree
category: index
permalink: articles/binary-tree/
---
    
## {{ page.title }}
Binary trees are one of the fundamental data storage structures
used in programming.
They provide advantages that the data structures we’ve seen so far cannot.

### Examples in this chapter:

{% assign articles = site.articles | where:"category","binary-tree" %}
<ol>
    {% for post in articles %}
      <li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
    {% endfor %}
</ol>