---
layout: page
title: Partion
category: sorting
file_path: 06_sorting/partion.dart
permalink: articles/sorting/2-partion
prevpage:
  url: 1-shell_sorting
  title: Shell Sorting
nextpage:
  url: 3-quick_sort1
  title: Quick Sort1
---

## {{ page.title }}

Partitioning is the underlying mechanism of quicksort, which we’ll explore
next, but it’s also a useful operation on its own.

To partition data is to divide it into two groups, so that all the items with
a key value higher than a specified amount are in one group, and all the items
with a lower key value are in another.

```terminal
$ dart {{ page.file_path }}
```      


{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}      
