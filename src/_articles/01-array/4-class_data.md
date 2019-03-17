---
layout: page
title:  "Ordered Array"
category: array
file_path: 01_array/class_data.dart
permalink: /articles/array/4-class_data
prevpage: 
    url: 3-ordered_array
    title: Ordered Array   
nextpage: 
    url: tasks
    title: Tasks
---

## {{ page.title }}

The program that makes use of the `Person` class is similar to the [Hight Array](2-high_array)
that stored items of type `int`. 
Only a few changes are necessaryto adapt that program to handle Person objects.

```terminal
$ dart {{ page.file_path }}
```

{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}
