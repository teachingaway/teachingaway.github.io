---
layout: page
title: NYC Technology Lawyers
description: "Innovative lawyers delivering practical advice in Dumbo Brooklyn, and NYC."
tags: [lawyers, patents, trademarks, MPEP]
modified: 2014-06-04
image:
    feature: NYC-Cityscape.jpg

---

*Business Law*  We structure deals, raise capital and litigate disputes. 

*Intellectual Property* We secure patents and trademarks in the US and abroad. 

*Clients*  We work for emerging technology ventures and public companies.

- - - 

## The [MPEP](_pages/index.html) in Jekyll. 

For example, [Obviousness](_pages/s2141.html), [written description](_pages/s2163.html), and [patentable subject matter](_pages/s2106.html). 


## Blog
<ul class="post-list">
{% for post in site.posts limit:10 %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>

