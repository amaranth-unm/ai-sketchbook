---
layout: sketchbook
title: Citation Test
summary: "Students verify an AI-generated reading list and discover how convincingly LLMs invent sources that sound real but do not exist."
thumbnail: "images/eniac-beck-snyder.jpg"
thumbnail-credit: 'Glen Beck and Betty Snyder program the ENIAC, Ballistic Research Laboratory, c. 1947. U.S. Army photo.'
date: 2026-03-28
status: refined
type: activity
effort: "30–40 min in class"
tools:
  - ChatGPT
  - Claude
level: any
author: "Fred Gibbs, History"
tags:
  - source evaluation
  - AI literacy
key-question: "How can AI output help students learn scholarly integrity?"
what-students-learn:
  - why polished prose is not evidence of accuracy
  - how hallucination happens and why it's convincing
  - verification is a scholarly habit that connects classroom work with library expertise
card_order: 20
---

# Citation Test

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Ask AI for a reading list on a focused scholarly topic, then hunt down the citations together as a class. Some are real. Some are garbled. Some are pure invention that sounds perfectly plausible, and those are the ones worth lingering over.

{% include typography/pullquote.html text="Fluent prose and tidy bibliographic formatting don't guarantee that a source exists. Once students see that, verification stops feeling like a library ritual and starts feeling necessary." %}

## The Setup

Pick a topic narrow enough to sound scholarly but broad enough that students won't know the literature by heart. Ask AI for eight to ten key books and articles. Then students track each citation through library catalogs, publisher pages, journal databases, and Google Scholar.

It works individually or in teams, with each team taking two or three citations and reporting back. The room usually ends up with a mix of confirmed sources, half-right sources, and outright inventions.

**What to verify:**
- Does the author exist?
- Does the title exist in that exact form?
- Does the journal, press, or book series match?
- Does the year line up?
- Does the source actually address the topic claimed in the annotation?

## The Prompt

{% capture citation_prompt %}
Give me a reading list of 8 to 10 important scholarly works on [topic]. Include author, full title, journal or publisher, year, and a one-sentence note about why each source matters.
{% endcapture %}

{% include typography/callout.html type="prompt" title="Prompt" text=citation_prompt %}

## Why It Works

Talk about "hallucination" stays abstract. This task has a clear answer: the source exists or it doesn't, and the metadata is right or it isn't. That makes it a strong early-semester exercise for any class headed toward research papers, annotated bibliographies, or historiographic review.

It isn't a gotcha about AI. AI's fluent mistakes make source evaluation concrete and show it as part of expert work. Once students start finding errors, the conversation moves from "AI makes mistakes" to a better question: why are we so easily persuaded by the look of correctness? That opens onto how LLMs work, why they confabulate, and what particular errors might reveal about their training data.

## Another Push

AI tools are getting better at avoiding fabrications when explicitly asked to verify sources. That sets up a second round: ask the tool to explain **precisely** where its citations came from.

{% capture citation_prompt2 %}
Verify each citation for accuracy and tell me precisely how you verified or generated these citations.
{% endcapture %}

{% include typography/callout.html type="prompt" title="A follow-up prompt" text=citation_prompt2 %}

Students can watch the model stitch nearby authors, titles, and publication habits into something that feels plausible but has no source behind it.

## What to Watch For

{% include typography/callout.html type="warning" text="Try a sample bibliography or two before class. AI tools change quickly, some topics are less error-prone than others, and vaguer prompts get looser bibliographies." %}

Frame the lesson carefully. It isn't "AI is bad because it makes mistakes." It's how LLMs work, how prompting changes precision, and why verification is the habit that defines expertise.
