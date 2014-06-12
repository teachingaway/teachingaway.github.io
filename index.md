---
layout: page
title: 
description: "Lawyers for Technology and Design Innovators."
tags: [lawyers, patents, trademarks, MPEP]
modified: 2014-06-04
image:
    feature: NYC-Cityscape.jpg


---




<h3>Lawyers for Technology and Design Innovators.</h3>

We provide legal advice and representation to clients who want to make a mark on the world. Our clients are entrepreneurs who work under conditions of uncertainty, and in competition with incumbents that are structurally opposed to change. We understand the challenge from direct experience.

Our professionals possess a combination of intellectual property and commercial expertise that is rare to find in a small firm. We look for engagements that leverage our full capabilities in service of our clients’ interests. Each client and engagement is unique.

- - - 

<h3>Blog</h3>

<ul class="post-list">
{% for post in site.posts limit:5 %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>

- - - 

<h3>Representative Clients<h3>

<figure class="third">
	<a href='http://www.simple.com'><img src="/images/clients/simple-logo.png"></a>
	<a href='http://redantler.com'><img src="/images/clients/red-antler-logo.png"></a>
	<a href='http://objectivesubject.com'><img src="/images/clients/objective-subject-logo.png"></a>
	<a href='http://outlier.cc'><img src="/images/clients/outlier-logo.png"></a>
	<a href='http://digitaldumbo.com'><img src="/images/clients/digital-dumbo-logo.png"></a>
	<a href='http://www.finalfrontierdesign.com/'><img src="/images/clients/final-frontier-logo.png"></a>
</figure>
