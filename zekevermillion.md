---
layout: person
permalink: /zekevermillion/
title: Zeke Vermillion
modified: 2013-09-13
author: vermillion
school-undergrad: B.A., Columbia University
school-law: J.D., New York University
admission1: New York
admission2: 
admission3: 
admission4:
admission5: 
image:
  feature: /wide/eric-zeke-phone-office.jpg
  credit: Michael Meysarosh
  creditlink: http://meysarosh.smugmug.com/

---


Zeke acts as a general corporate legal adviser to entrepreneurial companies and individuals. Recent engagements include capital-raising transactions, employee equity incentive grants, copyright and trademark licensing, business development partnerships, and small business acquisitions. Zeke was previously at White & Case, where he worked on a wide variety of M&A, securities, project and asset finance deals, and the largest IPO in history. He uses his broad experience and industry connections to solve clients' legal problems efficiently.

- - - 

### Zeke's Blog Posts

<ul class="post-list">
{% for post in site.posts %} 
{% if post.author == "vermillion" %}
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
