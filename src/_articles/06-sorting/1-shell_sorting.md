---
layout: page
title: Shell Sort
category: sorting
file_path: 06_sorting/shell_sort.dart
permalink: articles/sorting/1-shell_sort
prevpage:
  url: /articles/sorting
  title: Sorting
nextpage:
  url: /articles/sorting/2-partion
  title: Partion
---

## {{ page.title }}

The Shellsort is good for medium-sized arrays, perhaps up to a few thousand items, depending on the particular implementation.
It’s not quite as fast as quicksort and other O(N*logN) sorts, so it’s not optimum for very large files.
However, it’s much faster than the O(N^2) sorts like the
`selection sort` and the `insertion sort`, and it’s very easy to
implement.

```terminal
$ dart {{ page.file_path }}
```      


{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}      
