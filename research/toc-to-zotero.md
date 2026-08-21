---
layout: sketchbook
title: Table of Contents to Zotero
summary: "With one prompt get entries in Zotero from a book of essay chapters."
thumbnail: "images/zotero-toc.png"
date: 2026-08-21
status: tested
type: citation work
effort: "less than 10 minutes"
tools:
  - Claude
  - Zotero
level: any
tags:
  - citations
  - prompting
  - agentic AI
results:
  - extracted data from the Table of Contents
  - built a file in BibTeX format
  - imported to Zotero
what-i-learned:
  - how to save time when creating citations for essay collections
  - options for incorporating agentic AI into bibliographic work
card_order: 20
---

# Table of Contents to Zotero

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

In my research, I often come across essay collections in which almost all the chapters will end up in a footnote in one of my papers. Often, Google Scholar lacks correct pagination data for these book sections and in the past it took me a long time to enter in all entries for them into Zotero. I wanted to know if AI could handle this drudgery for me.

{% include typography/pullquote.html text="From a Table of Contents on a publisher's website to book sections in Zotero in under ten minutes." %}

## The Experiment
To test the capabilities of AI, I used the [Table of Contents webpage](https://academic.oup.com/edited-volume/34632) for the essay collection *The Oxford Handbook of Public History.* First, I tried the Zotero extension on this webpage, but it failed to import page numbers and put the editors in as authors.

I then asked Claude to create BibTeX entries for each of the chapters that I could then import into Zotero.

## The Prompt

{% include typography/sketch-prompt.html label="prompt to give to Copilot" text="There is a 2017 essay collection titled The Oxford Handbook of Public History edited by Hamilton and Gardner (DOI 10.1093/oxfordhb/9780199766024.001.0001). I want a single text file list of all the chapters to import into Zotero. So I would like you to make a single text file that includes a BibTeX entry for each of the chapters. In addition to the default BibTeX output for each chapter, please ensure that each BibTeX entry has the item type "book section", the page numbers of the chapter, and the editors as Paula Hamilton and James B. Gardner." %}


## Results
Not only did Claude create the BibTeX entries perfectly, but since I was using the Claude app, at the end I got a button called **Open in Zotero**. I clicked that and then got a new collection folder in Zotero with everything in it. 

Claude corrected my error to ensure that the item type code was correct. It also made the file into a .bib without my asking for that.

## What I Learned
I learned that AI can help me to reduce the amount of time spent on bibliographic drudgery. I also learned that Claude, using one of the advanced models such as Opus 4.8, will not make any mistakes in compiling a small amount of data when you prompt it to do a simple data transfer task. 
