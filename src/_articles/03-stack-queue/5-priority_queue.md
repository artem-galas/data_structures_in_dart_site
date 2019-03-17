---
layout: page
title: Priority Queue
category: stack-queue
file_path: 03_stack_queue/priority_queue.dart
permalink: articles/stack-queue/5-priority_queue
prevpage: 
    url: 4-queue
    title: Queue
nextpage: 
    url: 6-infix
    title: Infix
---

## {{ page.title }}

A priority queue is a more specialized data structure than a stack or a queue.

However, it’s a useful tool in a surprising number of situations. Like an ordinary queue, a priority queue has a front and a rear, and items are removed from the front.

However, in a priority queue, items are ordered by key value so that the item with the lowest key (or in some implementations the highest key) is always at the front. Items are inserted in the proper position to maintain the order.

```terminal
$ dart {{ page.file_path }}
```      


{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}      
