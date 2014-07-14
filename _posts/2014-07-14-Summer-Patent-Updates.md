---
layout: post
title: "Summer Patent Troll Recap: Good, Bad, and Ugly."
summary: "The Supreme Court did some good; Congress failed to act; and the Chief Judge of the Federal Circuit Resigns." 
tags: [patent trolls, software patents, supreme court]
author: adler
image:
  feature: /wide/transmission-patent-gray-blueprint.jpg
  credit:
  creditlink:
comments: true
share: true
---




There's lots of *good news* in the battle against patent trolls and frivolous patent litigation. The Supreme Court is weighing in on the fight in a big way, Elon Musk set an example by open sourcing all of Tesla's patents, and Google's Eric Shulman has an interesting new "License on Transfer" project. In the *bad news* category, Congress failed to pass anti-troll legislation. And in *news of the weird*, the Chief Judge of the Federal Circuit resigned after a minor scandal. 

## The Good: Supreme Court Weighs in Against Trolls with 5 Unanimous Decisions. 
The Supreme Court rarely hears patent cases. So its a big deal that the Court issued 5 unanimous patent decisions this summer. Although none of the decisions directly involved patent trolls, the Supreme Court ruled against patent holders in each case. All of the decisions should hurt patent trolls. Here's a short plain-language summary of each. 

### No Patent for "Doing it on a Computer" 
  
*Alice v. CLS Bank* says that taking an idea and "doing it on a computer" is not an invention and can't be patented. In this case, the Supreme Court found that taking the "abstract idea" of intermediated settlement and "doing it on a computer" was not an invention worthy of a patent. This decision should make it easier to invalidate a number of old software patents being used by trolls. [EFF's Take.](https://www.eff.org/deeplinks/2014/06/bad-day-bad-patents-supreme-court-unanimously-strikes-down-abstract-software)

### No Overly Vague Patents
*Nautilus v. Biosig* says that overly vague patents are invalid. In the legalese, patent claims are "invalid" for "indefiniteness" if they fail to describe the invention with "reasonable certainty." Again this should make it easier to invalidate a number of notoriously vague software patents. 

### Make Plaintiff's Pay for Frivolous Lawsuits

*Highmark v. Allcare* and *Octane v. Icon* are sister cases. Both are about punishing plaintiffs for filing frivolous patent lawsuits: 

*Highmark v. Allcare* says that judges can punish plaintiffs that file "exceptionally" weak patent lawsuits by forcing them to pay the defendant's legal bills. If the plaintiff appeals this punishment, the appeals court can only overturn the punishment if the trial judge was "abusing her discretion." This should make it easier for courts to punish patent trolls that file frivolous lawsuits. 

*Octane v. Icon* likewise says that a judge can punish plaintiffs for filing "exceptionally" weak patent cases. Judges are no longer required to apply the rigid "subjective bad faith" and "objectively baseless" framework before punishing plaintiffs. Instead, judges can look at all of the relevant facts to determine which cases are "exceptional" and warrant "fee shifting." 

### No "Inducing" Infringement without Actual Infringement. 

*Limelight v. Akamai* involves some complicated patent law. Imagine two people, Barry and Joe. Barry makes the top half of a widget and Joe makes the bottom half. The gist of the Limelight decision is that neither Joe nor Barry can be liable for patent infringement unless the end widget, when assembled, would infringe the patent. In the legalese, a defendant can't be liable for "inducing" a third party's infringement (§271(b)) if there was no direct infringement (§271(a)) in the first place. 


### Plaintiff Always Has Burden of Proving Infringement
*Medtronic v. Boston Scientific* is another case involving complicated patent law. Some background:  I could buy a license from a patent owner, and then turn around and sue the patent owner to invalidate the patent I just licensed. Buying a license first is like an insurance policy. If the court determines that the patent is invalid, I can stop paying the license. If the patent is found valid, I still have a license, so I haven't infringed anything. In this *Medtronic*, the Supreme Court decided that the patent owner still bears the "burden of persuasion" on the issue of whether the company that bought the license is actually infringing the patent.

Thats 5 cases, and 5 wins for defendants in frivolous patent lawsuits. 

## The Bad: Patent Reform Dies in Senate
Anti-patent troll legislation stalled in May. While Obama-supported patent reform passed the House, it [died in the senate judicial committee](http://www.nytimes.com/2014/05/22/business/legislation-to-protect-against-patent-trolls-is-shelved.html). According to the NY Times, 

> "heavy lobbying by pharmaceutical and biotechnology companies, universities and trial lawyers prevented the bill from advancing."

The proposed law would have required patent trolls (generally shell companies) to identify their true owners. This is useful because the true owners are frequently hedge funds that would prefer not to be associated with patent trolls. 

## The Ugly: Chief Judge of the Federal Circuit Resigns Over Minor Scandal
The Federal Circuit is the court that hears appeals from every patent lawsuit in the country. After the Supreme Court, the Federal Circuit is the highest patent court. 

Randall Ray Rader, the Chief Judge of the Federal Circuit, [resigned](http://blogs.wsj.com/law/2014/06/13/judge-rader-author-of-controversial-email-to-lawyer-to-resign-from-bench/?KEYWORDS=%22federal+circuit%22/) in June after an email surfaced that raised questions about his impartiality. Rader had emailed a lawyer who argued Federal Circuit patent cases, and called this lawyer's work “IMPRESSIVE in every way” and signed off, *“Your friend for life, R.R.R.”*  Its easy to suspect Judge Rader's impartiality. 

*Does Rader's resignation help the fight against patent trolls?* Probably. Judge Rader was intelligent, but his rulings tended to favor broad software patents. We're still waiting to see who will replace Rader. Hopefully Obama will appoint someone willing take a stand against overly broad software patents and frivolous litigation. 



<img class="big-image"  src="/images/tesla-car-patent.png">

# Bonus: More Good 

### [Tesla Open Sources its Patents](http://www.teslamotors.com/blog/all-our-patent-are-belong-you).

Tesla and Elon Musk are granting [free licenses](http://www.teslamotors.com/blog/all-our-patent-are-belong-you) to anyone who wants to use Tesla's patented technology.
On June 12, 2014, Tesla make the announcement under the headline "all our patents are belong to you."  This is pretty cool, and sets an interesting example for other innovators in the technology industry. 
- [Ars Technica](http://arstechnica.com/tech-policy/2014/06/tesla-will-use-patents-to-subvert-patent-systemtesla-frees-patents-wont-initiate-patent-lawsuits-against-anyone/)

### [License on Transfer](http://www.lotnet.com/) 

This is complicated, but its worth understanding. I had the pleasure of hearing Google's Eric Schulman talk about his License on Transfer ideas in detail while we were [working on the Defensive Patent License](http://www.defensivepatentlicense.com/content/dpl-team/#working-group). 
 Newegg, Canon, Dropbox, SAP, and Asana have joined Google to create the initial "license on transfer" group. 

*Result*: Joining the License-on-Transfer group will help de-weaponize patents before patent trolls can acquire them. 

*Background*: patent trolls tend to buy up patents from struggling technology companies, and then use these patents as the basis for frivolous litigation. 

*License on Transfer*:  Anyone with patents can join the group. Whenever anyone in the License on Transfer group sells a patent, it automatically licenses the patent to everyone else in the group. This means that if Dropbox sells its patents to a patent troll, everyone in the License on Transfer group is immune from lawsuits on those patents. Pretty sweet deal. 

*License on Transfer Link Roundup:*

- [Google on License on Transfer](http://www.google.com/patents/licensing/lot/)
- [IP Nav](http://www.ipnav.com/blog/google-wants-you-to-give-away-your-patents/) - A patent monetization firm is "utterly mystified as to why anyone in his right mind would agree to any of Google’s proposed licenses." 
- [The Verge](http://www.theverge.com/2014/7/10/5887355/google-dropbox-and-others-form-coalition-to-cut-patent-trolls-off) 
- [ReCode](http://recode.net/2014/07/09/google-canon-dropbox-and-others-pool-patents-to-ward-off-trolls/)
- [Ars Technica](http://arstechnica.com/tech-policy/2014/07/how-operating-companies-can-stop-patent-trolls-cut-off-the-ammo/)

## Planet Money Podcasts

The July 9, 2014 Planet Money podcast was about  [the Case Against Patents](http://www.npr.org/blogs/money/2014/07/09/329895088/episode-551-the-case-against-patents). 

> On today's show...  we talk to two guys who say we should get rid of patents altogether. If someone has an idea, anyone else is free to steal it. 

- - - 

Thats the major patent news from the summer so far. Let me know if I've made any errors. I tried to write about the Supreme Court cases for a non-lawyers, so I'm glossing over a lot of nuance to get to the gist of each case. 

- - - 