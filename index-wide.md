---
layout: widepage
permalink: /wide/
title: 
description: "Lawyers for Technology and Design Innovators"
tags: [lawyers, patents, trademarks, MPEP]
modified: 2014-06-04
image:
    feature: /wide/default-image.png
    credit: company folders


---


<h1 class="entry-title">Lawyers for Technology and Design Innovators</h1>
<div class="entry-content">
<p class='big-text'>Experienced IP and Business lawyers serving leading technology clients, from venture-backed startups to national brands.</p>

<p>Adler Vermillion is a law firm steeped in digital technology. We provide a combination of intellectual property and commercial law expertise rarely found in a small firm.  We raise capital, structure deals, secure patents and register trademarks.</p>
<p>Our relationships in the venture capital and technology communities help connect clients to valuable resources. For certain early stage companies, we offer deferred fee arrangements.
</p>
</div>


- - - 

We provide modern legal services to <a href="/clients">dynamic clients</a>.

<figure class="third">
	<a href='http://www.simple.com'><img src="/images/clients/simple-logo.png"></a>
	<a href='http://redantler.com'><img src="/images/clients/red-antler-logo.png"></a>
	<a href='http://solidoodle.com'><img src="/images/clients/solidoodle-logo.png"></a>
	
	<a href='http://www.mediaredefined.com/'><img src="/images/clients/redef-logo.png"></a>
	<a href='http://mitro.co'><img src="/images/clients/mitro-logo.png"></a>
	<a href='http://www.finalfrontierdesign.com/'><img src="/images/clients/final-frontier-logo.png"></a>
	
</figure>

- - - 

<div class="entry-content">
<div class="hang-left"><a href="/articles">Blog</a></div>

<ul class="post-list">
{% for post in site.posts limit:5 %} 
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
</div> <!-- end entry-content -->


- - - 
