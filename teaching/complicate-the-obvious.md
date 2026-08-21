---
layout: sketchbook
title: Complicate the Obvious
summary: "Students ask AI a question with a boringly familiar answer — what is a healthy diet? — then use the course to explain why that answer is neither timeless nor neutral."
thumbnail: "images/basic-seven-poster.jpg"
date: 2026-08-21
status: tested
type: assignment
effort: "600-word essay, end of term"
tools:
  - any AI tool
level: any
tags:
  - historical thinking
  - expertise
  - prompting
  - history
key-question: "What does a confident, ordinary answer take for granted?"
what-students-learn:
  - that practical advice carries a history and a set of assumptions
  - how authority gets constructed in a voice that sounds neutral
  - what a well-designed follow-up prompt can surface that a first answer hides
skills:
  - historical contextualization of present-day claims
  - reading for what a source omits
  - designing prompts that test rather than retrieve
card_order: 40
---

# Complicate the Obvious

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Ask AI what a healthy diet is and you get an answer nobody would argue with: balance, vegetables, whole grains, less sugar, drink water, ask a professional. The advice may well be good. It is also thoroughly historical — an artifact of particular ideas about bodies, evidence, moderation, responsibility, and who counts as an expert. This assignment asks students to take that unremarkable answer and make it strange, using a semester's worth of history as the solvent.

{% include typography/pullquote.html text="The task is not to decide whether the advice is right. It is to explain why it sounds the way it does — and to notice what a confident answer makes invisible." %}

## The Setup

This runs at the end of the term, which is the whole point: it asks students to bring the entire course to bear on an utterly ordinary present-day question.

**Before opening AI**, students jot down three course themes they expect to matter — regimen, moderation, quantification, moral discipline, official guidance, common sense. Writing these first keeps the exercise from becoming a reaction to whatever the model happens to say.

**Two required prompts** establish the baseline: the advice itself, then the justification behind it. The second prompt is the useful one, because it makes the model expose its warrants — evidence, authority, expert consensus — in a way the first answer conceals under practical tone.

**Three student-designed follow-ups** are where the assignment actually lives. These cannot just ask for more detail; they have to use course material to pressure-test the answer. What would a scholar of nutritional discourse notice here? What would a historian of dietary morality ask? Prompts about assumptions, moral framing, measurement and risk, or what populations and eating practices are treated as normal all tend to open something up.

**The write-up** is about 600 words: a summary of the AI's answer, the three follow-ups, at least one moment where a follow-up revealed something, several specific course examples used as interpretive tools, and an argument about what the answer reveals about modern expertise. Students also comment on the range they see across classmates' posts, which surfaces how much the "neutral" answer varies.

## The Prompt

{% capture obvious_prompt %}
What is a healthy diet? Give me practical advice for an ordinary adult.
{% endcapture %}

{% include typography/callout.html type="prompt" title="first required prompt" text=obvious_prompt %}

{% capture obvious_prompt2 %}
Why is this diet healthy? What evidence, assumptions, or expert knowledge supports this advice?
{% endcapture %}

{% include typography/callout.html type="prompt" title="second required prompt" text=obvious_prompt2 %}

Then at least three of the student's own, designed to reveal what the first answer hid. Models worth showing the class: *What assumptions are you making about health, bodies, responsibility, culture, science, and food?* — *What parts of your answer reflect modern American assumptions rather than universal truths?* — *What kinds of foods, people, traditions, bodies, or economic realities are left out?*

## Why It Works

Historical contextualization is easy to demonstrate on obviously strange material — humoral regimen, Victorian temperance diets, wartime food charts — and much harder on material that feels like plain fact. AI supplies the plain fact on demand, in a register of calm authority, which is exactly the hard case. Students get to practice the move that matters: treating a present-day consensus as a source with a history rather than as the baseline against which history is measured.

The prompt-design requirement does real work here too. A student who has understood the course can write a follow-up that opens up the moral or quantitative assumptions buried in "everything in moderation." A student who has not will write follow-ups that just request more advice. The difference is legible in the transcript, which makes this a fairly honest measure of whether the semester landed.

It also reframes AI usefully at the end of a course: not as an answer machine or a threat, but as a compact, queryable specimen of contemporary common sense — one that will happily explain its own reasoning if asked the right way.

## What to Watch For

{% include typography/callout.html type="warning" text="The most common failure is the verdict essay: students grade the AI's advice as accurate or inaccurate and stop there. Say explicitly, more than once, that rightness is not the question." %}

- Follow-up prompts drift into requests for elaboration rather than interrogation. Modeling two or three strong follow-ups against two or three weak ones takes ten minutes and changes the results substantially.
- Students gesture at course themes rather than citing specific readings. Requiring named sources keeps the analysis from becoming a general critique of diet culture, which they can produce without the course.
- The AI's answer is a moving target — models, guardrails, and hedging conventions shift, and answers vary by account and phrasing. That variation is worth assigning as evidence rather than treating as noise; the spread across a class is itself a finding.
- Pasting the whole transcript substitutes for analysis. Cap the quotation and grade the argument.
