---
layout: page
title: Object Sort
category: simple_sorting
file_path: 02_simple_sorting/object_sort.dart
permalink: articles/simple-sorting/4-object_sort
prevpage: 
    url: /articles/simple-sorting/3-insert_sort
    title: Insert Sort
---

## {{ page.title }}

For simplicity we’ve applied the sorting algorithms we’ve looked at thus far to a primitive data type: `int`.
However, sorting routines will more likely be applied to objects than primitive types. Accordingly, we show a Dart program that sorts an array of `Person` objects.

```terminal
$ dart {{ page.file_path }}
```      

{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}      
