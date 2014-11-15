---
layout: person
permalink: /ericadler/
title: Eric Adler
tags: [patent, trademark]
modified: 2014-06-13
author: adler
school-undergrad: B.S.M.E., Tufts University
school-law: J.D., Brooklyn Law School
admission1: New York
admission2: US Patent & Trademark Office
admission3: 
admission4:
admission5: 
image:
  feature: /wide/eric-zeke-phone-office.jpg
  credit: Michael Meysarosh
  creditlink: http://meysarosh.smugmug.com/

---


Eric builds robust patent portfolios at the intersection of design and technology. He brings principals of user experience and information architecture from the digital world into his legal work. 

Eric is an advisor to <a href="http://www.blipclinic.org/">Brooklyn Law School’s technology clinic (BLIP)</a>, sits on the board of the <a href="http://legalhackers.org/">NYC Legal Hackers</a>, and builds <a href='http://www.copyrightcodex.com'>copyright codex</a>, the free copyright law treatise. He writes <a href="https://medium.com/@teachingaway">good news about patent trolls</a> over at Medium. 

- - - 

### Eric's Blog Posts

<ul class="post-list">
{% for post in site.posts limit:9 %} 
{% if post.author == "adler" %}
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


