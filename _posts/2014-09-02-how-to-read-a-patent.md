---
layout: post
bloglist: "yes"
title: "How to Read a Patent"
summary: "A quick-and-dirty guide with with annotations and explanations."
tags: [patent]
author: adler
image:
  feature: /wide/second-circuit-courthouse--cc-flickr.com-KenLund.jpg
  credit: Ken Lund
  creditlink: https://www.flickr.com/photos/kenlund/7237324632
comments: true
share: true
---
 

Patents are complex documents that bury a handful of important sentences under a mountain of fluff and jargon.  If you're going to read a patent (and I urge you not to) you might as well start with the important parts, and read them correctly. 

Lets suppose you want to figure out whether your new technology might infringe some patent. Here's a simple strategy I’d use to do an initial, cursory analysis. 

[Note: links are to a local copy of the USPTO's ["Manual of Patent Examining Procedure"](/MPEP/) we serve from Jekyll.]

## First, skip down to the "claims." 

The [claims](/MPEP/s608.html#d0e45039) are a numbered list of run-on sentences buried toward the end of the patent. Although they come last, the claims are actually the meat of the patent - they define the actual patent rights. The other sections are auxiliary - they are supposed to help explain the claims. 

Next, highlight all the "**independent claims**." These are the claims starting with the word "A". For example, “1. A swizzle stick adapted to..." or “9. A computer implemented method for..." There are probably 2 or 3 of these independent claims, but there can be more. 

The others claims are the "**dependent claims**." The dependent claims start with the word “The” and refer back to a previous claim. For example, “7. The swizzle stick of claim 1, further comprising…” Ignore the dependent claims for now. Google Patents  actually displays dependent claims in gray text, making it easy to skim past them (UX!!). 

In 2 minutes, we've narrowed a huge patent document down to a small handful of important sentences - the independent claims. Next we will break down the independent claims and compare them to our technology. 

## Any Infringement? 

We want to determine whether our technology would infringe on this patent we're reading. A technology will infringe if it incorporates *every element* of any one of the claims. Fortunately, we only need to check the independent claims at this point. 

Claims read like run-on sentences, but if you're lucky the run-ons will be broken down into sections and even subsections. Take a look at the first claim in our annotated patent (which happens to be the patent for Larry Page’s PageRank algo). The first claim is a method with 3 steps, and the first step has 4 qualifications. If you’re technology does not incorporate even one of these steps or qualifications, its (probably) not infringing.** 

** at least not “directly infringing”. It might still be infringing under a complicated rule called the “Doctrine of Equivalents.”  

1. A computer implemented method of scoring a plurality of linked documents, comprising:
- obtaining a plurality of documents, 
- - at least some of the documents being linked documents, 
- - at least some of the documents being linking documents, and 
- - at least some of the documents being both linked documents and linking documents, 
- - each of the linked documents being pointed to by a link in one or more of the linking documents;
- assigning a score to each of the linked documents based on scores of the one or more linking documents and
- processing the linked documents according to their scores.

For example, lets say your technology does all of this except that none of the documents are both "linked documents and linking documents." Then your technology is (probably) not infringing on this claim 1. 

Parts of the claim might be ambiguous on their own. So at this point, we start referring back to the drawings and the summary to figure out whether words or phrases in the claim have some special meaning. This type of [claim interpretation](/MPEP/s2111.html) analysis is complicated, and beyond the scope of this post. In theory, if you are a reasonably competent engineer/scientist in the field of this patent, the claims should be written in language you can understand. (This is rarely true, but in theory, its required). 


<a href="/images/reading-patents.png"><img src="/images/reading-patents.png" class="big-image"></a>


## The Rest of the Patent 

Its easy to forget that the claims, and only the claims, define patent rights. The rest of the patent document is auxiliary to the claims. So let me hammer it home:  

- The **title** does not define the patent rights. If the title is "toaster", the patent probably covers some minor aspect of a toaster. It does not cover every aspect of every toaster, and certainly not the very concept of a toaster. Its usually best to ignore the title. 
- The **drawings** do not define the patent rights. The claims probably highlight some small aspect of the drawings, and this small aspect is part of the patent rights. The rest of the drawings may help explain the claims, but that is all they do. 
- The **summary** is just a summary of some technology. The claims probably highlight some small part of the summary, and this small part is part of the patent rights. The rest is fluff.  

## Prior Art

A [prior art analysis](MPEP/s706.html#d0e58220/) is similar to an infringement analysis. I’ll explain a quick taste of the prior art analysis because its useful to compare it to the infringement analysis.  
First, check the prior art reference’s date. Is it older* than the patent? If so, it might be prior art. Next, skip down to the claims. As with the infringement analysis, the claims are the most important part. But unlike infringement, we will need to review all the claims, not just the independent claims. 

* There are lots of complicated rules for determining whether prior art is *older* than the patent. 

Check to see whether the prior art reference explains *every element* of a claim in the patent. If so, the reference “anticipates” the claim, and the claim is invalid. Repeat this process for each claim. If an independent claim is anticipated and invalid, the dependent claims that branch off of it might still be valid. 

Even if a patent claim is not *anticipated*, it might still be *obvious*. The obviousness analysis essentially asks whether someone might reasonably combine two or more references to teach every element of a patent claim. Its complicated, so we will save the details for another post. 

 


## Conclusion

I hope this helps provide a general overview of how to read a patent. Patent law is complicated, and full of traps for the unwary. If you have an important patent question, hire a patent lawyer. 

Please feel free to ask general questions in the comment section. I'll try to answer and use them to help improve this guide. But I can't answer specific questions about your patents and technology. 

