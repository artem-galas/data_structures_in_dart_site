---
layout: page
title: Binary Search
category: recursion
file_path: 05_recursion/binary_search.dart
permalink: articles/recursion/3-binary_search
prevpage: 
    url: /articles/recursion/2-anagram
    title: Anagram
nextpage: 
    url: /articles/recursion/4-towers
    title: Towers
---

## {{ page.title }}

We wanted to find a given cell in an ordered array using the fewest number of comparisons. 

The solution was to divide the array in half, see which half the desired cell
lay in, divide that half in half again, and so on.

```terminal
$ dart {{ page.file_path }}
```      

{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}      
  