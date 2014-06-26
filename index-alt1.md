---
layout: page
title: 
permalink: /alt1/
description: "Lawyers for Technology and Design Innovators"
tags: [lawyers, patents, trademarks, MPEP]
modified: 2014-06-04
image:
    feature: /wide/computer-hardware-free-stock-vector-set-motherboard.pngIndexed.png



---


<h1 class="entry-title">Lawyers for Technology and Design Innovators</h1>

<p class='big-text'>Experienced IP and Business lawyers serving leading technology clients, from venture-backed startups to national brands.</p>

Adler Vermillion is a law firm steeped in digital technology. We provide a combination of intellectual property and commercial expertise rarely found in a small law firm.  We raise capital, structure deals, secure patents and register trademarks.

Our relationships in the legal, technology and venture capital communities help connect clients to investors and engineers. For certain early stage companies, we offer deferred fee arrangements.    

- - - 

**We provide modern legal services to [dynamic clients](/clients).**

<figure class="third">
	<a href='http://www.simple.com'><img src="/images/clients/simple-logo.png"></a>
	<a href='http://redantler.com'><img src="/images/clients/red-antler-logo.png"></a>
	<a href='http://objectivesubject.com'><img src="/images/clients/objective-subject-logo.png"></a>
	
	<a href='http://outlier.cc'><img src="/images/clients/outlier-logo.png"></a>
	<a href='http://mitro.co'><img src="/images/clients/mitro-logo.png"></a>
	<a href='http://www.finalfrontierdesign.com/'><img src="/images/clients/final-frontier-logo.png"></a>
	
</figure>

- - - 

<ul class="post-list">
{% for post in site.posts limit:5 %} 
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

- - - 