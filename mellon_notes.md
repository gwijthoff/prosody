Hi Everyone,

I am writing to give a long overdue update on the Princeton Prosody Archive. A lot has occurred since our very generative Summit in May. The first big change is my involvement. Upon defending his dissertation in August, Dr. Grant Wythoff has joined Columbia as a Postdoc. I will be taking over as Project Manager, and I am very much looking forward to working with all of you as we continue to develop the Archive.

Before I delve into the specific challenges and opportunities we have encountered in the last several months, I also want to give a synopsis for those who were not able to attend the Summit and test-drive the Archive (and perhaps give a nice refresher for those who did attend). Here are the highlights, but I should also give the caveat that this is a relatively long email given all the exciting information we have to impart! Here is what this update covers at a high level:

Summit Summary (including an overview of the collection, a synthesis of reactions to the Archive, and proposed wish lists)
Summer Challenges (detailing the technology troubles we encountered)
2013-2014 Initiatives (introducing the development Travis Brown is undertaking, beginning a case study of Coventry Patmore's "English Metrical Law," and upcoming initiatives such as an NEH grant application and DH2014)
Summit Summary

Archive Overview

At the Summit, the group was able to test-drive the Archive for the first time. There was an unanimous agreement that a key strength of the Archive is its curation: Comprising more than 8,500 texts on English versification published between 1750 and 1923 (including reproductions and revisions), the Archive possesses immense potential for tracking prosodic discourse. The Archive exists as four collections digitized by HathiTrust, all which are available by searching HathiTrust collections:

Brogan's English Versification, 1570-1980 (578 works collected by Terry V. F. Brogan)
Prosody Archive (1308 works collected by Meredith Martin)
PPA Subject Search (6991 works categorized under the keywords that librarians have been using to index texts on versification)
Graphically/Typographically Unique (26 works set aside as possessing especially troubling or interesting page images that would be misread by OCR) 
A database of all texts in the Archive is available here.

Test-drive Reactions

Taking the Archive for a spin was also incredibly helpful in looking for ways to improve it. One of the key issues, and one that drives the methodology for the archive, is the OCR output of texts. Not only are we dependent upon the scans of HathiTrust's partner institutions, but Hathi's OCR as well. When dealing with versification this becomes especially problematic, as the small groups at the Summit experienced firsthand. How do you render musical annotation, scansion, line spacing, or iambic markings, for example, into plain text? And how can we correct and then implement these corrections back into Hathi's collection? We looked at crowdsourcing tools such as TypeWright, which allows users to correct OCR on 18th Century texts, discussing a potential to enlisting students for help cleaning up the Archive's OCR.

Future Wish Lists

The search interface was also an issue for users. The Archive had multiple search boxes, which returned different results with the same word search, and it was unclear how results were ranked and ordered (date, frequency of search term, etc.). Documentation for search syntax and perhaps suggested keywords and/or a prosody glossary was suggested. And because prosody criticism is exceptionally visual, many users asked for a way to see thumbnails in addition to plain text in the search results window.

Because the Archive links users to the HathiTrust to actually access texts, it was unclear how the Prosody Archive would complement what was already available through a collections search in HathiTrust. Users suggested case studies, editorials, blog entries, or other means for modeling pathways through the Archive to be hosted directly on the Archive site.

Several ideas for tracing versification networks were proposed. A few gathered on visualization: This would be extremely effective in tracking the frequency of prosody terms across time and/or region. Other users suggested a "cite-back" tool: This would work like a bibliographic network whereby a user could track which critics cited other prosodists. Because this would be fairly challenging, it was recommended that perhaps this could be managed within a closed network of around 40 texts.

Helpful notes from participants of the Summit can be found here. 

Summer Challenges

This summer, our developer Travis Brown dealt with a setback due to a change in the new Drupal 7, the Archive's platform. In a nutshell, the updated version of Drupal introduced a new model, Entity API. This model conflicted with the Bibliography module the development site was running in Drupal 6 in that Bibliography module items were not formatted as "entities." For this reason, and because of limited access to Travis's time as an independent contractor, the fully indexed site that we had desired to release this summer was not available. Travis is working on reconciling the change by rendering Bibliography items as entities with some creative maneuvering, but we are still in the process of uploading the site unto Princeton servers. In short, this change has set us back a few months.

2013-2014 Initiatives

Archive Development

Starting in fall, we have continued working with Travis and MITH to address the incredibly helpful feedback we received at the Summit. The first big push is to improve the Archive's HathiTrust-dependent metadata. In his capacity as a software developer at MITH, Travis has been working on automated corrections for punctuation standardization and keyword unification. As each item in the Archive has a HathiTrust record created by its partner institutions, keywords can be idiosyncratic in nature. This step aims at freeing the Archive from some of these idiosyncratic keywords that HathiTrust partners used for cataloging texts, providing richer/more standardized descriptions in a given text's record.  

Travis will also be working on text correction and filtering. As we found during the Summit, the Archive is composed of items with uncorrected OCR output, which distorts search results. To modify this, we will perform simple dictionary-­based text correction and filtering of pages that pass an error threshold to be determined experimentally. As the confusion of search result organization/ranking was a common complaint by users during the Summit, Travis will also implement a total result count and a result count per collection count to improve functionality, with aspects of this work building on the Drupal-based platform that MITH developed for the Shelley-Godwin Archive (which you should all check out — it is really well done). 

After working on these interface enhancements, Travis will begin experimenting with named-entity recognition and topic modeling in an effort to demonstrate output and visualizations. Once implemented, we will be tapping on all of you for feedback, having the test site up and running with these additions. Travis and Kirsten Keister, a designer for MITH, will be integrating user feedback and finalizing user design. We envision this happing in early 2014, including the production of a final site design mockup. Travis and Kristin will begin translating the design mockups into Drupal, incorporating additional metadata corrections, and, very importantly, documenting the work performed.

Technologists: This is an open call to you. If you would like to be involved in any aspect of the technology side of things, please let me know. We are beginning to draft our concrete plans for the future and need your help.  

Patmore Case Study

One idea from the Summit that we are currently working on is a "case study" of a few pages of Coventry Patmore's "English Metrical Law." This initiative stems from the expressed desire to visualize/connect a network of prosodic discourse. We are looking for methods by which we can showcase the self-referential nature of prosody as well as implement pedagogically helpful tools — e.g. translations from passages in foreign languages, links to referred texts, audio that would read back given musical annotation/scansion, etc. These more interactive features are things we would be looking at much further down the line, but in the near future, Cliff Wulfman will be helping us begin to tag our own scans of the different versions of Patmore's essay using Text Encoding Initiative (TEI) standards. 

We have tapped a few prosodists from the group, but if you would like to participate, or have models we could look at, please let me know. Thus far we have merely printed out a few pages and started to mark them up, but the more the merrier –  I will send those pages to you.

Funding/DH2014

One major funding push will be applying for an NEH Digital Humanities Implementation Grant in February. This is another open call to anyone who has undergone this process: We will need help. For now, please send me your CVs! The proposal requires brief (two-page) resumes for each of the principal project participants, as well as members of the advisory board.

Also exciting: We have submitted a long paper proposal, "Building the Princeton Prosody Archive," for DH2014, held in July at Lausanne, Switzerland. We will send an update regarding acceptance (fingers crossed!) when it is announced in February.

I will end here, because this update is already quite long. If you have any questions or comments to share with the group — please do not hesitate to reach out. I will send out our indexed and retooled development site as soon as we have it available, as I know everyone is eager to play around with the implementations Travis has been working on in the last few months.

Again, I am looking forward to working with you all!

Best,

Meagan

====

A link to the PPA collection in HathiTrust.
Here are links to all four HathiTrust collections.  I have no idea why they don't show up under any keyword searches, since I have them marked public, but these links should work.
Brogan's English Versification, 1570-1980 (578 items)
Every pre-1923 (i.e. out of copyright) book on prosody/meter/verse/versification etc. listed in Terry Brogan's annotated bibliography "English Versification."  Note that this leaves out all dissertations and journal articles, some of which we have but aren't on HathiTrust and because they've been digitized by Project Muse, EEBO, etc., we don't have the rights to collect them. 
The book is available online here: http://depts.washington.edu/versif/resources/evrg/
We were able to extract every citation and create a spreadsheet that me and an undergrad research asst James Bedell went through and categorized.  You can find those spreadsheets in this Google docs folder.  They will be useful down the line if we ever want to try and get the articles, dissertations, and various ephemera in Brogan (some of which his widow, who was in contact with Meredith, has said she will donate to us out of his private collection.
Graphically / Typographically Unique (26 items)
books with graphically unique features that allowed us to convince HathiTrust (and Google) to provide us with the PDFs of these books, rather than merely the text files produced by OCRing the books.
PPA Subject Search (6,991 items)
a collection of every single book listed under certain subject keywords (English metrics, nineteenth century versification, etc).  A complete list of those keywords was attached to the documentation I sent to the advisory board in advance of our summit.
Prosody Archive (1,308 items)
Miscellaneous books we've collected over the years that weren't listed in Brogan.
Travis's contact information. 
travisrobertbrown@gmail.com
trbrown@umd.edu
202-760-1132 (cell)
301-405-8927 (directory listed office phone)
@travisbrown (twitter)
 
Our current Mellon grant application. My understanding is we have funds that we must use by October, and if we are reapplying, which I assume we are, it will be helpful to get a look at the full document.
Attached!
A breakdown on other financing/timing on financing renewal. It sounds like Nancy Shillingford might be the best resource for this, but I'd love any kind of cheat sheet available to familiarize myself with the what/where/when of our funding. 
cc'd you on an email to Nancy -- we'll know once John Orluk is back in the office at the end of August.
The near, mid, and far range goals of the project. This will help me gauge where we are in terms of the aspirations we set forth at the Summit. 
The roadmap (which we're long since behind on) can be found in my main summit notes (link below), which also has a summary of the three main approaches to the archive (fulltext search / visualization / curated core collections).  We were planning to use these three divisions to subdivide the advisory board once we have everything live on our servers at prosody.princeton.edu -- once Travis transfers things over to us, we can say, okay, the site is live, go play!  And, which of these three groups would you like to participate in, and who can serve as coordinator for each of these groups?
https://docs.google.com/document/d/1RcUNuai_Qqd8t7t7Whdm5oDJAjlGCyW64x2qT8UpWP4/edit?usp=sharing
Other documents in that folder include notes from advisory board members from the summit.
Access to the PPA DropBox. I've asked Grant to do a major dump of all his files. My first goal is to sift through this material to immerse myself in all things PPA.
I've attached a zip file of all my raw notes on meetings, phone calls, schedules, funding, etc etc. Let me emphasize that it's *really* raw, so if you have any questions, don't hesitate to ask.
Here is a link to the only files we have left in the Dropbox shared with Ben Johnston -- a bunch of records from our initial, pre-HathiTrust pre-Travis install of Drupal.  We're using all of the data given to us by Hathi now, but it'll still be useful to have that stuff around.
I've shared a folder with you on Princeton's Webspace simply called "Prosody."  In there, you'll find some old layers from one of the many pre-Hathi iterations of the archive -- the citation info we were able to scrape from Brogan, some initial PDFs, etc.  It's mainly useful as a place to ferry files back and forth with Ben Johnston and anyone else at Princeton you may need.
I've shared a Dropbox folder with you called "Prosody Dump."  Everything is still uploading now, and should be ready in an hour or so.  Can you tell me once you copy them onto your own computer so that I can delete them from Dropbox?  There's quite a lot of data in there (a bunch of PDFs that were given to us by Ben Bunnel at Google Books with the flick of a wrist, PDFs in various states of organization), and I don't want it to clog up our cloud storage too much.