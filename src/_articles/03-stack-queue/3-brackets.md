---
layout: page
title: Brackets
category: stack-queue
file_path: 03_stack_queue/stack/brackets.dart
permalink: articles/stack-queue/3-brackets
prevpage: 
    url: 2-reverse
    title: Reverse
nextpage: 
    url: 4-queue
    title: Queue
---

## {{ page.title }}

One common use for stacks is to parse certain kinds of text strings.
Typically,the strings are lines of code in a computer language, and the programs parsing them are compilers.

Example:

```terminal
c[d] // correct
a{b[c]d}e // correct
a{b(c]d}e // not correct; ] doesn’t match (
a[b{c}d]e} // not correct; nothing matches final }
a{b(c) // not correct; nothing matches opening {
```

```terminal
$ dart {{ page.file_path }}
```      


{% highlight dart %}
{% include_absolute examples/data_structures_in_dart/{{ page.file_path }} %}
{% endhighlight %}      
