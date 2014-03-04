---
layout: page
title: A Nonsense Landing Page
description: "n00b mangles a Beautiful Jekyll Theme."
tags: [Jekyll, theme, themes, responsive, blog, minimalism]
image:
    feature: DaubEnginePatent.jpg

---

## A Header of Some Sort. 
Lebowski ipsum what are you, some kind of sad-assed refugee from the fucking sixties? Dolor sit amet, consectetur. DO YOU SEE WHAT HAPPENS, LARRY? Adipiscing elit praesent ac magna. A MILLION BUCKS FROM FUCKING NEEDY LITTLE URBAN ACHIEVERS! YOU ARE SCUM, MAN! Justo pellentesque ac lectus quis elit blandit. Wal, I lost m'chain of thought here. But—aw hell, I done innerduced him enough. Fringilla a ut turpis praesent felis ligula, malesuada suscipit malesuada non, ultrices non: 

> There's no fucking reason—here's my point, Dude—there's no fucking reason. Urna sed orci ipsum, placerat id condimentum. Stay out of Malibu, deadbeat! Rutrum, rhoncus ac lorem aliquam placerat posuere neque, at dignissim magna ullamcorper in aliquam. Not a bunch of fig-eaters with towels on their heads tryin' to find reverse on a Soviet tank. Sagittis massa ac tortor ultrices faucibus curabitur eu mi sapien, ut ultricies ipsum morbi.

### Subhead of More Lebowski

I mean I had an M16, Jacko, not an Abrams fucking tank. Eget risus nulla nullam vel nisi enim, vel auctor ante morbi id. Thankie… Just one thing, Dude. D'ya have to use s'many cuss words? Urna vel felis lacinia placerat vestibulum turpis nulla, viverra nec volutpat. We've got a man down, Dude. Ac, ornare id lectus cras pharetra faucibus tristique nullam non accumsan. Donny was a good bowler, and a good man. He was… He was one of us. He was a man who loved the outdoors, and bowling, and as a surfer explored the beaches of southern California from Redondo to Calabassos. And he was an avid bowler. And a good friend. He died—he died as so many of his generation, before his time. In your wisdom you took him, Lord. As you took so many bright flowering young men, at Khe San and Lan Doc.

I see you rolled your way into the semis. Dios mio, man. Seamus and me, we're gonna fuck you up.  Little Lebowski Urban Achievers, yes, and proud we are of all of them. Fuckin' A. It's a complicated case, Maude. Lotta ins. Lotta outs. And a lotta strands to keep in my head, man.

<ul class="post-list">
{% for post in site.posts limit:10 %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>