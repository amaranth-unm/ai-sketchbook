---
layout: sketchbook
title: Citation Test
activity: "Students verify AI-generated citations one by one and turn fabricated sources into a lesson about evidence and authority."
thumbnail: "/assets/images/headers/Glen_Beck_and_Betty_Snyder_program_the_ENIAC_in_building_328_at_the_Ballistic_Research_Laboratory.jpg"
date: 2026-04-09
status: refined
type: activity
effort: "30–40 min in class"
tools:
  - ChatGPT
  - Claude
level: any
tags:
  - source evaluation
  - fabrication
  - research skills
  - library instruction
key-question: "How can AI output help students learn scholarly integrity?"
what-students-learn:
  - why polished prose is not evidence of accuracy
  - how hallucination happens and why it's convincing
  - verification is a scholarly habit that connects classroom work with library expertise
card_order: 20
---

# Citation Test

<span class="section-accent teach"></span>

{% include typography/sketch-info.html %}

Ask AI for a reading list on a focused scholarly topic. Then verify every citation together as a class. Some will be real. Some will be distorted. Some will be entirely fabricated while sounding perfectly plausible.

{% include typography/pullquote.html text="Fluent prose and bibliographic formatting do not guarantee the existence of a source — and recognizing that makes verification feel less like a library ritual and more like an intellectual necessity." %}

## The Setup

Choose a topic narrow enough to sound scholarly but broad enough that students will not already know the literature by heart. Ask AI for eight to ten key books and articles. Then have students track each citation across library catalogs, publisher pages, journal databases, and Google Scholar.

This is a natural place to partner with a librarian. The exercise is not trying to turn library instruction into a gotcha moment about AI; it uses AI's fluent mistakes to make source evaluation feel concrete, consequential, and shared across the course and the library.

Works individually, but best as a group exercise where each team verifies two or three citations and reports back. The room usually ends up with a mix of confirmed sources, half-right sources, and fully invented ones.

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
You can have students better understand how AI works by asking AI to explain **precisely** where citations come from. 

{% capture citation_prompt2 %}
Tell me precisely how you found or generated these citations.
{% endcapture %}

{% include typography/callout.html type="prompt" title="A follow-up prompt" text=citation_prompt2 %}

Students then get to see some of the origins of intellectual adjacent ideas and publications getting combined that makes perfect sense for the LLM engine, but no basis in reality.


## What to Watch For

{% include typography/callout.html type="warning" text="This works best when students have access to a real library discovery system and at least some guidance on how to search beyond Google. A librarian-led or librarian-supported version would likely be stronger. Without that scaffolding, the exercise can slide into frustration rather than insight." %}

Frame it carefully: the lesson is not simply "AI bad." The lesson is that verification is a scholarly habit, and AI gives us a vivid way to show why that habit matters.
