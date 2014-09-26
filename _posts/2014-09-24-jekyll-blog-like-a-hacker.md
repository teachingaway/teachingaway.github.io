---
layout: post
title: "Blog Like a Hacker, Lawyer Edition."
summary: "Jekyll and Github reflect our values as a firm - simplicity, efficiency, and collaboration."
tags: [software]
author: adler
image:
  feature: /wide/octojekyll-blue.png/
  credit: Github
  creditlink:
comments: true
share: true
---


<p class="big-text">Jekyll is a lightweight static website generator. We use Jekyll & Github because they reflect our values as a law firm: simplicity, efficiency, and collaboration. Its the right size tool for the job.</p> 

When I learned HTML 15 years ago, I built static websites. This involved repetitive copy/pasting and link updating. I eventually discovered Wordpress and thought it solved my problems. While Wordpress has lots of fancy features, these features make it slow. When a user hits a Wordpress site, Wordpress queries a database for instructions on how to build the website, builds it, and then forgets what it just learned. When the next visitor shows up, Wordpress starts over from scratch. Wordpress is the big-law of content management systems, happily wasting time by repeating mundane tasks.[^1]  

[^1]: Except that unlike big-law, Wordpress is free.  


Wordpress is painfully slow on Media Temple, Dreamhost, Bluehost, and even on Wordpress.com. The only place Wordpress seems to work is on [Digital Ocean](https://www.digitalocean.com/) [full disclosure: Digital Ocean was one of our first clients].  While Wordpress has lots of fancy bling, I don't need bling for my blog. I need a fast website.

With Jekyll, we return to static websites. Unlike Wordpress, Jekyll builds the website once, and then re-serves the same static website over and over. Without a database, Jekyll is not only faster than Wordpress, its more secure. A poorly configured database is an unlocked door. ([_see, Database v. Bobby’); DROP TABLE cases;_ (2012)](http://xkcd.com/327/)). 

## Jekyll Living in Github

Github serves Jekyll websites right from a Github repository.  This takes care of version control, and also leverages Github’s wonderful CDN. Github pages can be set up in [5 quick steps](https://pages.github.com/). If you already use Github, its more like 2 steps. If you’re new to GitHub, building a Github page is a great introduction.  

## CSS Styles with LESS

Learning [LESS](http://lesscss.org/) feels like escaping from the front-end stone age. LESS is a CSS "preprocessor" (whatever that means). All I know that writing CSS is [repetitive](http://en.wikipedia.org/wiki/Don't_repeat_yourself), and LESS is concise. LESS is easier to write than CSS, and far easier to edit. The LESS learning curve is gentle, and the payoff is huge. 


## Technology that Reflects our Values as a Law Firm

We use Jekyll & Github for our website because they reflect our values as a law firm. We aim to provide simple, elegant solutions to complex legal problems. We don’t waste time grinding through 50 page contracts when 5 pages will do. We prioritize efficiency, not maximizing billable hours. We collaborate, and love open source software. One of our earliest law firm side-projects was writing and sharing open source legal documents. We were early advisors to [Docracy](Docracy.com), and Eric’s face still decorates their landing page. Zeke contributes to the open source [Series Seed](http://www.seriesseed.com/posts/2014/02/version-32.html) documents.  

Technology makes lawyering more fun for us, and delivers better value to our clients. 


## Links

* [Original Blog like a Hacker](http://tom.preston-werner.com/2008/11/17/blogging-like-a-hacker.html). Tom Preston-Werner. 

* [Creating a fast and mobile-friendly website with Jekyll](http://nicolashery.com/fast-mobile-friendly-website-with-jekyll/). Nicolas Hery, 2013. 

* [octodex](https://octodex.github.com/)

* [Jekyll From Scratch](http://pixelcog.com/blog/2013/jekyll-from-scratch-introduction/)

* [Jekyll 201: Beyond Hello World](http://www.mdswanson.com/blog/2013/06/03/jekyll-201.html)

* [Build A Blog With Jekyll And GitHub Pages](http://www.smashingmagazine.com/2014/08/01/build-blog-jekyll-github-pages/) - Smashing Magazine, 2014. 

- - - 


