---
layout: page
title: Anagram
category: recursion
file_path: 05_recursion/anagram.dart
permalink: articles/recursion/2-anagram
prevpage: 
  url: /articles/recursion/1-triangle
  title: Triangle
nextpage: 
  url: /articles/recursion/3-binary_search
  title: Binary Search
---

## {{ page.title }}

Here’s a different kind of situation in which recursion provides a neat solution to a problem.
A permutation is an arrangement of things in a definite order.
Suppose you want to list all the anagrams of a specified word—that is, all possible permutations (whether they make a real English word or not) that can be made from the letters of the original word.
We’ll call this anagramming a word. 
Anagramming cat, for example, would produce:
```bash
cat
cta
atc
act
tca
tac
```

```terminal
$ dart {{ page.file_path }}
```

{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}      
  