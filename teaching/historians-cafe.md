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
  - "describe how historical approaches differ in evidence and assumptions"
  - "evaluate a generated character against course readings"
  - "revise a representation that reduces an approach to a label"
card_order: 30
---

# Historians' Café

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

What would three historians from different schools of thought argue about over coffee? Students choose a question, define the historians' positions, and ask AI to write their conversation. They then evaluate whether the characters reason from those positions or merely use the expected vocabulary.

## Preparation and submission

Assign readings that represent the chosen approaches before asking students to judge them. Prepare a comparison between a methodological disagreement and a change of vocabulary.

Students submit their question, character descriptions, original dialogue, quoted evaluation with course references, and revised dialogue. **Suggested adaptation:** allow a well-supported evaluation that finds no caricature; students can explain which exchanges they would retain and why.

## Before the prompt

**Choose an interpretive question.** The fall of Rome, the causes of the French Revolution, or the persistence of colonialism can support different arguments. Ask students to explain why their question admits disagreement before they start.

**Choose three approaches.** Marxist, nationalist, history-from-below, cultural, postcolonial, environmental, and great-man approaches are possibilities. Connect each to a historian the class has read so students have something specific against which to judge the result.

**Write the character descriptions by hand.** For each historian, students explain what evidence matters, what they think history should explain, and what claim they would make about this question. These descriptions are part of the submitted work.

## The Prompt

{% capture cafe_prompt %}
I'm writing a dialogue between three historians who disagree about [YOUR QUESTION]. Each represents a different historiographical approach. The goal is to show how different methodological assumptions lead to different interpretations of the same evidence. Here are my three characters:

[PASTE YOUR CHARACTER DESCRIPTIONS]

Write a 1000-word conversation in which all three historians debate this question at a café table. Each character should argue from their specific methodological position — not just assert conclusions, but challenge the *assumptions* behind the other characters' arguments. Make them argue, not just take turns speaking.
{% endcapture %}

{% include typography/callout.html type="prompt" title="prompt to give students" text=cafe_prompt %}

## Evaluating and revising

The original task asks students to quote one line that represents an approach well and one that turns it into a caricature. They explain both judgments with reference to the historians they have read. A character can mention silencing or class conflict without making a convincing historical argument about either.

The next prompt addresses the problem they identified. Students might ask a character to explain how a particular economic change contributed to an event, or ask AI to question them about the character's assumptions before trying again. They retain the evaluation and the revised dialogue.

Before class, students post their work and read two classmates' dialogues. They arrive ready to discuss which arguments they found convincing and what evidence or assumptions made the difference.

## Method or vocabulary?

**Constructed example — invented dialogue about a hypothetical strike.** “As a Marxist, I care about class” names a position without using it. “The wage cut and workers' dependence on the employer help explain why bargaining became a strike” proposes a causal account that needs evidence.

Another character might ask how workers described the dispute themselves and whether that changes the explanation. Students should connect each move to a particular assigned historian. The labels alone cannot establish whether either character represents that historian fairly.

## What to grade

Grade the character descriptions, evaluation, and decisions made during revision. A fluent dialogue isn't enough to show that the student understood its positions.

- **Strong work** explains how the approaches differ, quotes lines from the dialogue, and uses course readings to justify the evaluation. Revisions respond to an identified problem.
- **Work needing development** recognizes differences but explains them loosely, or identifies a weakness without addressing it.
- **Weak work** supplies labels in place of positions and accepts the generated dialogue with a general assurance that it seems accurate.

## What to watch for

Approve the question before students spend time drafting. If their historians all agree, revisit the question and character descriptions.

AI characters often take turns speaking instead of answering each other. Ask students to locate an exchange in which one character has to respond to another's evidence or objection. That is a more useful revision target than a request to make the conversation livelier.

Keep the dialogue formatted for reading. An unbroken block of text makes it difficult for classmates to follow who is arguing what.
