---
permalink: /about/
title: "About"
last_modified_at: 2022-04-15
---

## What's in YRDL? 

The short answer: a lot of different things 

The long answer: 
 Our initial corpus-building stage prioritized several subgenres—including “Hi-Lo” novels, LGBTQ+ novels, and popular series for girls—that have often been overlooked in favor of prestige literature, opening up new possibilities for quantitative research on young readers’ fiction that reaches beyond award-winners and immediately-recognizable titles. We've also focused on acquring titles from our various awards lists, mass-market paperback titles, and texts on various Young Readers' bibliographies. 

#### Why young readers? Why not Children's or YA? 

Deciding to focus on just Children's, Middle-grade, or YA literature from the beginning would have limited the work we wanted to do—including work on identifying the features that distinguish between these categories. Instead, we created a large database with a loose understanding of "fiction for young readers" to cast a wide net. Our database approach requires us to assemble sub-corpora based on explicitly articulated criteria for every research question we ask. This means YRDL is not a representative sample of "YA" or "Children's" or "Middle-grade"—categories that are fuzzy not only in the contemporary moment, but also over time—but it does contain works from all three.

## Our metadata

### Readability metrics: 
We calculate readability/difficulty metrics for each text using textstat in Python. (link) Our database contains the following metrics: 

- Flesch Ease
- Gunning-Fog
- ARI 
- SMOG
- Dale-Chall
- Linsear-Write
- Coleman-Liau
- Flesch-Kincaid 
- Lexcount (textstat's wordcount)
- Sentences (textstat's sentence count)
- Consensus (textstat's best guess at a grade-level based on the other scores)


### Authority lists 
Not only do we use various authority lists to find texts to include in our database, we think a text's inclusion on the list is valuable metadata itself, so we track it. 

Some of the lists we create metadata from: 

- Critical bibliographies 
- Fan & Best-of lists
- Awards lists 


### Horn Book 
For texts that were reviewed by the Horn Book prior to 2018, we collect review scores for individual titles using scanned pages, optical character recognition, and manual cleaning, checking, and entry. 


### Series & Series Position 