---
layout: sketchbook
title: Historians' Café
summary: "Students script an argument among three historians from different schools of thought, then judge whether AI captured real methodological differences or just swapped labels."
thumbnail: "images/daumier-politiques-de-cafe.jpg"
date: 2026-08-21
status: lightly tested
type: assignment
effort: "1–2 hours out of class, plus discussion"
tools:
  - any AI tool
level: any
tags:
  - historiography
  - prompting
  - history
  - interpretation
key-question: "Can AI represent a school of thought, or only its vocabulary?"
what-students-learn:
  - how methodological assumptions produce different readings of the same evidence
  - what a caricature of an intellectual position looks like next to the real thing
  - that the quality of AI output depends on how well they already understand the material
skills:
  - distinguishing methodology from conclusion
  - evaluating AI output against course readings
  - specifying a position precisely enough to prompt for it
card_order: 30
---

# Historians' Café

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Three historians sit at a café table arguing about the same question — the fall of Rome, the causes of the Civil War, why nationalism took hold in the nineteenth century — and talk past each other, because they disagree less about the facts than about what history is for. Students use AI to write that conversation. Then they decide whether AI actually understands the difference between a Marxist historian and a postcolonial one, or whether it is just producing labels.

{% include typography/pullquote.html text="The dialogue is not the assignment. The evaluation is. A polished conversation accepted uncritically is worth less than a mediocre one a student can take apart." %}

## The Setup

Students work through it in four moves, and the first one happens before they open an AI tool.

**Pick a question worth arguing about.** It has to be interpretive — one where the answer depends on what you think matters most about the past. Did Rome fall? What caused the French Revolution? Why did colonialism last as long as it did? Questions with settled answers produce three historians nodding at each other.

**Choose three approaches that would genuinely collide.** Marxist or economic structuralist, nationalist, history-from-below, cultural, postcolonial, great-man, environmental. Tie each to a historian the class has actually read, so the comparison has something to stand on.

**Write the character descriptions by hand.** For each historian: what evidence do they trust, what do they think history is fundamentally for, and what would their core claim about this specific question be? This is the load-bearing step. Students who cannot answer those three questions themselves get mush back, which is a useful thing for them to discover but a bad thing to discover at the deadline.

**Then prompt, evaluate, revise.** The evaluation asks students to quote one line that reads as a genuine representation of an approach and one that reads as a caricature, and to explain the difference. Revision prompts push the thin characters toward specific evidence: *make her argument specifically about how [mechanism] shaped the conditions that led to [event]*, or *ask me three questions, one at a time, to help me sharpen what this historian's core claim would actually be.*

Students post the final dialogue and the evaluation, then read two classmates' dialogues and come to class ready to say which historian made the most convincing argument and why.

## The Prompt

{% capture cafe_prompt %}
I'm writing a dialogue between three historians who disagree about [YOUR QUESTION]. Each represents a different historiographical approach. The goal is to show how different methodological assumptions lead to different interpretations of the same evidence. Here are my three characters:

[PASTE YOUR CHARACTER DESCRIPTIONS]

Write a 1000-word conversation in which all three historians debate this question at a café table. Each character should argue from their specific methodological position — not just assert conclusions, but challenge the *assumptions* behind the other characters' arguments. Make them argue, not just take turns speaking.
{% endcapture %}

{% include typography/callout.html type="prompt" title="prompt to give students" text=cafe_prompt %}

## Why It Works

Historiography is usually taught as a list of schools with adjectives attached, and students can reproduce that list without ever seeing how a methodological commitment does work on evidence. Staging the schools as people who have to answer each other forces the question of mechanism: not *what does a Marxist historian believe* but *what would she say next, given what the cultural historian just claimed*.

The evaluation step turns AI's characteristic failure into the content of the assignment. AI is good at the register of a position and unreliable about its substance — it will give you a "postcolonial critic" who gestures at silencing without ever naming what was silenced, or a Marxist who says capitalism is bad. Spotting that requires knowing the real thing, which means the grading criterion and the learning goal are the same criterion. Students cannot fake the evaluation with a better prompt.

It also makes prompting legible as a knowledge problem rather than a technique problem. The students who get good dialogues are the ones who wrote good character descriptions, and that connection is obvious to them by the end.

## What to Watch For

{% include typography/callout.html type="warning" text="Grade the evaluation and the character descriptions, not the dialogue. If students sense the dialogue is what earns the grade, they will optimize for a polished transcript and skip the part where they argue with it." %}

- Students pick a question with an obvious answer and get three historians who agree. Approving the question before they start avoids the whole assignment collapsing.
- Characters take turns delivering position statements instead of arguing. The revision prompts exist for exactly this; without them, students often accept the first draft because it looks finished.
- Evaluations drift toward "it seemed accurate." Requiring a quoted line in each direction — one genuine, one caricature — is what keeps the step from becoming a formality.
- Formatting matters more than it should here. A dialogue pasted as one unbroken block is unreadable and unusable for the peer-reading step.
