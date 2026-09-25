---
layout: sketchbook
title: Initiate Research with an Annotated Bibliography
summary: "This sketch demonstrates how to construct a prompt for a high quality annotated bibliography."
thumbnail: "images/card-catalog.jpg"
date: 2026-09-01
status: tested
type: LLM orientation
effort: "less than 10 minutes"
tools:
  - Claude Fable 5.1
level: any
author: "Jonathan Seyfried"
tags:
  - prompting
  - model tiers
  - citations
results:
  - a sophisticated and reliable annotated bibliography to initiate research
what-i-learned:
  - when prompted with specifications, higher tier LLMs will provide reliable citations
  - the higher tier LLM will also notice and challenge assumptions in a prompt
card_order: 20
---

# Initiate Research with an Annotated Bibliography

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

How good is a top-tier LLM at building an annotated bibliography for a brand-new research topic? I put one to the test.

In his 2026 monograph, *Using Generative AI in Historical Practice*, Yaniv Fox discusses two terms that he sees as integral to sophisticated use of AI by historians: agency and taste.[^yf] *Agency* is conceiving and framing a new research question. *Taste* is judging the LLM's output for quality and reliability. Both require expertise. 

[^yf]:Yaniv Fox, *Using Generative AI in Historical Practice* (Cambridge University Press, 2026), 16.


{% include typography/pullquote.html text="Agency and taste: two names for what expertise does when working with generative AI." %}

## The Experiment
To try out Fox's ideas, I gave a high-tier LLM, Claude Fable 5.1, a research question about the decline of McCarthyism in the decades after the Red Scare, then used Claude's **Research** button to get an annotated bibliography. 

## The Prompt

{% include typography/sketch-prompt.html label="prompt to give to Claude Fable 5.1" text="I'd like you to help me answer the question of how the USA's political and cultural leaders restored norms in the wake of McCarthyism. Please provide me with some specific examples that illustrate the history of the rolling back of McCarthyism from its peak during the Red Scare and through the following decades. I specifically want to know the names of key people in this history and also any popular culture products that were influential. In your response, please cite some scholarly monographs and journal articles, including ISBNs, DOIs, and full bibliographic citations." %}


## Results
Claude Fable 5.1 opened by questioning my prompt. I had assumed a scholarly consensus that McCarthyism was rolled back, when some scholars argue that pre-McCarthy norms were never restored. Still, within twenty years of its rise, McCarthyism was over: the congressional committees disbanded, and blacklisted people regained their standing. My own knowledge of the period told me not to take Claude's challenge to my framing too literally. That judgment is what Fox calls *taste*.

{% include images/figure-wrap.html
  class="center"
  width="90%"
  caption="Response from Claude Fable 5.1."
  image-path="images/mccarthy-claude-framing.png"
  text = text
%}

After that framing, Claude [answered](pdfs/mccarthyism-chat-claude-fable5.1-2026.pdf) with short summaries of the key people's roles and a three-part bibliography, with ISBNs for six books and DOIs for three journal articles. Then it offered a **Research** button. Clicking it produced a [separate report](pdfs/rolling-back-mccarthyism-claude-fable5.1-2026.pdf) with more than forty sources, each with a confirmed ISBN or DOI.  

{% include images/figure-wrap.html
  class="center"
  width="90%"
  caption="Sample of the annotated bibliography generated through the Research function."
  image-path="images/mccarthyism-annotated-bib-sample.png"
  text = text
%}

## What I Learned
Asking for a synthesis of scholarship on the decline of McCarthyism was *agency*. Checking the citations and weighing Claude's challenge to my framing was *taste*.

High-tier LLMs like Claude Fable 5.1 can give researchers a sophisticated starting point. LLM summaries can narrow how a researcher first sees a topic, but they can also point toward interpretive directions the researcher hadn't considered. Requiring ISBNs, DOIs, or the best available citation information in the prompt pushes the model toward reliable sources, and [hallucinated sources](model-tiers.md) are now rare in the higher-tier models.
