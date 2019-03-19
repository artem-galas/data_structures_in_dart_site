---
layout: page
title:  "Array | Tasks"
category: index_array_tasks
permalink: /articles/array/tasks
nextpage: 
    url: /articles/array/tasks/1-task
    title: Task 1
prevpage:
    url: /articles/array/4-class_data
    title: Class Data
---

## {{ page.title }}

### Tasks

{% assign articles = site.articles | where:"category","array_task" %}
<ol>
    {% for post in articles %}
    {% assign title = post.title | split:"| " %}
      <li><a href="{{ post.url | prepend: site.baseurl }}">{{ title.last }}</a></li>
    {% endfor %}
</ol>
