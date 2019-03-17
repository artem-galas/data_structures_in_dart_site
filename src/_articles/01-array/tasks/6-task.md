---
layout: page
title:  "Array | Task 6"
category: array_task
permalink: /articles/array/tasks/6-task
file_path: 01_array/tasks/task_6.dart
prevpage: 
    url: 5-task
    title: Tasks 5
---

## {{ page.title }}

Write a `noDups()` method for the `HighArray` class of the [HighArray](articles/array/2-high_array) program.

This method should remove all duplicates from the array.
That is, if three items with the key 17 appear in the array, `noDups()` should remove two of them.

Don’t worry about maintaining the order of the items.

One approach is to first compare every item with all the other items and
overwrite any duplicates with a null (or a distinctive value that isn’t used for real keys).

Then remove all the nulls. Of course, the array size will be reduced.

```terminal
$ dart {{ page.file_path }}
```

{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}
