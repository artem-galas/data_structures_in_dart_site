---
layout: page
title:  "Ordered Array"
category: array
file_path: 01_array/ordered_array.dart
permalink: /articles/array/3-ordered_array
prevpage: 
    url: 2-high_array
    title: High Array
nextpage: 
    url: 4-class_data
    title: Class Data
---

## {{ page.title }}

Describes **BinarySearch** in sorted Arrays.

We’ll use the `OrderedArray` class to encapsulate the array and its algorithms. The heart of this class is the `find()` method, which uses a **BinarySearch** to locate a specified data item.
In general, the `OrderedArray` program is similar to [Hight Array](2-high_array)

```terminal
$ dart {{ page.file_path }}
```

{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}
