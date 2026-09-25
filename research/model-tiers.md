---
layout: sketchbook
title: Effect of Model Tiers on LLM Responses
summary: "This sketch shows the difference in response quality baseed on the LLM model tier."
thumbnail: "images/istanbul-bridge.jpg"
date: 2026-09-01
status: tested
type: LLM orientation
effort: "less than 10 minutes"
tools:
  - Claude Opus 5
  - Gemini Flash Lite
level: any
author: "Jonathan Seyfried"
tags:
  - prompting
  - model tiers
  - hallucinations
results:
  - hallucinations occur far less frequently with higher tier models
what-i-learned:
  - the LLM model tier makes a significant difference in prompt response quality
  - lower tier LLMs generate less reliable responses
card_order: 20
---

# The Effect of Model Tiers on LLM Responses

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Early reports of AI hallucinations made many people skeptical of LLMs. As of 2026, though, high-tier models hallucinate far less often. The catch: free tiers typically send your query to an older model. Pay for a higher tier and you'll see a dramatic drop in inaccurate responses. 

{% include typography/pullquote.html text="Higher-performing models give noticeably better answers." %}

## The Experiment
Free-tier LLMs on default settings often struggle with prompts that ask for highly specific information: they answer without checking themselves. Paid-tier models check their work before responding. To show the difference, I gave the same specific prompt to the free tier of Gemini and a paid tier of Claude.

## The Prompt

{% include typography/sketch-prompt.html label="prompt to give to the LLM" text="What did Huizinga say about court ceremony in The Waning of the Middle Ages? Quote the passage with page number." %}


## Results
Gemini Flash Lite gave an almost entirely useless response, below. Its quotation isn't about court ceremony at all; it's the opening sentence of the book.
{% include images/figure-wrap.html
  class="center"
  width="90%"
  caption="Response from Gemini Flash Lite."
  image-path="images/gemini-flash-lite-sep1-2026-huizinga.png"
  text = text
%}

Claude Opus 5 found material in *The Waning of the Middle Ages* that genuinely connects to court ceremony, and it didn't fabricate page numbers.

{% include images/figure-wrap.html
  class="center"
  width="90%"
  caption="Response from Claude Opus 5."
  image-path="images/claude-opus5-sep1-2026-huizinga.png"
  text = text
%}

## What I Learned
The quality gap between free, lower-tier models and paid, higher-tier ones is easy to demonstrate. As of 2026, the newest LLMs are trained with reinforcement learning as well as pattern recognition, so they work less like giant spell-checkers and more like pathfinders. That's part of why their output keeps getting more reliable. 
