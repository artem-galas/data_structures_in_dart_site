---
layout: page
title: Double Linked List
category: linked-list
file_path: 04_linked_list/double_linked_list.dart
permalink: articles/linked-list/7-double_linked_list
prevpage: 
    url: 6-list_insertion_sort
    title: List Insertion Sort
nextpage:
    url: 8-list_iterator
    title: List Iterator
---

## {{ page.title }}

Let’s examine another variation on the linked list: the doubly linked list (**not to be** confused with the double-ended list).
What’s the advantage of a doubly linked list? A potential problem with ordinary linked lists is that it’s difficult to traverse backward
along the list.

Double Linked List allows you to traverse **backward** as well as **forward** through the list.
The secret is that each link has two references to other links instead of one. The first is to the **next link**, as in ordinary lists. The second is to the **previous link**.

```terminal
$ dart {{ page.file_path }}
```      


{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}      
