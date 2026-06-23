---
layout: sketchbook
title: Citation Test
summary: "Ask students to verify AI-generated citations so fabricated sources become a concrete lesson about evidence, authority, citation accuracy, and why LLMs can produce sources that sound real but do not exist."
thumbnail: "images/Glen_Beck_and_Betty_Snyder_program_the_ENIAC_in_building_328_at_the_Ballistic_Research_Laboratory.jpg"
date: 2026-03-28
status: refined
type: activity
effort: "30–40 min in class"
tools:
  - ChatGPT
  - Claude
level: any
tags:
  - source evaluation
  - source fabrication
  - library instruction
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

Ask AI for a reading list on a focused scholarly topic. Then start verifying citations together as a class. Some will be real. Some will be distorted. Some will be entirely fabricated while sounding perfectly plausible.

{% include typography/pullquote.html text="Fluent prose and bibliographic formatting do not guarantee the existence of a source — and recognizing that makes verification feel less like a library ritual and more like an intellectual necessity." %}

## The Setup

Choose a topic narrow enough to sound scholarly but broad enough that students will not already know the literature by heart. Ask AI for eight to ten key books and articles. Then have students track each citation across library catalogs, publisher pages, journal databases, and Google Scholar.

The exercise is not trying to turn library instruction into a gotcha moment about AI; it uses AI's fluent mistakes to make source evaluation feel concrete, consequential, and part of expert work. It also opens a conversation about how AI works, why confabulation happens, and what particular errors might reveal about training data.

Works individually and as a group exercise where each team verifies two or three citations and reports back. The room usually ends up with a mix of confirmed sources, half-right sources, and fully invented ones. 

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

Unlike more abstract conversations about hallucination, this exercise gives students a task with a clear answer. Either the source exists or it does not. Either the metadata is right or it is not. That clarity makes it a strong early-semester exercise in classes that involve research papers, annotated bibliographies, or historiographic review.

Once students start finding errors, the conversation usually shifts from "AI makes mistakes" to the more useful question: why are we so easily persuaded by the look and tone of correctness?


## Another push
AI tools are getting better at avoiding fabrications when they are explicitly asked to verify sources. That creates another useful teaching moment: ask the tool to explain **precisely** where its citations came from.

{% capture citation_prompt2 %}
Verify each citation for accuracy and tell me precisely how you verified or generated these citations.
{% endcapture %}

{% include typography/callout.html type="prompt" title="A follow-up prompt" text=citation_prompt2 %}

Students can then see how the model stitches together nearby ideas, titles, authors, and publication habits into something that feels plausible but has no real source behind it.


## What to Watch For
{% include typography/callout.html type="warning" text="Test out a sample bibliography or two before class. AI tools change quickly, and some topics and sources are less error-prone than others. Vaguer prompts tend to get looser bibliographies." %}

Frame it carefully: the lesson is not simply "AI is bad because it makes mistakes." The lesson is to think about the nature of LLMs, how prompting can get different levels of precision, and that verification is a crucial scholarly habit that defines expertise.
