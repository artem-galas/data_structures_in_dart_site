---
layout: page
title: Tree 2 3 4
category: index
permalink: articles/tree-2-3-4/
---
    
## {{ page.title }}

2-3-4 trees are interesting for several reasons.
**First**, they’re balanced trees like `red-black` trees.
They’re slightly less efficient than red-black trees but easier to program. **Second**, and most important, they serve as an easy-to-understand introduction to `B-trees`.

### Examples in this chapter:

{% assign articles = site.articles | where:"category","tree-2-3-4" %}
<ol>
    {% for post in articles %}
      <li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
    {% endfor %}
</ol>