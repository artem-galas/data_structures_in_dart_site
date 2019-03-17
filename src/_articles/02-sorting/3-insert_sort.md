---
layout: page
title: Insert_sort
category: simple_sorting
file_path: 02_simple_sorting/insert_sort.dart
permalink: articles/simple-sorting/3-insert_sort
prevpage: 
    url: 2-select_sort
    title: Select Sort
nextpage: 
    url: 4-object_sort
    title: Object Sort
---

## {{ page.title }}

In most cases the insertion sort is the best of the elementary sorts described in this chapter.
It still executes in `O(N^2)` time, but it’s about twice as fast as the bubble sort and somewhat faster than the selection sort in normal situations.
It’s also not too complex, although it’s slightly more involved than the bubble and selection sorts. It’s often used as the final stage of more sophisticated sorts, such as **quicksort**

```terminal
$ dart {{ page.file_path }}
```      

{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}      
