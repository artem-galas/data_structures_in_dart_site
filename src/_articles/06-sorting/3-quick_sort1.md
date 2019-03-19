---
layout: page
title: Quick Sort 1
category: sorting
file_path: 06_sorting/quick_sort1.dart
permalink: articles/sorting/3-quick_sort1
prevpage:
  url: /articles/sorting/2-partion
  title: Partion
nextpage:
  url: /articles/sorting/4-quick_sort2
  title: Quick Sort2
---

## {{ page.title }}

Quicksort is undoubtedly the most popular sorting algorithm, and for good reason:
In the majority of situations, it’s the fastest, operating in `O(N*logN)` time.

```terminal
$ dart {{ page.file_path }}
```      


{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}      
