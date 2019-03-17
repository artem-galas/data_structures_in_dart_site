---
layout: page
title: Simple Linked List
category: linked-list
file_path: 04_linked_list/linked_list/simple_linked_list.dart
permalink: articles/linked-list/1-simple_linked_list
prevpage:
    url: /articles/linked-list
    title: Linked List Index
nextpage:
    url: 2-linked-list
    title: Linked List
---

## {{ page.title }}

Here we're demonstrates a simple linked list. 

The only operations allowed in this version of a list are:
- Inserting an item at the beginning of the list
- Deleting the item at the beginning of the list
- Iterating through the list to display its contents

These operations are fairly easy to carry out, so we’ll start with them.

```terminal
$ dart {{ page.file_path }}
```      

{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}      
