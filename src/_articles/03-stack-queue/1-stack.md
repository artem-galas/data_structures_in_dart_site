---
layout: page
title: Stack
category: stack-queue
file_path: 03_stack_queue/stack/stack.dart
permalink: articles/stack-queue/1-stack
prevpage: 
    url: /articles/stack-queue
    title: Stack Queue
nextpage: 
    url: 2-reverse
    title: Reverse
---

## {{ page.title }}

A stack allows access to only one data item: **the last item inserted**. If you remove this item, you can access the **next-to-last item inserted**, and so on.
This capability is useful in many programming situations.

```terminal
$ dart {{ page.file_path }}
```      

{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}      
