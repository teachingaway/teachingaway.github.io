---
layout: post
title: "Blog Like a Hacker: Lawyer Edition."
summary: "Jekyll and Github reflect our values as a firm - simplicity, efficiency, and open source collaboration."
tags: [software]
author: adler
image:
  feature: /wide/octojekyll-blue.png
  credit: Github
  creditlink: https://octodex.github.com/
comments: true
share: true
---


<p class="big-text">Jekyll and Github reflect our values as a law firm - simplicity, efficiency, and open source collaboration. Jekyll is the right size tool for a simple law blog.</p> 

Jekyll is a lightweight static website generator. It's speed and elegance convinced me to switch our law firm website over from Wordpress. Wordpress is slow. When a user hits a Wordpress site, Wordpress queries a database for instructions on how to build the website, builds it, serves it, and then forgets everything. When the next visitor shows up, Wordpress starts over from scratch.[^1] Wordpress is the big-law of content management systems: happy to waste time by repeating mundane tasks.

[^1]: caching a Wordpress website is possible in theory, and should speed up page loads, but after several attempts I've never made it work. 

Wordpress is painfully slow on Media Temple, Dreamhost, Bluehost, and even on Wordpress.com. The only fast Wordpress host I've used is [Digital Ocean](https://www.digitalocean.com/). 

<!-- [disclosure: Digital Ocean was one of our first clients].   -->

<img src="/images/bob-loblaw.jpg" class="translucent">

For a simple law blog, try jekyll. Unlike Wordpress, Jekyll builds the website once, and then re-serves the same static website over and over. Without a database, Jekyll is not only faster than Wordpress, it's more secure. 

**Jekyll + Github.** Github can serve a Jekyll website from a repository.  This takes care of version control, and also leverages Github’s wonderful CDN. Github Pages can be set up in [5 quick steps](https://pages.github.com/). If you already use Github, its more like 2 steps. 

**CSS Styles with LESS.** [LESS](http://lesscss.org/) is a "CSS preprocessor." Writing plain CSS is [repetitive](http://en.wikipedia.org/wiki/Don't_repeat_yourself), while LESS is concise. LESS is not only easier to write than CSS, it's easier to edit. The LESS learning curve is gentle, and the payoff is huge. It feels like escaping from the front-end stone age.  

<img src="/images/octocat-agendacat-law.png" class="translucent">

## Technology that Reflects our Values as a Law Firm

We use Jekyll & Github for our website because they reflect our values as a law firm. We aim to provide simple, elegant solutions to complex legal problems. We don’t waste time grinding through 50 page contracts when 5 pages will do. We prioritize efficiency, not billable hours. We collaborate, and love open source software. One of our earliest law firm side-projects was writing and sharing open source legal documents. We were early advisors to [Docracy](Docracy.com), and Eric’s face decorates their landing page. Dedication to open source is why Zeke contributes to the [Series Seed](http://www.seriesseed.com/posts/2014/02/version-32.html) documents. 


### Links

Tom Preston-Werner wrote the original [Blog like a Hacker](http://tom.preston-werner.com/2008/11/17/blogging-like-a-hacker.html) post, just after he wrote the Jekyll code (2008). The most useful guide to Jekyll is probably [Creating a fast and mobile-friendly website with Jekyll](http://nicolashery.com/fast-mobile-friendly-website-with-jekyll/) from Nicolas Hery (2013). [Jekyll From Scratch](http://pixelcog.com/blog/2013/jekyll-from-scratch-introduction/) is also quite good. Smashing Magazine's [Build A Blog With Jekyll And GitHub Pages](http://www.smashingmagazine.com/2014/08/01/build-blog-jekyll-github-pages/) is another good starting point (8/2014). 

