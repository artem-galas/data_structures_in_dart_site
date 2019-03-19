---
layout: page
title:  "Array | Task 3"
category: array_task
permalink: /articles/array/tasks/3-task
file_path: 01_array/tasks/task_3.dart
prevpage: 
    url: /articles/array/tasks/2-task
    title: Tasks 2
nextpage: 
    url: /articles/array/tasks/4-task
    title: Task 4
---

## {{ page.title }}

The removeMax() method in `task_2.dart` suggests a way to sort the contents of an array by key value.

Implement a sorting scheme that does not require modifying the HighArray class, but only the code in main().

You’ll need a second array, which will end up inversely sorted.
(This scheme is a rather crude variant of the selection sort in Chap03, 'Simple Sorting.)

```terminal
$ dart {{ page.file_path }}
```

{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}
