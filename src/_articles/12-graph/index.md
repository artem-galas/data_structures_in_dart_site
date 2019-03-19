---
layout: page
title: Graph
category: index
permalink: articles/graph/
---
    
## {{ page.title }}

Graphs are one of the most versatile structures used in computer programming. 
The sorts of problems that graphs can help to solve are generally quite
different from those
we’ve dealt with thus far in this book.
If you’re dealing with general kinds of data storage problems, you probably
won’t need a graph, but for some problems—and they tend
to be interesting ones—a graph is indispensable.

### Examples in this chapter:

{% assign articles = site.articles | where:"category","graph" %}
<ol>
    {% for post in articles %}
      <li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
    {% endfor %}
</ol>