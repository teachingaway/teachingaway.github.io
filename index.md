---
layout: page
title: NYC Technology Lawyers
description: "Innovative lawyers delivering practical advice in Dumbo Brooklyn, and NYC."
tags: [lawyers, patents, trademarks, MPEP]
modified: 2014-06-04
image:
    feature: NYC-Cityscape.jpg


---

*Experienced NYC lawyers using digital technology to provide efficient legal services.*

**Business Law:** We structure deals, raise capital and run mergers and acquisitions. We counsel clients on equity incentive plans that attract skilled employees in competitive fields. 

**Intellectual Property:** We secure patents and trademarks in the US and abroad. Our patent work includes cryptography, 3D printers, spacesuit components, and medical devices.

**Litigation:** We litigate complex contract and intellectual property disputes, including patent troll defense. We also help enforce legitimate IP rights in trade secret disputes, trademark appeals at the USPTO and litigation in federal court. 

- - - 

**Clients:** We work for emerging technology ventures and public companies. 

<figure class="half">
	<img src="/images/client1.png">
	<img src="/images/client2.png">
	<img src="/images/client3.png">
	<img src="/images/client4.png">
	<img src="/images/client5.png">
	<img src="/images/client3.png">
</figure>

- - -  


## Blog
<ul class="post-list">
{% for post in site.posts limit:5 %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>



