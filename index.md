---
layout: page
title: NYC Technology Lawyers
description: "Innovative lawyers delivering practical advice in Dumbo Brooklyn, and NYC."
tags: [lawyers, patents, trademarks, MPEP]
modified: 2014-06-04
image:
    feature: NYC-Cityscape.jpg


---

An established law firm using digital technology to provide efficient legal services. 


## Business Law

We structure deals and raise capital. We run mergers and acquisitions efficiently to close deals quickly without sacrificing risk control.  Our lawyers work at the forefront of innovative debt and equity financing, including convertible debt with deferred pricing, crowd-sourced and P2P lending networks, standardized convertible preferred stock terms, and contractual profit-sharing rights. We counsel clients on equity incentive plans that attract skilled employees in competitive fields. 


## Intellectual Property

We secure patents and trademarks in the US and abroad. Our patent work includes cryptography, 3D printers, spacesuit components, and medical devices.

## Litigation

We litigate complex contract and intellectual property disputes. We defend technology companies from patent trolls. We also help enforce legitimate IP rights, even against larger, better-funded competitors. We have successfully handled trade secret disputes, won trademark appeals at the USPTO, and contract and copyright disputes in federal court. 

- - - 

## Clients:

We work for emerging technology ventures and public companies. 

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



