---
layout: page
title: Queue
category: stack-queue
file_path: 03_stack_queue/queue.dart
permalink: articles/stack-queue/4-queue
prevpage: 
    url: /articles/stack-queue/3-brackets
    title: Brackets
nextpage: 
    url: /articles/stack-queue/5-priority_queue
    title: Priority Queue
---

## {{ page.title }}

In computer science a queue is a data structure that is somewhat like a stack, except that in a queue the **first item inserted** is **the first to be removed** (First-In-First-Out, FIFO), while in a stack, as we’ve seen, the **last item inserted** is the **first to be removed** (LIFO).

```terminal
$ dart {{ page.file_path }}
```      

{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}      
