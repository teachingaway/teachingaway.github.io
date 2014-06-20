---
layout: page
permalink: /articles/
title: Articles
description: "An archive of posts sorted by date."
image:
  feature: default-image.jpg
  credit: 
  creditlink: 
---

<ul class="post-list">
{% for post in site.posts limit:25 %} 
  <li>
    <article>
        <a href="{{ site.url }}{{ post.url }}">
            <span class="post-list-title">
                {{ post.title }} 
            </span>
            <span class="entry-date">
                <time datetime="{{ post.date | date_to_xmlschema }}">
                    {{ post.date | date: "%B %d, %Y" }}
                </time>
            </span>
        </a>
        <span class="post-list-summary">
            {{ post.summary }} 
        </span>
    </article>
</li>
{% endfor %}
</ul>


