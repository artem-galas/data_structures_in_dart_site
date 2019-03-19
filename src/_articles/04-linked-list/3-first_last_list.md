---
layout: page
title: First Last List
category: linked-list
file_path: 04_linked_list/first_last_list.dart
permalink: articles/linked-list/3-first_last_list
prevpage: 
    url: /articles/linked-list/2-linked_list
    title: Linked List
nextpage: 
    url: /articles/linked-list/4-link_stack_list
    title: Link Stack List
---

## {{ page.title }}

A double-ended list is similar to an ordinary linked list, but it has one additional feature: **a reference to the last link** as well as **to the first**.

```terminal
$ dart {{ page.file_path }}
```      


{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}      
