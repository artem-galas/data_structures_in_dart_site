---
layout: page
title:  "Array | Task 4"
category: array_task
permalink: /articles/array/tasks/4-task
file_path: 01_array/tasks/task_4.dart
prevpage: 
    url: 3-task
    title: Tasks 3
nextpage: 
    url: 5-task
    title: Task 5
---

## {{ page.title }}

Modify the [OrderedArray](/articles/array/3-ordered-array) so that the `insert()` and `delete()`
routines, as well as `find()`, use a binary search, as suggested in the text.


```terminal
$ dart {{ page.file_path }}
```

{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}
