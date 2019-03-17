---
layout: page
title: Triangle
category: recursion
file_path: 05_recursion/triangle.dart
permalink: articles/recursion/1-triangle
prevpage: 
  url: /articles/recursion
  title: Recursion
nextpage: 
  url: 2-anagram
  title: Anagram
---

## {{ page.title }}

The nth term in the series is obtained by adding n to the previous term.
Thus, the second term is found by adding 2 to the first term (which is 1), giving 3. The third term is 3 added to the second term (which is 3) giving 6, and so on.
The numbers in this series are called **triangular numbers** because they can be visualized as a triangular arrangement of objects.

```terminal
$ dart {{ page.file_path }}
```      


{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}      
