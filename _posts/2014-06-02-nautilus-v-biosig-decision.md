---
layout: post
title: "Supreme Court: Patents Must Define Invention with Reasonable Certainty"
summary: "<em>Nautilus v. Biosig</em> makes it easier to invalide patent claims for being too broad and non-specific."
category: articles
tags: [patent, supreme court]
author: adler
image:
  feature: /wide/supreme-court-equal-justice-cc-matt-wade.jpg
  credit: Matt Wade
  creditlink: http://en.wikipedia.org/wiki/User:UpstateNYer
comments: true
share: true
---

<p class="big-text">In <em>Nautilus v. Biosig</em>, the Supreme Court raised the minimum level of clarity and precision required in patent language.</p>

Patents grant rights to an invention, and these rights are defined in the patent's "Claims."  The "claims" are a numbered list of run-on sentences found toward the end of the patent document. They define what's in and what's out.

_In theory_, patent claims are supposed to notify competitors about what technology requires a license and what's public domain. If its described in a claim, its patented, and you need a license. If the technology is not described in any patent claims, its public domain. _In practice_, patent claims are difficult to read and understand, and their meaning is often ambiguous. They might look like this: 

    1. A multi-modal crowdfunding platform, comprising: 
       a plurality of contextual back-links 
       a prime number factorization engine, 
       an API for disruption-as-a-service, and
       a peer-to-peer network for salting rainbow tables. 

    2. The platform of claim 1, further comprising, 
       a robust experience for A/B testing curated moonshots. 
       

Here's the [actual patent claim](https://www.google.com/patents/US5337753) at issue in Nautilus v. Biosig: 

    1. A heart rate monitor for use by a user 
       in association with exercise apparatus
       and/or exercise procedures, comprising;

       an elongate member;

       electronic circuitry including a difference 
       amplifier having a first input terminal of a 
       first polarity and a second input terminal  
       of a second polarity opposite to said first polarity;
 
       said elongate member comprising a first half 
       and a second half;
  
       a first live electrode and a first common 
       electrode mounted on said first half in  
       **SPACED RELATIONSHIP** with each other;

       a second live electrode and a second common 
       electrode mounted on said second half in  
       spaced relationship with each other;
       [and so on for 350 more words]

Its not supposed to be this complicated. The Patent Statute requires claims "particularly pointing out and distinctly claiming" the subject matter of the invention. 35 U.S.C. § 112(b). A claim that fails to "particularly" and "distinctly" identify the invention should be "indefinite" and therefore invalid.  

<img src="/../images/BioSig-patent.jpg" />

## Old Standard: Claim Can be Ambiguous, But Not "Insolubly Ambiguous." 

We see so many ambiguous patent claims because the Federal Circuit has been extremely lenient towards patent holders. While congress required patents to use language that is "particular" and "distinct", the Federal Circuit allowed patent claim to be ambiguous, but not "insolubly ambiguous." This standard encouraged a proliferation of ambiguous patents, made it difficult for startups to enter the marketplace. 

As the Supreme Court put it: 

> absent a meaningful definiteness check... patent applicants face powerful incentives to inject ambiguity into their claims.

## New Standard: "Reasonable Certainty"

The Supreme Court raised the standard: patent claims must now describe the invention with such "reasonable certainty" that an engineer or scientist in the relevant field can understand what is in and what is out. 

> In place of the "insolubly ambiguous" standard, we hold that a patent is invalid for indefiniteness if its claims, read in light of the specification delineating the patent, and the prosecution history, fail to inform, with reasonable certainty, those skilled in the art about the scope of the invention.

The Supreme Court acknowledged that the Patent Statute demands a minimum level of "clarity and precision", and this minimum level is "reasonable certainty."  

## Affect on Patent Litigation Procedure

In patent litigation, the "indefiniteness" analysis is generally conducted at a "claim construction" hearing. This is a hearing in front of a judge, not a jury. But when a legal standard uses the word "reasonable", it generally means the standard must be applied by the jury (if there is a jury). Since the new standard for clarity in patent claims is "reasonable certainty", we may see the indefiniteness analysis move away from the "claim construction" hearing (before a judge) and into the trial (before a jury). 

- - - 

## Links

- [PatentlyO](http://patentlyo.com/patent/2014/06/reasonable-certainty-regarding.html)

- [Scotus Blog](http://www.scotusblog.com/case-files/cases/nautilus-inc-v-biosig-instruments-inc/)

- - - 

# Text of Supreme Court Decision

Nutilus, Inc., v. Biosign Instruments, Inc. 

No. 13-369.

Supreme Court of the United States.

Argued April 28, 2014.  Decided June 2, 2014.

GINSBURG, J., delivered the opinion for a unanimous Court.


The Patent Act requires that a patent specification "conclude with one or more claims _particularly pointing out and distinctly claiming_ the subject matter which the applicant regards as [the] invention." 35 U. S. C. §112, ¶2 (2006 ed.) (emphasis added). This case, involving a heartrate monitor used with exercise equipment, concerns the proper reading of the statute's clarity and precision demand. According to the Federal Circuit, a patent claim passes the §112, ¶2 threshold so long as the claim is "amenable to construction," and the claim, as construed, is not "insolubly ambiguous." 715 F. 3d 891, 898-899 (2013). We conclude that the Federal Circuit's formulation, which tolerates some ambiguous claims but not others, does not satisfy the statute's definiteness requirement. In place of the "insolubly ambiguous" standard, we hold that a patent is invalid for indefiniteness if its claims, read in light of the specification delineating the patent, and the prosecution history, fail to inform, with reasonable certainty, those skilled in the art about the scope of the invention. Expressing no opinion on the validity of the patent-in-suit, we remand, instructing the Federal Circuit to decide the case employing the standard we have prescribed.

## I [Constitutional and Historical Background]

Authorized by the Constitution "[t]o promote the Progress of Science and useful Arts, by securing for limited Times to... Inventors the exclusive Right to their... Discoveries," Art. I, §8, cl. 8, Congress has enacted patent laws rewarding inventors with a limited monopoly. "Th[at] monopoly is a property right," and "like any property right, its boundaries should be clear." _Festo Corp. v. Shoketsu Kinzoku Kogyo Kabushiki Co._, 535 U. S. 722, 730 (2002). See also _Markman v. Westview Instruments, Inc._, 517 U. S. 370, 373 (1996) ("It has long been understood that a patent must describe the exact scope of an invention and its manufacture... ."). Thus, when Congress enacted the first Patent Act in 1790, it directed that patent grantees file a written specification "containing a description... of the thing or things... invented or discovered," which "shall be so particular" as to "distinguish the invention or discovery from other things before known and used." Act of Apr. 10, 1790, §2, 1 Stat. 110.

The patent laws have retained this requirement of definiteness even as the focus of patent construction has shifted. Under early patent practice in the United States, we have recounted, it was the written specification that "represented the key to the patent." Markman, 517 U. S., at 379. Eventually, however, patent applicants began to set out the invention's scope in a separate section known as the "claim." See generally 1 R. Moy, Walker on Patents §4.2, pp. 4-17 to 4-20 (4th ed. 2012). The Patent Act of 1870 expressly conditioned the receipt of a patent on the inventor's inclusion of one or more such claims, described with particularity and distinctness. See Act of July 8, 1870, §26, 16 Stat. 201 (to obtain a patent, the inventor must "particularly point out and distinctly claim the part, improvement, or combination which [the inventor] claims as his invention or discovery").

The 1870 Act's definiteness requirement survives today, largely unaltered. Section 112 of the Patent Act of 1952, applicable to this case, requires the patent applicant to conclude the specification with "one or more claims particularly pointing out and distinctly claiming the subject matter which the applicant regards as his invention." 35 U. S. C. §112, ¶2 (2006 ed.). A lack of definiteness renders invalid "the patent or any claim in suit." §282, ¶2(3).[^1]

## II [Factual Background]

### A [The Patent at Issue]

The patent in dispute, U. S. Patent No. 5,337,753 ('753 patent), issued to Dr. Gregory Lekhtman in 1994 and assigned to respondent Biosig Instruments, Inc., concerns a heart-rate monitor for use during exercise. Previous heart-rate monitors, the patent asserts, were often inaccurate in measuring the electrical signals accompanying each heartbeat (electrocardiograph or ECG signals). The inaccuracy was caused by electrical signals of a different sort, known as electromyogram or EMG signals, generated by an exerciser's skeletal muscles when, for example, she moves her arm, or grips an exercise monitor with her hand. These EMG signals can "mask" ECG signals and thereby impede their detection. App. 52, 147.

Dr. Lekhtman's invention claims to improve on prior art by eliminating that impediment. The invention focuses on a key difference between EMG and ECG waveforms: while ECG signals detected from a user's left hand have a polarity opposite to that of the signals detected from her right hand,[^2] EMG signals from each hand have the same polarity. The patented device works by measuring equalized EMG signals detected at each hand and then using circuitry to subtract the identical EMG signals from each other, thus filtering out the EMG interference.

As relevant here, the '753 patent describes a heart-rate monitor contained in a hollow cylindrical bar that a user grips with both hands, such that each hand comes into contact with two electrodes, one "live" and one "common." The device is illustrated in figure 1 of the patent, id., at 41, reproduced in the Appendix to this opinion.

Claim 1 of the '753 patent, which contains the limitations critical to this dispute, refers to a "heart rate monitor for use by a user in association with exercise apparatus and/or exercise procedures." Id., at 61. The claim "comprise[s]," among other elements, an "elongate member" (cylindrical bar) with a display device; "electronic circuitry including a difference amplifier"; and, on each half of the cylindrical bar, a live electrode and a common electrode "mounted... in spaced relationship with each other." Ibid.[^3] The claim sets forth additional elements, including that the cylindrical bar is to be held in such a way that each of the user's hands "contact[s]" both electrodes on each side of the bar. Id., at 62. Further, the EMG signals detected by the two electrode pairs are to be "of substantially equal magnitude and phase" so that the difference amplifier will "produce a substantially zero [EMG] signal" upon subtracting the signals from one another. Ibid.

### B [The Dispute and the "Spaced Relationship" Claim Limitation.]

The dispute between the parties arose in the 1990's, when Biosig allegedly disclosed the patented technology to StairMaster Sports Medical Products, Inc. According to Biosig, StairMaster, without ever obtaining a license, sold exercise machines that included Biosig's patented technology, and petitioner Nautilus, Inc., continued to do so after acquiring the StairMaster brand. In 2004, based on these allegations, Biosig brought a patent infringement suit against Nautilus in the U. S. District Court for the Southern District of New York.

With Biosig's lawsuit launched, Nautilus asked the U. S. Patent and Trademark Office (PTO) to reexamine the '753 patent. The reexamination proceedings centered on whether the patent was anticipated or rendered obvious by prior art—principally, a patent issued in 1984 to an inventor named Fujisaki, which similarly disclosed a heart-rate monitor using two pairs of electrodes and a difference amplifier. Endeavoring to distinguish the '753 patent from prior art, Biosig submitted a declaration from Dr. Lekhtman. The declaration attested, among other things, that the '753 patent sufficiently informed a person skilled in the art how to configure the detecting electrodes so as "to produce equal EMG [signals] from the left and right hands." Id., at 160. Although the electrodes' design variables—including spacing, shape, size, and material— cannot be standardized across all exercise machines, Dr. Lekhtman explained, a skilled artisan could undertake a "trial and error" process of equalization. This would entail experimentation with different electrode configurations in order to optimize EMG signal cancellation. Id., at 155-156, 158.[^4] In 2010, the PTO issued a determination confirming the patentability of the '753 patent's claims.

Biosig thereafter reinstituted its infringement suit, which the parties had voluntarily dismissed without prejudice while PTO reexamination was underway. In 2011, the District Court conducted a hearing to determine the proper construction of the patent's claims, see Markman v. Westview Instruments, Inc., 517 U. S. 370 (1996) (claim construction is a matter of law reserved for court decision), including the claim term "in spaced relationship with each other." According to Biosig, that "spaced relationship" referred to the distance between the live electrode and the common electrode in each electrode pair. Nautilus, seizing on Biosig's submissions to the PTO during the reexamination, maintained that the "spaced relationship" must be a distance "greater than the width of each electrode." App. 245. The District Court ultimately construed the term to mean "there is a defined relationship between the live electrode and the common electrode on one side of the cylindrical bar and the same or a different defined relationship between the live electrode and the common electrode on the other side of the cylindrical bar," without any reference to the electrodes' width. App. to Pet. for Cert. 43a-44a.

Nautilus moved for summary judgment, arguing that the term "spaced relationship," as construed, was indefinite under §112, ¶2. The District Court granted the motion. Those words, the District Court concluded, "did not tell [the court] or anyone what precisely the space should be," or even supply "any parameters" for determining the appropriate spacing. Id., at 72a.

The Federal Circuit reversed and remanded. A claim is indefinite, the majority opinion stated, "only when it is 'not amenable to construction' or 'insolubly ambiguous.'" 715 F. 3d 891, 898 (2013) (quoting _Datamize, LLC v. Plumtree Software, Inc._, 417 F. 3d 1342, 1347 (CA Fed. 2005)). Under that standard, the majority determined, the '753 patent survived indefiniteness review. Considering first the "intrinsic evidence"—i.e., the claim language, the specification, and the prosecution history—the majority discerned "certain inherent parameters of the claimed apparatus, which to a skilled artisan may be sufficient to understand the metes and bounds of 'spaced relationship.'" 715 F. 3d, at 899. These sources of meaning, the majority explained, make plain that the distance separating the live and common electrodes on each half of the bar "cannot be greater than the width of a user's hands"; that is so "because claim 1 requires the live and common electrodes to independently detect electrical signals at two distinct points of a hand." Ibid. Furthermore, the majority noted, the intrinsic evidence teaches that this distance cannot be "infinitesimally small, effectively merging the live and common electrodes into a single electrode with one detection point." Ibid. The claim's functional provisions, the majority went on to observe, shed additional light on the meaning of "spaced relationship." Surveying the record before the PTO on reexamination, the majority concluded that a skilled artisan would know that she could attain the indicated functions of equalizing and removing EMG signals by adjusting design variables, including spacing.

In a concurring opinion, Judge Schall reached the majority's result employing "a more limited analysis." Id., at 905. Judge Schall accepted the majority's recitation of the definiteness standard, under which claims amenable to construction are nonetheless indefinite when "the construction remains insolubly ambiguous." Ibid. (internal quotation marks omitted). The District Court's construction of "spaced relationship," Judge Schall maintained, was sufficiently clear: the term means "there is a fixed spatial relationship between the live electrode and the common electrode" on each side of the cylindrical bar. Ibid. Judge Schall agreed with the majority that the intrinsic evidence discloses inherent limits of that spacing. But, unlike the majority, Judge Schall did not "presum[e] a functional linkage between the 'spaced relationship' limitation and the removal of EMG signals." Id., at 906. Other limitations of the claim, in his view, and not the "'spaced relationship' limitation itself," "included a functional requirement to remove EMG signals." Ibid.

We granted certiorari, 571 U. S. ___ (2014), and now vacate and remand.

## III [Analysis]

### A [Competing Concerns: Incentivizing Inventor vs. Clear Notice]

Although the parties here disagree on the dispositive question—does the '753 patent withstand definiteness scrutiny—they are in accord on several aspects of the §112, ¶2 inquiry. First, definiteness is to be evaluated from the perspective of someone skilled in the relevant art. See, e.g., _General Elec. Co. v. Wabash Appliance Corp._, 304 U. S. 364, 371 (1938). See also §112, ¶1 (patent's specification "shall contain a written description of the invention, and of the manner and process of making and using it, in such full, clear, concise, and exact terms as to enable _any person skilled in the art_ to which it pertains, or with which it is most nearly connected, to make and use the same" (emphasis added)). Second, in assessing definiteness, claims are to be read in light of the patent's specification and prosecution history. See, e.g., United States v. Adams, 383 U. S. 39, 48-49 (1966) (specification); Festo Corp. v. Shoketsu Kinzoku Kogyo Kabushiki Co., 535 U. S. 722, 741 (2002) (prosecution history). Third, "[d]efiniteness is measured from the viewpoint of a person skilled in [the] art _at the time the patent was filed_." Brief for Respondent 55 (emphasis added). See generally E. Manzo, Patent Claim Construction in the Federal Circuit §0.2, p. 9 (2014) ("Patent claims... should be construed from an objective perspective of a [skilled artisan], based on what the applicant actually claimed, disclosed, and stated during the application process.").

The parties differ, however, in their articulations of just how much imprecision §112, ¶2 tolerates. In Nautilus' view, a patent is invalid when a claim is "ambiguous, such that readers could reasonably interpret the claim's scope differently." Brief for Petitioner 37. Biosig and the Solicitor General would require only that the patent provide reasonable notice of the scope of the claimed invention. See Brief for Respondent 18; Brief for United States as Amicus Curiae 9-10.

Section 112, we have said, entails a "delicate balance." _Festo_, 535 U. S., at 731. On the one hand, the definiteness requirement must take into account the inherent limitations of language. See ibid. Some modicum of uncertainty, the Court has recognized, is the "price of ensuring the appropriate incentives for innovation." Id., at 732. One must bear in mind, moreover, that patents are "not addressed to lawyers, or even to the public generally," but rather to those skilled in the relevant art. _Carnegie Steel Co. v. Cambria Iron Co_., 185 U. S. 403, 437 (1902) (also stating that "any description which is sufficient to apprise [steel manufacturers] in the language of the art of the definite feature of the invention, and to serve as a warning to others of what the patent claims as a monopoly, is sufficiently definite to sustain the patent").[^5]

At the same time, a patent must be precise enough to afford clear notice of what is claimed, thereby "'appris[ing] the public of what is still open to them.'" Markman, 517 U. S., at 373 (quoting McClain v. Ortmayer, 141 U. S. 419, 424 (1891)).[^6] Otherwise there would be "[a] zone of uncertainty which enterprise and experimentation may enter only at the risk of infringement claims." _United Carbon Co. v. Binney & Smith Co_., 317 U. S. 228, 236 (1942). And absent a meaningful definiteness check, we are told, patent applicants face powerful incentives to inject ambiguity into their claims. See Brief for Petitioner 30-32 (citing patent treatises and drafting guides). See also Federal Trade Commission, [The Evolving IP Marketplace: Aligning Patent Notice and Remedies With Competition](http://www.ftc.gov/sites/default/files/documents/reports/evolving-ip-marketplace-aligning-patent-notice-and-remedies-competition-report-federal-trade/110307patentreport.pdf) 85 (2011) (quoting testimony that patent system fosters "an incentive to be as vague and ambiguous as you can with your claims" and "defer clarity at all costs").[^7] Eliminating that temptation is in order, and "the patent drafter is in the best position to resolve the ambiguity in... patent claims." _Halliburton Energy Servs., Inc. v. M-I LLC_, 514 F. 3d 1244, 1255 (CA Fed. 2008). See also _Hormone Research Foundation, Inc. v. Genentech, Inc_., 904 F. 2d 1558, 1563 (CA Fed. 1990) ("It is a well-established axiom in patent law that a patentee is free to be his or her own lexicographer... .").

To determine the proper office of the definiteness command, therefore, we must reconcile concerns that tug in opposite directions. Cognizant of the competing concerns, we read §112, ¶2 to require that a patent's claims, viewed in light of the specification and prosecution history, inform those skilled in the art about the scope of the invention with reasonable certainty. The definiteness requirement, so understood, mandates clarity, while recognizing that absolute precision is unattainable. The standard we adopt accords with opinions of this Court stating that "the certainty which the law requires in patents is not greater than is reasonable, having regard to their subject-matter." Minerals Separation, Ltd. v. Hyde, 242 U. S. 261, 270 (1916). See also United Carbon, 317 U. S., at 236 ("claims must be reasonably clear-cut"); Markman, 517 U. S., at 389 (claim construction calls for "the necessarily sophisticated analysis of the whole document," and may turn on evaluations of expert testimony).

### B [The "Insolubly Ambiguous" Standard Fosters an Innovation-Discouraging "Zone of Uncertainty."]

In resolving Nautilus' definiteness challenge, the Federal Circuit asked whether the '753 patent's claims were "amenable to construction" or "insolubly ambiguous." Those formulations can breed lower court confusion,[^8] for they lack the precision §112, ¶2 demands. It cannot be sufficient that a court can ascribe some meaning to a patent's claims; the definiteness inquiry trains on the understanding of a skilled artisan at the time of the patent application, not that of a court viewing matters post hoc. To tolerate imprecision just short of that rendering a claim "insolubly ambiguous" would diminish the definiteness requirement's public-notice function and foster the innovation-discouraging "zone of uncertainty," _United Carbon_, 317 U. S., at 236, against which this Court has warned.

Appreciating that "terms like 'insolubly ambiguous' may not be felicitous," Brief for Respondent 34, Biosig argues the phrase is a shorthand label for a more probing inquiry that the Federal Circuit applies in practice. The Federal Circuit's fuller explications of the term "insolubly ambiguous," we recognize, may come closer to tracking the statutory prescription. See, e.g., 715 F. 3d, at 898 (case below) ("[I]f reasonable efforts at claim construction result in a definition that does not provide sufficient particularity and clarity to inform skilled artisans of the bounds of the claim, the claim is insolubly ambiguous and invalid for indefiniteness." (internal quotation marks omitted)). But although this Court does not "micromanag[e] the Federal Circuit's particular word choice" in applying patent-law doctrines, we must ensure that the Federal Circuit's test is at least "probative of the essential inquiry." _Warner-Jenkinson Co. v. Hilton Davis Chemical Co_., 520 U. S. 17, 40 (1997). Falling short in that regard, the expressions "insolubly ambiguous" and "amenable to construction" permeate the Federal Circuit's recent decisions concerning §112, ¶2's requirement.[^9] We agree with Nautilus and its amici that such terminology can leave courts and the patent bar at sea without a reliable compass.[^10]

## IV [Case Remanded to Federal Circuit to Apply New "Reasonable Certainty" Standard.]

Both here and in the courts below, the parties have advanced conflicting arguments as to the definiteness of the claims in the '753 patent. Nautilus maintains that the claim term "spaced relationship" is open to multiple interpretations reflecting markedly different understandings of the patent's scope, as exemplified by the disagreement among the members of the Federal Circuit panel.[^11] Biosig responds that "spaced relationship," read in light of the specification and as illustrated in the accompanying drawings, delineates the permissible spacing with sufficient precision.

"[M]indful that we are a court of review, not of first view," _Cutter v. Wilkinson_, 544 U. S. 709, 718, n. 7 (2005), we decline to apply the standard we have announced to the controversy between Nautilus and Biosig. As we have explained, the Federal Circuit invoked a standard more amorphous than the statutory definiteness requirement allows. We therefore follow our ordinary practice of remanding so that the Court of Appeals can reconsider, under the proper standard, whether the relevant claims in the '753 patent are sufficiently definite. See, e.g., _Johnson v. California_, 543 U. S. 499, 515 (2005); _Gasperini v. Center for Humanities, Inc_., 518 U. S. 415, 438 (1996).

* * *

For the reasons stated, we vacate the judgment of the United States Court of Appeals for the Federal Circuit and remand the case for further proceedings consistent with this opinion.

It is so ordered.

APPENDIX

[^1]: In the Leahy-Smith America Invents Act, Pub. L. 112-29, 125 Stat. 284, enacted in 2011, Congress amended several parts of the Patent Act. Those amendments modified §§112 and 282 in minor respects not pertinent here. In any event, the amended versions of those provisions are inapplicable to patent applications filed before September 16, 2012, and proceedings commenced before September 16, 2011. See §§4(e), 15(c), 20(l), 125 Stat. 297, 328, 335, notes following 35 U. S. C. §§2, 111, 119. Here, the application for the patent-in-suit was filed in 1992, and the relevant court proceedings were initiated in 2010. Accordingly, this opinion's citations to the Patent Act refer to the 2006 edition of the United States Code.

[^2]: This difference in polarity occurs because the heart is not aligned vertically in relation to the center of the body; the organ tilts leftward from apex to bottom. App. 213.

[^3]: As depicted in figure 1 of the patent, id., at 41, reproduced in the Appendix to this opinion, the live electrodes are identified by numbers 9 and 13, and the common electrodes, by 11 and 15.

[^4]: Dr. Lekhtman's declaration also referred to an expert report prepared by Dr. Henrietta Galiana, Chair of the Department of Biomedical Engineering at McGill University, for use in the infringement litigation. That report described how Dr. Galiana's laboratory technician, equipped with a wooden dowel, wire, metal foil, glue, electrical tape, and the drawings from the '753 patent, was able in two hours to build a monitor that "worked just as described in the... patent." Id., at 226.

[^5]: See also Eibel Process Co. v. Minnesota & Ontario Paper Co., 261 U. S. 45, 58, 65-66 (1923) (upholding as definite a patent for an improvement to a paper-making machine, which provided that a wire be placed at a "high" or "substantial elevation," where "readers... skilled in the art of paper making and versed in the use of the... machine" would have "no difficulty... in determining... the substantial [elevation] needed" for the machine to operate as specified).

[^6]: See also United Carbon Co. v. Binney & Smith Co., 317 U. S. 228, 236 (1942) ("The statutory requirement of particularity and distinctness in claims is met only when they clearly distinguish what is claimed from what went before in the art and clearly circumscribe what is foreclosed from future enterprise."); General Elec. Co. v. Wabash Appliance Corp., 304 U. S. 364, 369 (1938) ("The limits of a patent must be known for the protection of the patentee, the encouragement of the inventive genius of others and the assurance that the subject of the patent will be dedicated ultimately to the public.").

[^7]: Online at [http://www.ftc.gov/sites/default/files/documents/reports/evolving-ip-marketplace-aligning-patent-notice-and-remediescompetition-report-federal-trade/110307/patentreport.pdf](http://www.ftc.gov/sites/default/files/documents/reports/evolving-ip-marketplace-aligning-patent-notice-and-remedies-competition-report-federal-trade/110307patentreport.pdf) (as visited May 30, 2014, and available in Clerk of Court's case file).

[^8]: See, e.g., Every Penny Counts, Inc. v. Wells Fargo Bank, N. A., ___ F. Supp. 2d ___, ___, 2014 WL 869092, *4 (MD Fla., Mar. 5, 2014) (finding that "the account," as used in claim, "lacks definiteness," because it might mean several different things and "no informed and confident choice is available among the contending definitions," but that "the extent of the indefiniteness... falls far short of the 'insoluble ambiguity' required to invalidate the claim").

[^9]: E.g., Hearing Components, Inc. v. Shure Inc., 600 F. 3d 1357, 1366 (CA Fed. 2010) ("the definiteness of claim terms depends on whether those terms can be given any reasonable meaning"); Datamize, LLC v. Plumtree Software, Inc., 417 F. 3d 1342, 1347 (CA Fed. 2005) ("Only claims 'not amenable to construction' or 'insolubly ambiguous' are indefinite."); Exxon Research & Engineering Co. v. United States, 265 F. 3d 1371, 1375 (CA Fed. 2001) ("If a claim is insolubly ambiguous, and no narrowing construction can properly be adopted, we have held the claim indefinite."). See also Dept. of Commerce, Manual of Patent Examining Procedure §2173.02(I), p. 294 (9th ed. 2014) (PTO manual describing Federal Circuit's test as upholding a claim's validity "if some meaning can be gleaned from the language").

[^10]: The Federal Circuit suggests that a permissive definiteness standard "'accord[s] respect to the statutory presumption of patent validity.'" 715 F. 3d 891, 902 (2013) (quoting Exxon Research, 265 F. 3d, at 1375). See also §282, ¶1 ("[a] patent shall be presumed valid," and "[t]he burden of establishing invalidity of a patent or any claim thereof shall rest on the party asserting such invalidity"); Microsoft Corp. v. i4i Ltd. Partnership, 564 U. S. ___, ___ (2011) (slip op., at 1) (invalidity defenses must be proved by "clear and convincing evidence"). As the parties appear to agree, however, this presumption of validity does not alter the degree of clarity that §112, ¶2 demands from patent applicants; to the contrary, it incorporates that definiteness requirement by reference. See §282, ¶2(3) (defenses to infringement actions include "[i]nvalidity of the patent or any claim in suit for failure to comply with... any requirement of [§112]"). <br/> <br/> The parties nonetheless dispute whether factual findings subsidiary to the ultimate issue of definiteness trigger the clear-and-convincing evidence standard and, relatedly, whether deference is due to the PTO's resolution of disputed issues of fact. We leave these questions for another day. The court below treated definiteness as "a legal issue [the] court reviews without deference," 715 F. 3d, at 897, and Biosig has not called our attention to any contested factual matter—or PTO determination thereof—pertinent to its infringement claims.

[^11]: Notably, however, all three panel members found Nautilus' arguments unavailing.