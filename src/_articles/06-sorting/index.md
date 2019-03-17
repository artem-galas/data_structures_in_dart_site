---
layout: page
title: Sorting
category: index
permalink: articles/sorting/
---
    
## {{ page.title }}

This chapter covers two advanced approaches to sorting: **Shellsort** and **Quicksort**.

These sorts both operate much faster than the simple sorts: the Shellsort in about `O(N*(logN)^2)` time, and quicksort in `O(N*logN)` time.

Neither of these sorts requires a large amount of extra
space, as mergesort does.
The **Shellsort** is almost as easy to
implement as `mergesort`, while `quicksort` is the fastest of all
the general-purpose sorts.

### Examples in this chapter:

{% assign articles = site.articles | where:"category","sorting" %}
<ol>
    {% for post in articles %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ol>