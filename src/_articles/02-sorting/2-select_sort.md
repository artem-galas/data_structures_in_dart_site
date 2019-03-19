---
layout: page
title: Select Sort
category: simple_sorting
file_path: 02_simple_sorting/select_sort.dart
permalink: articles/simple-sorting/2-select_sort
prevpage: 
    url: /articles/simple-sorting/1-bubble_sort
    title: Bubble Sort
nextpage: 
    url: /articles/simple-sorting/3-insert_sort
    title: Insert Sort
---

## {{ page.title }}

The `selection sort` improves on the `bubble sort` by reducing the number of swaps necessary from `O(N^2)` to `O(N)`. Unfortunately, the number of comparisons remains `O(N^2)`.
However, the selection sort can still offer a significant improvement for large records that must be physically moved around in memory, causing the swap time to be much more important than the comparison time. 

```terminal
$ dart {{ page.file_path }}
```      


{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}      
