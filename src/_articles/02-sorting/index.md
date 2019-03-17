---
layout: page
title:  "Simple Sorting"
category: index
permalink: articles/simple-sorting/
nextpage:
    url: 1-bubble_sort
    title: Bubble Sort
---

## {{ page.title }}

### Examples in this chapter:

{% assign articles = site.articles | where:"category","simple_sorting" %}
<ol>
    {% for post in articles %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ol>

### Tasks:
{% assign articles = site.articles | where:"category","simple_sorting_task" %}
<ol>
    {% for post in articles %}
        {% assign title = post.title | split:"| " %}
      <li><a href="{{ post.url }}">{{ title.last }}</a></li>
    {% endfor %}
</ol>
