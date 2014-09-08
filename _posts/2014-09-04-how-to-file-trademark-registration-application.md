---
layout: post
bloglist: "yes"
title: "How to Register a US Trademark"
summary: "An illustrated walkthrough of the USPTO trademark application process."
tags: [trademark]
author: adler
image:
  feature: /wide/transmission-patent-gray-blueprint.jpg
  credit:
  creditlink:
comments: true
share: true
---

**This is a Work in Progress**

A trademark protects a brand - a company’s unique relationship with its customers. A startup’s brand is one of its most valuable assets. This post discusses basic trademark law, how to search the trademark database, and how to file a trademark application at the US Patent and Trademark Office (I'll just call it the "Trademark Office”). 

There is nothing inherently complicated about the trademark application process. The Trademark Office just collects some basic information about the trademark, about the trademark owner, and about how the owner uses the trademark to sell things. The Trademark Office has a website to collect this application info, but sadly, the website complicates a potentially-simple process with a tangle of baffling instructions. Their web design philosophy is "more but worse." 

This walkthrough tries to explain the trademark application process, but it doesn't cover every detail. Its not a substitute for hiring an experienced trademark attorney.

## The Benefits of Trademark Registration

Trademark law automatically grants a basic set of rights called “common law” trademark rights. Federal trademark registration enhances these rights in a big way. A registration is strong evidence[^1] of your exclusive trademark rights, it increases the penalties for infringing your trademark, and provides official government recognition of your brand identity. In addition to providing evidence, registration creates substantive trademark rights and psychological benefits. 

[^1]: Registration is “prima facie” evidence; it creates a legal presumption. Although these presumptions can be overcome, they stack the litigation deck in your favor.



Evidence | Description
| - | - | 
Exclusive Rights | You have the exclusive right to use the trademark to sell the specified goods & services.
Validity | Not every word or symbol can be a valid trademark. For example, generic words are not valid trademarks. A trademark registration is evidence that your trademark is valid.  
Start Date  |  Trademark rights go to the first company to use the trademark (with some exceptions).  If two companies use the same trademark, the company that started using it first has the superior trademark rights. A registration is strong evidence that your “date of first use” of the trademark was sometime before the application date.
Continuous Use |  Trademark rights end when you stop using the trademark to sell your goods or services. A trademark registration is evidence that you have not abandoned the trademark.
**TM Rights** | **Description**
Nation-Wide Rights  |  Registration provides immediate nation-wide rights, while unregistered trademark rights are limited to the particular towns and cities where the trademark is actually being used to sell products or services.
Seize Counterfeit Imports  | With a trademark registration, you can have the US Customs and Border Protection service seize counterfeit imports at the border.
Incontestability  | After 5 years on the Principal Register, and after filing the appropriate forms, your registration will be “incontestable.” An incontestable registration cannot be cancelled (with a few exceptions).
Compensation for Infringement  |  Registration increases the amount of compensation you’re entitled to collect from infringers. It allows for treble (3x) damages, and even forcing the infringer to pay your attorney’s fees. Registration provides for mandatory treble damages and criminal penalties for counterfeiters. 15 USC §1117(b).
® Symbol  | You can display the ® symbol after a registered trademark. Unregistered trademarks can only use the ™ symbol.
Psychological Benefits  | In addition to enhancing formal legal rights, registration provides an intangible psychological advantage, especially in front of a jury.




## Trademark Law Basics: Confusion and Distinctiveness

Before looking at the application, I’ll talk about the two most common reasons the Trademark Office will reject an application:  _Likelihood of Confusion_ and _lack of distinctiveness_. Both of these concepts involve the relationship between a “mark” and the product or service being advertised under the mark. For example, think of “apple” as a mark used for the product “computers,” or FedEx as a mark used for “delivery” services.  
 
**Likelihood of Confusion.** The Trademark Office will compare your trademark to a database of existing trademark registrations. If your trademark is too similar to an existing registration, it will be rejected for "likelihood of confusion" under §2(d). This comparison weighs two major factors: the mark and the product. Your trademark should only be refused if your brand, as used on your product, is too similar to an existing mark used on a similar product. 

In the language of the Lanham Act §2(d), the Trademark Office will refuse to register a trademark that,  

> (d) Consists of or comprises a mark which so resembles a mark registered in the Patent Office... as to be likely, when applied to the goods of the applicant to cause confusion….

How similar is *too similar*? A new trademark is too similar to an old one if an average consumer is likely to confuse the new product for the old one. This "likelihood of confusion" test involves several complicated legal considerations, and goes beyond the scope of this quick guide.[^1]

[^1]: The leading case on this complicated “likelihood of confusion” issue is [_In re EI DuPont DeNemours & Co._, 476 F. 2d 1357 (CCAP 1973)](http://scholar.google.com/scholar_case?&case=10357410588643700224).


**Distinctiveness.** A trademark should be "distinctive" as opposed to merely "descriptive" or worse - "generic."  Generic words are words that define a particular product. Trademark Law does not protect these words. Instead, they are kept available in the public domain. For example, every coffee shop must be allowed to use the word "coffee" in its marketing. The Trademark Office will not grant anyone single coffee shop the exclusive rights to use such a generic term. If you apply for a trademark that defines - or even closely describes - a product, the Trademark Office will reject your application.  

This is not only the law, its good branding. A distinctive trademark makes a lasting impression, while customers quickly forget a generic trademark.


| Name | TM Type  | Strength | 
| - | - |
| Computer | Generic | No TM Rights | 
| Digital Data Systems | Descriptive | Weak Rights | 
| Silicon Power | Suggestive | Strong Rights | 
| Apple | Arbitrary | Strongest Rights | 



- - - 

## Clearance Search

Before investing in your brand, search for any existing trademark registrations that might be too similar to your proposed brand. Lawyers sometimes call this a “trademark clearance search.” When lawyers say “knockout search” they’re talking about quick searches for identical (or nearly identical) trademark registrations. 

Three good places for starting your trademark clearance search are the US Trademark Office (called “TESS”), the EU Trademark Office database (called “OHIM”), and the World Intellectual Property Office trademark database (called “ROMARIN”). I’m not sure why they all have terrible acronyms. 

- [US Trademark Office Search - TESS](http://tess2.uspto.gov/bin/gate.exe?f=login&p_lang=english&p_d=trmk)
- [EU Trademark Office Search - OHIM](http://oami.europa.eu/eSearch/#advanced/trademarks)
- [World IP Office Trademark Search - ROMARIN](http://www.wipo.int/romarin/)

The EU and WIPO databases are somewhat intuitive. The US database is not intuitive at all, so I’ll try to offer some tips. Go to the [US Trademark Office Search page](http://tess2.uspto.gov/bin/gate.exe?f=login&p_lang=english&p_d=trmk). You should see this: 

<a href="/images/tm-app/search-tess-trademarks.png"><img src="/images/tm-app/search-tess-trademarks.png"></a>

click on the “free form search.” Here are some useful search strings for the US Trademark Database: 

    “some mark*”[BI] AND 
    “some products”[GS] AND 
    live[LD] 

If you’re a coder, you might recognize some of this as a weird cousin of “regular expressions” or “GREP.” The database is particular about the *search string format* you use. Type in the word you want to search for, and follow it (no spaces) with the initials for the part of the database you want to search. These initials need to be in brackets. Operators (“AND”, “OR”) need to be capitalized. 

| Search String | Result | 
| - | - |  
| “markxyz*”[BI]  |  This searches for the term “markxyz” in the “Basic Index.” The Basic Index is the index of both word marks and design marks. Use an asterisk as a ‘wildcard.’    |  
|  “productxyz”[GS]  |   This searches for marks with “productxyz” listed in the goods and services field of the database.  |  
| live[LD]  |  This limits your search results to live trademark registrations and applications.  |  


- - - 

## The Trademark Application Process

If you have picked out a unique, distinctive mark, then you’re ready to apply for a trademark registration. First, go to the <a title="USPTO Trademark Application" href="http://www.uspto.gov/teas/teasplus.htm">USPTO's Trademark Application</a> page. You should see the wall of text pictured below.

<a href="/images/tm-app/1-pick-teas-plus.png"><img src="/images/tm-app/1-pick-teas-plus.png" class="big-image"></a>

Pick "TEAS Plus." TEAS is some trademark Office acronym.  "TEAS Plus" is the version that saves you $50, but limits your options for describing your goods and services.

Click continue to be whisked away to a second page of convoluted warnings and instructions. 

- - - 

## Lawyer or DIY Application? 

All you need to do on this page is pick whether an attorney is filling out the form or not. 

<a href="/images/tm-app/2-is-attorney-filing-trademark.png"><img src="/images/tm-app/2-is-attorney-filing-trademark.png" class="big-image"></a>

**Time Limit.** This form will self destruct in 60 minutes. You can save your work for later by clicking "download portable data" on the "validation" page at the very end of the process. In a UX catch 22, you can’t actually get to the "download portable data" page until after you finish filling out each previous page of the form. If you do manage to download your saved data, you can upload it again at this page.  

Click continue, and you will see an ugly data entry form. 

- - - 

## Trademark Owner 

Here, you enter some info about the trademark owner. Be careful if the owner is a company that has parents, subsidiaries, or licensees. Entering the wrong owner can cause problems.

<a href="/images/tm-app/3-trademark-owner.png"><img src="/images/tm-app/3-trademark-owner.png" class="big-image"></a>

Note that this page asked for info about the trademark _owner_. Later in the process, you will see a very similar form asking for info about the _contact person_. 


- - - 

## The Trademark Itself

Trademark registrations can protect one of two types of marks, a "word mark" or a "design mark." The plaintext *word mark* protects the word (or short phrase or slogan) in any font and in any color. The *design mark* protects a stylized version of a word, and can also protect a logo or design without any words. [^2]

[^2]: While word-marks and design-marks are the most common types of trademarks, there are really several other types of marks that can be registered, including sounds, product packaging, colors, and animations. 

If you want to register a plaintext word mark, then pick "Standard Character." Plain text trademark registrations provide stronger trademark rights, but are more likely to be rejected by office actions. Plain text registration are generally stronger because they protect your trademark in every font, every color, and in any design.  Since they are broader rights, they are more likely to be rejected by the trademark office as being too similar to existing trademark registrations. 

If you want to register a stylized word or logo as your trademark, then pick "Special Form." You might want to apply for two separate trademark registrations - one for the plain-text words and another for the logo. 

Note: If the trademark includes any letters at all, type them into the box. Trademark law doesn't care much about capitalization or punctuation.

<a href="/images/tm-app/4-standard-character-trademark.png"><img src="/images/tm-app/4-standard-character-trademark.png" class="big-image"></a>

Pro tip: claim your logo as _colorless_ even if it includes particular colors. Colorless actually means every color. If you claim a color, your registration is limited to that particular color. A "special form" trademark should be easier to register, but the resulting trademark rights are less extensive than the plain-text option. If you pick "special form", you will be asked to upload a .jpg of your trademark.

- - - 

## Adding Goods and Services

Now we come to yet another page of complicated warnings. Click "Add Goods/Services." This will take us to a separate page  for selecting appropriate goods and services. 

<a href="/images/tm-app/5-add-goods.png"><img src="/images/tm-app/5-add-goods.png" class="big-image"></a>

- - - 

## Searching for Goods and Services

Now we're at a search box. This box lets us query the list list of pre-approved descriptions of goods and services. Describing your goods and services is tricky.  If the description is too broad, it can void your trademark. If its too narrow you may have trouble stopping infringers. If you can’t find an accurate description of your goods in the list of pre-approved descriptions, you should end this "TEAS Plus" application and start over with a “TEAS” application. The TEAS application will allow you to describe your goods and services in your own words. 

<a href="/images/tm-app/6-search-goods-services.png"><img src="/images/tm-app/6-search-goods-services.png" class="big-image"></a>

Before searching, try to identify the "class" of goods and services applicable to your trademark. We are talking about the “International Class” here. The [“International Class"](http://www.uspto.gov/trademarks/notices/international.jsp) system tries to categorize all possible goods and services into 45 classes. There is a separate US Classification system, but its essentially irrelevant, even for a US trademark application.

Rather than describe each of the classes, I’ll just touch on the classes that are most relevant to tech startups. 


| Class | for GOODS | 
| - | - | 
3  | Cosmetics 
7  | Machinery  
9 |  Software, Electrical and Scientific 
10 |  Medical Apparatus 
11 |  Environmental Control Apparatus
12 |  Vehicles
16 |  Paper Goods and Printed Matter
25 |  Clothing
28 |  Toys and Sporting Goods


| Class | for SERVICES | 
| - | - | 
35 |   Advertising and Business
36 |  Insurance and Financial
38 |   Communication
39 |   Transportation and Storage
41 |   Education and Entertainment
42 |   Computer, Scientific and Legal
43 |   Hotels and Restaurants
44 |   Medical, Beauty and Agricultural
45 |   Personal


In addition to selecting one or more “classes”, you will need to identify your products or services within that class. Here are some examples of product descriptions:  

> **iPad Mini** - Class 09 (Software and Electrical) - “Handheld mobile digital electronic device comprising a tablet computer, electronic book and periodical reader, digital audio and video player, camera, electronic personal organizer, calendar, and mapping and GPS device, and capable of providing access to the Internet.” 

> **Etsy** - Class 35 (Advertising and Business) - “Computerized online ordering featuring general merchandise and general consumer goods.”

> **Tumblr** - Class 41 (Education and Entertainment) - Electronic publishing services, namely, publishing of online works of others featuring electronic media, multimedia contents, videos, movies, pictures, images, text, photos, user-generated content, and related information via the Internet; electronic publishing of blogs of others.

> **BOSE** - Class 09 (Software and Electrical) - Loudspeaker systems; electrical power processors-namely, power amplifiers, inverters, and battery chargers.

**A note on software.** Picking the right class and description for software is difficult. Consider claiming software in several different classes:

Class | Short Title | Example 
| - | - | 
9 | Software (goods) | Any software that users download into a computer or mobile device. 
35 | Advertising and Business (services) | online advertisements, digital markets, database services, 
38 | Communication (services) | Internet service providers, cloud computing, chat & messaging services, streaming media.
42 | Software  (services) | “software as a service” and software development services. 
45 | Software (services) | Social networking, online dating


**Extra Fees:** The USPTO charges an extra application fee of about $300 per class. After your registration, they will charge you renewal fees per class. These renewal fees come at year 5, and then every 10 years after registration. 


- - - 

## Selecting Goods and Services from the List

When viewing the results, be sure the description is in the rights class. You can pick several descriptions, as long as they accurate describe your goods or services. The USPTO charges additional fees per "class" but not for multiple descriptions within a class.

<a href="/images/tm-app/7-pick-description-goods-services.png"><img src="/images/tm-app/7-pick-description-goods-services.png" class="big-image"></a>

- - - 

## Filing Basis

Every trademark needs a "filing basis." Think of the filing basis as the reason why you're entitled to a trademark registration. The two filing bases we will discuss here are called "use in commerce" [§1(a)] and "intent to use" [§1(b)]. The others relate to international trademarks. 
 
Pick §1(a) if you already use the trademark in interstate commerce. That is, you already use this trademark to sell some product or service in more than one US state. 

Pick §1(b) if you don't use the trademark to sell anything yet, but you plan to start soon.

<a href="/images/tm-app/8-assign-filing-basis.png"><img src="/images/tm-app/8-assign-filing-basis.png" class="big-image"></a>

If you selected §1(a) (use in commerce), you will be asked to provide a jpg image showing how you use the trademark in commerce. The Trademark Office wants some evidence that you are truly using the trademark to sell something. This will be the next step.

If you selected §1(b), you will end up with an "intent to use" registration. This registration is a placeholder. It will not provide full trademark rights until you file a "statement of use" with the Trademark Office. There is a time limit. You must file the statement of use within 6 months after your intent-to-use registration issues. You can extend this deadline for up to 3 additional 6-month periods by paying extension fees. This guide does not cover the §1(b) intent-to-use trademark application process. 

- - - 

## Specimen of Use

If you are already using your trademark (and picked §1(a) above), you need to upload a jpg that shows how you use the trademark. For _physical goods_, upload a picture of the trademark on the actual product.  You can use a screen-shot of your website, but only if it shows a "buy now" or "Purchase" button. For _services_, upload an advertisement showing the mark being used to promote the service. 

<a href="/images/tm-app/9-filing-basis-specimen.png"><img src="/images/tm-app/9-filing-basis-specimen.png" class="big-image"></a>

_Software as a service_ applications have recently become tricky. If your application claims software as a service, some examiners will reject a specimen that they believe shows only “downloadable” software. 

- - - 

## Upload the Specimen of Use

On this page, you will upload a jpg of your specimen of use. The image should be smaller than 900px square, but big enough to show the trademark being used to sell your product or service. Feel free to upload a few different images to help ensure the Trademark Office will approve at least one of them. 

<a href="/images/tm-app/10-attach-specimen-of-use-in-commerce.png"><img src="/images/tm-app/10-attach-specimen-of-use-in-commerce.png" class="big-image"></a>

After you upload the image, click "return to application.”  

- - - 

## Date of First Use

Next you will input the "date of first use" of the trademark. There are two dates - first use *in commerce*, and first use *anywhere*. Its critical that you get the date of first use in commerce correct. If its an old trademark, and you don't have the exact launch date, input the month and year. 

For goods in the same class, you can assign filing bases in a batch. If the goods are in different classes, each class needs to be assigned a filing basis separately. 

Click "assign filing basis" at the bottom, and you will be returned to the "Basis for Filing" screen once again. 

<a href="/images/tm-app/11-date-of-first-use.png"><img src="/images/tm-app/11-date-of-first-use.png" class="big-image"></a>

- - - 

## Back to the Basis for Filing Screen

After every line is assigned its filing basis, click continue. 

<a href="/images/tm-app/12-basis-assigned.png"><img src="/images/tm-app/12-basis-assigned.png" class="big-image"></a>

You have now described your goods and services, and assigned a filing basis for each class. The final steps are easier. You need to enter your contact info, sign the application (swearing that its contents are accurate), and pay the USPTO fee ($275 per class). 

- - - 

## Enter Contact Info

You entered "owner info" earlier, this time you are entering the contact info for the person who should receive Trademark Office notifications related to this application.

<a href="/images/tm-app/13-correspondence-info.png"><img src="/images/tm-app/13-correspondence-info.png" class="big-image"></a>

- - - 

## Sign the Application 

Pick "sign directly." Sign your name by typing it between two slashes like this: /Osbert Sitwell/. By signing the declaration, you are swearing that everything you just wrote is true. 

<a href="/images/tm-app/14-sign-declaration.png"><img src="/images/tm-app/14-sign-declaration.png" class="big-image"></a>

Click "Validate". Don't click "add signatory" unless you want to add a <em>second</em> signer. 

- - - 

## Click to Agree

Enter your email again, and then click to agree to the terms. The Trademark Office fee is non-refundable, and any info you send will become public information (except credit card). 

<a href="/images/tm-app/15-enter-email.png"><img src="/images/tm-app/15-enter-email.png" class="big-image"></a>

- - - 

## Pay the Filing Fee

Submit payment and you're done. 

<a href="/images/tm-app/16-pay-uspto-fee.png"><img src="/images/tm-app/16-pay-uspto-fee.png" ></a>


## What to Expect After You Submit

The USPTO sends an immediate confirmation email. Then, about 3 months later, a Trademark Examining Attorney will review your application and send you an "office action." If the office action is an approval, your trademark will probably register in 2 more months, and the Trademark Office will mail you an official document with a shiny gold seal. 

If the office action is a refusal, you will receive an email explaining the reasons for the rejection. You will have 6 months to respond to the refusal by either amending the application or pointing out any errors in the Trademark Office's reasons for rejecting the application.   

- - - 

## Conclusion 

Filing a DIY trademark application risky. Reading a blog is not a substitute for a legal education or hiring an experienced trademark attorney. 


- - - 









