---
layout: page
permalink: /longform/
title: In Depth Articles
description: "An archive of longform articles."
image:
  feature: /wide/default-image.png
  credit: Company Folders
  creditlink: 
---


<nav class="pagination" role="navigation">
 <a href="/tags/" class="btn big-btn">Sort by Topic</a> 
</nav>


<ul class="page-list">
{% for page in site.pages %} 
{% if page.longform == "yes" %}
  <li>
    <article>
        <a href="{{ site.url }}{{ page.url }}">
            <span class="page-list-title">
                {{ page.title }} 
            </span>   
         <br>   
         </a>
        <span class="page-list-summary">
            {{ page.summary }} 
        </span>
    </article>
</li>
{% endif %}
{% endfor %}
</ul>



