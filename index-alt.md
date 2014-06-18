---
layout: page
title: 
permalink: /index-alt/
description: "Lawyers for Technology and Design Innovators."
tags: [lawyers, patents, trademarks, MPEP]
modified: 2014-06-04
image:
    feature: default-image.jpg


---


<h1 class="entry-title">Lawyers for Technology and Design Innovators.</h1>

<p class='big-text'>We practice intellectual property and business law at a level rarely found in a small firm. We help raise capital, structure deals, and secure patents and trademarks.</p>

We're more than just lawyers. We're technology nerds immersed in crypto-currencies, 3D printing, crowdfunding, and software development. We serve this website from GitHub. 

Our clients are innovators in fields like cryptography, financial technology, mobile health, fashion, and spacesuit design:

<figure class="third">
	<a href='http://www.simple.com'><img src="/images/clients/simple-logo.png"></a>
	<a href='http://redantler.com'><img src="/images/clients/red-antler-logo.png"></a>
	<a href='http://objectivesubject.com'><img src="/images/clients/objective-subject-logo.png"></a>
	<a href='http://outlier.cc'><img src="/images/clients/outlier-logo.png"></a>
	<a href='http://digitaldumbo.com'><img src="/images/clients/digital-dumbo-logo.png"></a>
	<a href='http://www.finalfrontierdesign.com/'><img src="/images/clients/final-frontier-logo.png"></a>
</figure>

- - - 

Blog

<ul class="post-list">
{% for post in site.posts limit:5 %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>

- - - 
Located in Brooklyn, NY

<iframe class="google-maps" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3024.6791757542383!2d-73.99045970000006!3d40.70306290000001!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c25a313e4fd337%3A0xc024c97fc54f6963!2s45+Main+St!5e0!3m2!1sen!2sus!4v1402924084152"  frameborder="0" style="border:0"></iframe>
