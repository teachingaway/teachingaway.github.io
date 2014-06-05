---
layout: page
title: NYC Technology Lawyers
description: "Innovative lawyers delivering practical advice in Dumbo Brooklyn, and NYC."
tags: [lawyers, patents, trademarks, MPEP]
modified: 2014-06-04
image:
    feature: NYC-Cityscape.jpg

---

## We <a href="#securities">raise capital</a>, <a href="#ip">secure patents</a>, <a href="#corporate">structure deals</a> and <a href="#litigation">litigate disputes.


## We represent public companies, emerging enterprises, and creative professionals.

<div class="section" id="services">	
    <div id="corporate" class="sub_section">
        <h2>Corporate Counsel</h2>
        <p>Our corporate practice counsels companies and funds. Corporate counsel is fundamentally about managing principal-agent problems where multiple stakeholders have overlapping interests. Governance, incentive structures, moral hazard, and regulatory risk are all part of the equation. We help clients chart a course through this thicket, avoiding risks and seizing opportunities along the way.</p>
        <p>We run small and medium enterprise mergers and acquisitions processes efficiently to close deals quickly without  sacrificing risk control.</p>
    </div> <!-- #corporate -->

    <div id="securities" class="sub_section">
        <h2>Raising Capital & Equity Compensation</h2>
        <p>We are at the forefront of innovative debt and equity financing, including convertible debt with deferred pricing, crowd-sourced and P2P lending networks, standardized convertible preferred stock terms, and contractual profit-sharing rights.</p>
        <p>We craft equity incentive plans that attract skilled employees in competitive fields.</p>
    </div> <!-- #securities -->

    <div id="ip" class="sub_section">
        <h2>Intellectual Property</h2>
        <p>We litigate IP disputes, secure patents, and counsel clients on trademark, copyright, and technology licensing issues.</p>
        <h3>Patents: <em>Defending Research & Development</em></h3>
        <p>Our patent practice combines rigorous data analytics with deep patent law experience. We use modern, data-driven models to help clients develop robust, cost-effect patent portfolios. Patent data from <a href="https://judicialstats.com/index.php/patent-examiners">Judicial Stats</a> helps us craft patent applications that are more likely to sail through the Patent Office and return valuable patent rights.</p> 
        <p>A carefully structured portfolio helps create lucrative licensing opportunities, venture capital strategies, and powerful tools for disposing with baseless lawsuits.</p>
        <h3>Trademarks: <em>Brand Protection</em></h3>
        <p>From identity development, to trademark registration and enforcement, our attorneys work side-by-side with clients to maximize brand value. We understand the fluid nature of branding for the internet, and we help direct  direct clients toward unique and easily defensible identities.</p>
        <h3>Copyright: <em>Defending Creative Works</em></h3>
        <p>Copyright law helps creative professionals and software developers protect their art and code. Eric and Joe write <a href="http://www.copyrightcodex.com/">Copyright Codex</a>, a free treatise on copyright law that has been recognized by law schools like Standford and Duke.</p> 
        </p>
    </div> <!-- #ip -->

    <div id="litigation" class="sub_section">
        <h2>Litigation</h2>
        <p>We litigate complex contract and intellectual property disputes. We defend technology companies from patent trolls. We also help enforce legitimate IP rights, even against larger, better-funded competitors. We contain litigation costs through efficient discovery technology. </p>
        <p>We have successfully handled disputes including trade secret claims, winning trademark appeals at the USPTO, and contract and copyright disputes in federal court.</p>
    </div> <!-- #litigation -->
</div> <!-- #services -->

## The [MPEP](_pages/index.html) in Jekyll. 

For example, [Obviousness](_pages/s2141.html), [written description](_pages/s2163.html), and [patentable subject matter](_pages/s2106.html). 



<ul class="post-list">
{% for post in site.posts limit:10 %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>

