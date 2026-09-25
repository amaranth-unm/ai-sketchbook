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
author: "Jonathan Seyfried"
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

I often run into essay collections where nearly every chapter will end up in one of my footnotes. Google Scholar often lacks correct page numbers for these chapters, and entering them all into Zotero by hand used to take forever. Could AI handle the drudgery?

{% include typography/pullquote.html text="From a publisher's table of contents to a Zotero entry for every chapter, in under ten minutes." %}

## The Experiment
My test case was the [table of contents page](https://academic.oup.com/edited-volume/34632) for *The Oxford Handbook of Public History*. The Zotero browser extension failed on it: no page numbers, and the editors listed as authors.

So I asked Claude to create a BibTeX entry for each chapter that I could import into Zotero.

## The Prompt

{% include typography/sketch-prompt.html label="prompt to give to Copilot" text="There is a 2017 essay collection titled The Oxford Handbook of Public History edited by Hamilton and Gardner (DOI 10.1093/oxfordhb/9780199766024.001.0001). I want a single text file list of all the chapters to import into Zotero. So I would like you to make a single text file that includes a BibTeX entry for each of the chapters. In addition to the default BibTeX output for each chapter, please ensure that each BibTeX entry has the item type 'book section', the page numbers of the chapter, and the editors as Paula Hamilton and James B. Gardner." %}


## Results
Claude produced the BibTeX entries perfectly. Because I was using the Claude app, it also offered an **Open in Zotero** button; one click, and a new Zotero collection appeared with everything in it.

Claude even fixed my mistake in the item type code, and saved the file as a .bib without being asked.

## What I Learned
AI can cut the time I spend on bibliographic drudgery. With an advanced model like Opus 4.8, Claude handled this small, simple data-transfer task without a single mistake. 
