---
layout: page
title:  "Array | Task 5"
category: array_task
permalink: /articles/array/tasks/5-task
file_path: 01_array/tasks/task_5.dart
prevpage: 
    url: 4-task
    title: Tasks 4
nextpage: 
    url: 6-task
    title: Task 6
---

## {{ page.title }}

Add a `merge()` method to the `OrderedArray` class in the [OrderedArray](/articles/array/3-ordered-array)
program so that you can merge two ordered source arrays into an ordered destination array.

Write code in `main()` that inserts some random
numbers into the two source arrays, invokes `merge()`, and displays the contents of the resulting destination array.

The source arrays may hold different numbers of data items.

In your algorithm you will need to compare the keys of
the source arrays, picking the smallest one to copy to the destination.

You’ll also need to handle the situation when one source array exhausts its contents before the other.


```terminal
$ dart {{ page.file_path }}
```

{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}
