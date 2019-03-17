---
layout: page
title:  "Array | Task 2"
category: array_task
permalink: /articles/array/tasks/2-task
file_path: 01_array/tasks/task_2.dart
prevpage: 
    url: 1-task
    title: Tasks 1   
nextpage: 
    url: 3-task
    title: Task 3
---

## {{ page.title }}

Modify the method from [Task 1](arciles/array/tasks/1-task) so that the item with the highest key is not only returned by the method,
but also removed from the array.
Call the method `removeMax()`.

```terminal
$ dart {{ page.file_path }}
```

{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}
