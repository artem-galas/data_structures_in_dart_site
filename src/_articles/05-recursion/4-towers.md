---
layout: page
title: Towers
category: recursion
file_path: 05_recursion/towers.dart
permalink: articles/recursion/4-towers
prevpage: 
  url: 3-binary_search
  title: Binary Search
nextpage: 
  url: 5-merge
  title: Merge
---

## {{ page.title }}

The Towers of Hanoi is an ancient puzzle consisting of a number of disks  placed on three columns.

The disks all have different diameters and holes in the middle so they will fit over the columns.

All the disks start out on column `A`.
The object of the puzzle is to transfer all the disks from column `A` to column `C`.
Only one disk can be moved at a time, and no disk can be placed on a disk that’s smaller than itself

```terminal
$ dart {{ page.file_path }}
```      


{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}
  