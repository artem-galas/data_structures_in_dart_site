---
layout: page
title: Weighted Graph
category: index
permalink: articles/weighted-graph/
---
    
## {{ page.title }}

When we include weight as a feature of a graph’s edges, some interesting and complex questions arise.
What is the minimum spanning tree for a weighted graph? 
What is the shortest (or cheapest) distance from one vertex to another?
Such questions have important applications in the real world.

### Examples in this chapter:

{% assign articles = site.articles | where:"category","weighted-graph" %}
<ol>
    {% for post in articles %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ol>