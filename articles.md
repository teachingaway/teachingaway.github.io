---
layout: page
permalink: /articles/
title: Articles
description: "An archive of posts sorted by date."
image:
  feature: /wide/default-image.png
  credit: Company Folders
  creditlink: 
---

<ul class="post-list">
{% for post in site.posts limit:25 %} 
{% if post.includeinbloglist != "no" %}
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
{% endif %}
{% endfor %}
</ul>


