---
layout: page
title:  "High Array"
category: array
file_path: 01_array/high_array.dart
permalink: /articles/array/2-high_array
prevpage: 
    url: /articles/array/1-low_array
    title: Low Array
nextpage:
    url: /articles/array/3-ordered_array
    title: Ordered Array    
---

## {{ page.title }}

Rewritten [Low Array](1-low_array) using more OOP way. Describes **LinerSearch** in Arrays.

The [Low Array](1-low_array) program is essentially consists of one big method.
We can reap many benefits by dividing the program into classes.
The data storage structure itself is one candidate, and the part of the program that uses this data structure is another.
By dividing the program into these two classes, we can
clarify the functionality of the program, making it easier to design and understand
(and in real programs to modify and maintain).

In [Low Array](1-low_array) we used an array as a data storage structure, but we treated it simply as a language element.
Now we’ll encapsulate the array in a class, called LowArray.
Our first design of the LowArray class won’t be entirely successful, but it will demonstrate the need for a better approach.

```terminal
$ dart {{ page.file_path }}
```

{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}
