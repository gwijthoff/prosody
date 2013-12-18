---
title:  Mellon Report | Princeton Prosody Archive
author: |
   Meredith Martin \| Princeton University, Department of English\
   Grant Wythoff \| Columbia University, Society of Fellows\
date:  December 2013
bibliography: /Users/grantwythoff/TeX/zotero.bib
---

## 1.	Objectives *(A brief review of the project objectives and any changes that have occurred):*

We are happy to report that all objectives set out for the AY 2012-2013 in our initial grant proposal have been completed.  Most importantly, we compiled the first data set for the Princeton Prosody Archive (PPA): 8,742 full text books on poetry, poetics, and the measure of language.  While we initially planned to gather texts from a number of resources (including Google Books) and digitize the remainder ourselves, we decided to work with HathiTrust digital library to collect, organize, and download all of our data.  Using HathiTrust's "collection" feature and negotiating a Google Distribution Agreement between Princeton University Library, Princeton Counsel, and HathiTrust allowed us to access, download, and host all of this data on our own servers.  Once we received all of our data from HathiTrust, we set up a web portal using the content management system Drupal and a Solr search module.

On May 13, 2013, we hosted an international group of literary scholars and technologists (see the attached agenda) to provide input on the PPA in its early inception.  These twenty-four participants were the first to test our search interface, help us plan our next steps, and think about access issues and long term maintenance for the next five years.

## 2.	Deliverables *(Clear, concise description of the expected outcomes and benefits of the project):*

- Collect every record in Terry Brogan’s annotated bibliography English Versification, 1570-1980 for versification in English between 1750-1923.
- Collect multiple editions of each of the most important grammars of the English language
- Assemble the first ever comprehensive historical collection of writings on English prosody, poetics, and versification
- Use the latest techniques in topic modeling to discover machine connections in this collection of texts
- Launch beta version of a web interface
- Host a summit of technologists and scholars of historical poetics

## 3.	Accomplishments *(A brief summary of progress made towards realizing those deliverables since the last reporting period):*

At the Summit, the group was able to test-drive the Archive for the first time. There was unanimous agreement that a key strength of the Archive is its curation: Comprising more than 8,500 texts on English versification published between 1750 and 1923 (including reproductions and revisions), the Archive possesses immense potential for tracking prosodic discourse. Using Terry Brogan's definitive *English Versification, 1570-1980* and the research records of Meredith Martin as a guide, project manager Grant Wythoff organized the following four collections digitized by HathiTrust:

- Brogan's *English Versification* (578 works collected by Terry V. F. Brogan)
- Prosody Archive (1308 works collected by Meredith Martin)
- PPA Subject Search (6991 works categorized under the keywords that librarians have been using to index texts on versification)
- Graphically/Typographically Unique (26 works set aside as possessing especially troubling or interesting page images that would be misread by OCR) 

A spreadsheet of all texts hosted by the Archive can be found [at this link](https://docs.google.com/spreadsheet/ccc?key=0As9CC5gogHU5dDQwZ2dqejFDRC02MC1LR3J1NFp3N2c&usp=drive_web#gid=0).

Taking the Archive for a spin was also incredibly helpful in looking for ways to improve it. One of the key issues, and one that drives the methodology for the archive, is the OCR output of texts. Not only are we dependent upon the scans of HathiTrust's partner institutions, but Hathi's OCR as well. When dealing with versification this becomes especially problematic, as the small groups at the Summit experienced firsthand. How do you render musical annotation, scansion, line spacing, or iambic markings, for example, into plain text? And how can we correct and then implement these corrections back into Hathi's collection?

One idea that emerged during the Summit that we are currently working on is a "case study" of a few pages of Coventry Patmore's *English Metrical Law.* This initiative stems from the expressed desire to visualize/connect a network of prosodic discourse. We are looking for methods by which we can showcase the self-referential nature of prosody as well as implement pedagogically helpful tools — e.g. translations from passages in foreign languages, links to referred texts, audio that would read back given musical annotation/scansion, etc. These more interactive features are things we would be looking at much further down the line.  However, in the near future, Clifford Wulfman, Coordinator of Library Digital Initiatives at Princeton, will be helping us begin to tag our own scans of the different versions of Patmore's essay using Text Encoding Initiative (TEI) standards.

## 4.	Challenges *(Any setbacks or challenges since the last reporting period):*

This summer, our developer Travis Brown (see personnel changes, below) dealt with a setback due to a change in the new Drupal 7, the Archive's platform. In a nutshell, the updated version of Drupal introduced a new model, Entity API. This model conflicted with the Bibliography module the development site was running in Drupal 6 in that Bibliography module items were not formatted as "entities." For this reason, and because of limited access to Travis's time as an independent contractor, the fully indexed site that we had desired to release by the end of summer 2013 was not available. Travis is working on reconciling the change by rendering Bibliography items as entities with some creative maneuvering, but we are still in the process of uploading the site unto Princeton servers. In short, this change has set us back a few months, but an accessible version of the collection will have been migrated from our development site to <http://prosody.princeton.edu> in the coming months.

## 5.	Project Personnel *(Significant board, management, or staff changes since the last reporting period):*

In addition to the Advisory and Technology boards listed in the grant proposal, there have been two significant additions to our team.  Meagan R. Wilson, a PhD student in the Department of English at Princeton, has taken over as project manager for Grant Wythoff, who began a postdoc at Columbia University in September 2013.  Second, Travis Brown, Assistant Director of Research and Development at the Maryland Institute for Technology in the Humanities (MITH), has taken on a very prominent role in helping us develop the Archive.  Brown was first hired to help us incorporate the collections of text we received from HathiTrust into a Drupal-based web platform, a task which was beyond our immediate expertise. It is important to note that all of Brown's work was paid for using existing funds from a Princeton University grant we received from the [David A. Gardner '69 "Magic" Project](http://humanities.princeton.edu/grants/magic).

## 6.	Publications *(A description of any recent publications, new articles, or other grant-related materials):*

Martin, Wythoff, Wilson, and Brown have submitted a long paper proposal to the Digital Humanities 2014 conference in Lausanne, Switzerland. This long paper will reflect on the outcomes of the grant year, as well as some of the challenges and opportunities presented by launching a large-scale digital archive at an institution with no digital humanities infrastructure. We are waiting to hear back from conference organizers.

## 7.	Intellectual Property *(Projects subject to an intellectual property agreement should include with the final report the codes, license or related technologies developed during the project, or explain how they may be obtained by the Foundation):*

All software used by our team in the development of the Archive was open source, including our content management system (Drupal) and search library (Apache Solr).  Because, as stated in the intellectual property agreement, "'Digital Content' does not include content neither created by nor for Princeton in connection with this Project, but made available to Princeton by organizations such as Google, HathiTrust, etc.," the texts made available to us by HathiTrust and originally digitized by them do not fall under the purview of our Intellectual Property agreement with the Mellon Foundation.

Travis Brown, who was hired using funds from another grant (David A. Gardner Magic Project), has released all of the code he wrote for our project under an open source [Apache License, v. 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).

## 8.	Future Plans *(Plans and goals for the upcoming grant year):*

Though our Mellon award period has ended, we detail future plans below.  In discussing next steps, we have been looking at crowdsourcing tools such as TypeWright, which allows users to correct OCR on 18th Century texts, discussing a potential to enlisting students for help cleaning up the Archive's OCR.  Documentation for search syntax and perhaps suggested keywords and/or a prosody glossary was suggested. And because prosody criticism is exceptionally visual, many users asked for a way to see thumbnails in addition to plain text in the search results window.

Users have suggested that we might incorporate case studies, editorials, blog entries, or other means for modeling pathways through the Archive, hosted directly on the Archive site.  Several ideas for tracing versification networks were also proposed. A few gathered around visualization: This would be extremely effective in tracking the frequency of prosody terms across time and/or region. Other users suggested a "cite-back" tool: This would work like a bibliographic network whereby a user could track which critics cited other prosodists. Because this would be fairly challenging, it was recommended that perhaps this could be managed within a closed network of around 40 texts.

We will continue to work with Travis Brown and MITH to address the incredibly helpful feedback we received at the Summit.  We are most excited by the possibility of standardizing a workflow for future users of HathiTrust data, wherein those individual users' curation of that data can be fed back into the larger HathiTrust ecosystem.

The first big push will be to improve the Archive's HathiTrust-dependent metadata. In his capacity as a software developer at MITH, Travis has been working on automated corrections for punctuation standardization and keyword unification. As each item in the Archive has a HathiTrust record created by its partner institutions, keywords can be idiosyncratic in nature. This step aims at freeing the Archive from some of these idiosyncratic keywords that HathiTrust partners used for cataloging texts, providing richer/more standardized descriptions in a given text's record.  Travis will also be working on text correction and filtering. As we found during the Summit, the Archive is composed of items with uncorrected OCR output, which distorts search results. To modify this, we will perform simple dictionary-based text correction and filtering of pages that pass an error threshold to be determined experimentally.

After working on these interface enhancements, Travis will begin experimenting with named-entity recognition and topic modeling in an effort to demonstrate output and visualizations. Once implemented, we will be tapping on all of you for feedback, having the test site up and running with these additions. Travis and Kirsten Keister, a designer for MITH, will be integrating user feedback and finalizing user design. We envision this happing in early 2014, including the production of a final site design mockup. Travis and Kristin will begin translating the design mockups into Drupal, incorporating additional metadata corrections, and, very importantly, documenting the work performed.

## 9.	Financial Narrative *(A financial section commenting on actual expenditures during the current reporting period as they relate to the proposed budget, and an explanation of any significant variance between projected spending and actual spending in each budget category):*

There were no significant variances between projected and actual spending during the year.  The majority of the grant went toward personnel (graduate student research assistant salary, faculty summer salary, and fringe faculty benefits).  The remainder went toward airfare, train, and hotel accommodations for those summit participants traveling from out of town.

Remaining Balance: $0.00
Interest Credited to Date: $23.87

## 10.	Endowment Reporting *(For endowment grants, grantees should report on the market value at the start of the reporting period, the market value at the end of the reporting period, the status of any matching requirement, expenditures on the spendable portion, and a general statement on investment strategy):*

n/a