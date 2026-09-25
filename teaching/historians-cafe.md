---
layout: sketchbook
title: Historians' Café
summary: "Students script an argument among three historians from different schools of thought, then judge whether AI captured real methodological differences or just swapped labels."
thumbnail: "images/daumier-politiques-de-cafe.jpg"
thumbnail-credit: 'Honoré Daumier, *Les Politiques de café*, lithograph, 1864 (detail). National Gallery of Art.'
thumbnail-position: "center 30%"
date: 2026-08-21
status: lightly tested
type: assignment
effort: "1–2 hours out of class, plus discussion"
tools:
  - any AI tool
level: any
author: "Fred Gibbs, History"
context: "HIST 1105 Making History (intro survey), UNM"
handout: "https://fredgibbs.net/courses/making-history/historians-cafe"
tags:
  - historical thinking
  - prompting
  - interpretation
key-question: "Can AI represent a school of thought, or only its vocabulary?"
what-students-learn:
  - how methodological assumptions produce different readings of the same evidence
  - what a caricature of an intellectual position looks like next to the real thing
  - that the quality of AI output depends on how well they already understand the material
card_order: 30
---

# Historians' Café

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Three historians sit at a café table arguing about the same question — the fall of Rome, the causes of the Civil War, why nationalism took hold in the nineteenth century — and talk right past each other, because they disagree less about the facts than about what history is for. Students use AI to write that conversation. Then they decide whether AI understands the difference between a Marxist historian and a postcolonial one, or is just swapping labels.

{% include typography/pullquote.html text="The dialogue is not the assignment. The evaluation is. A polished conversation accepted uncritically is worth less than a mediocre one a student can take apart." %}

## The Setup

Four moves, and the first three happen before anyone opens an AI tool.

**Pick a question worth arguing about.** It has to be interpretive, with an answer that depends on what you think matters most about the past. Did Rome fall? What caused the French Revolution? Why did colonialism last as long as it did? Questions with settled answers produce three historians nodding at each other.

**Choose three approaches that would collide.** Marxist or economic structuralist, nationalist, history-from-below, cultural, postcolonial, great-man, environmental. Tie each to a historian the class has read, so the comparison has something to stand on.

**Write the character descriptions by hand.** For each historian: what evidence do they trust, what do they think history is fundamentally for, and what would their core claim about this specific question be? Everything rests on this step. Students who can't answer those questions themselves get mush back, which is a useful discovery, but not one to make at the deadline.

**Then prompt, evaluate, revise.** For the evaluation, students quote one line that represents an approach faithfully and one that reads as caricature, and explain the difference. Revision prompts push the thin characters toward specific evidence: *make her argument specifically about how [mechanism] shaped the conditions that led to [event]*, or *ask me three questions, one at a time, to help me sharpen this historian's core claim.*

Students post the final dialogue and the evaluation, then read two classmates' dialogues and come to class ready to say which historian made the most convincing argument and why.

## The Prompt

{% capture cafe_prompt %}
I'm writing a dialogue between three historians who disagree about [YOUR QUESTION]. Each represents a different historiographical approach. The goal is to show how different methodological assumptions lead to different interpretations of the same evidence. Here are my three characters:

[PASTE YOUR CHARACTER DESCRIPTIONS]

Write a 1000-word conversation in which all three historians debate this question at a café table. Each character should argue from their specific methodological position — not just assert conclusions, but challenge the *assumptions* behind the other characters' arguments. Make them argue, not just take turns speaking.
{% endcapture %}

{% include typography/callout.html type="prompt" title="prompt to give students" text=cafe_prompt %}

## Why It Works

Historiography usually arrives as a list of schools with adjectives attached, and students can recite the list without ever seeing a method work on evidence. Put the schools at one table, make them answer each other, and the question changes from *what does a Marxist historian believe?* to *what would she say next, after what the cultural historian just claimed?*

The evaluation turns AI's signature weakness into course content. AI nails the register of a position and wobbles on its substance: you get a "postcolonial critic" who gestures at silencing without naming what was silenced, or a Marxist who says capitalism is bad. Catching that takes knowing the real thing, so the learning goal and the grading criterion are one and the same. No prompt trick can fake the evaluation.

Prompting also shows up as a knowledge problem, not a technique problem. The students who get good dialogues are the ones who wrote good character descriptions, and by the end they can see the connection.

## What to Grade

The grade rests on the character descriptions and the evaluation, not on how good the dialogue turned out. A polished dialogue accepted uncritically is worth less than a mediocre one with a sharp evaluation.

- **Strong:** character descriptions show real understanding of how the approaches differ (what evidence each historian values and why, not just labels); the evaluation quotes specific lines and explains why each one succeeds or fails as a representation of a real intellectual position; revisions pushed back on what was thin.
- **Middling:** solid descriptions and a mostly specific evaluation, but revisions only touched the thinnest parts.
- **Weak:** characters are labeled rather than understood; the first draft was accepted as is; the evaluation is generic ("it seemed accurate").

## What to Watch For

{% include typography/callout.html type="warning" text="Approve each question before students start. A question with an obvious answer gets three historians who agree, and the whole assignment collapses." %}

- Tell students up front that the dialogue doesn't earn the grade. If they think it does, they'll polish the transcript and skip arguing with it.
- Characters take turns giving speeches instead of arguing. That's what the revision prompts are for; without them, students accept the first draft because it looks finished.
- Evaluations drift toward "it seemed accurate." Requiring one quoted line in each direction, faithful and caricature, keeps the step honest.
- Formatting matters more than it should. A dialogue pasted as one unbroken block is useless for peer reading.
