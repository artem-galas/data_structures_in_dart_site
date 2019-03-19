---
layout: page
title:  "Array | Task 1"
category: array_task
permalink: /articles/array/tasks/1-task
file_path: 01_array/tasks/task_1.dart
prevpage: 
    url: /articles/array/tasks
    title: Tasks   
nextpage: 
    url: /articles/array/tasks/2-task
    title: Task 2
---

## {{ page.title }}

To the HighArray class in the [High Array](/articles/array/2-high_array) program
add a method called `getMax()` that returns the value of the highest key in the array, or –1 if the array is empty.
You can assume all the keys are positive numbers.

```terminal
$ dart {{ page.file_path }}
```

{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}
