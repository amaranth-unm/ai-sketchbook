---
layout: sketchbook
title: Design the AI Assignment
summary: "Students design an AI-assisted exercise on a difficult concept, then observe a classmate trying it."
thumbnail: "images/johnston-classroom-1899.jpg"
thumbnail-credit: "Frances Benjamin Johnston, classroom with students and teacher, Washington, D.C., 1899. Library of Congress."
date: 2026-09-25
status: lightly tested
type: assignment
effort: "out-of-class design, plus one class session of peer testing"
tools:
  - any AI tool
level: any
author: "Fred Gibbs, History"
context: "HIST 300 Critical Thinking with AI (upper-division), UNM"
last-run: "Spring 2026"
handout: "https://fredgibbs.net/courses/critical-thinking-with-ai/ai-assignment"
tags:
  - prompting
  - course design
key-question: "What does an assignment look like that uses AI to learn, not just to get an answer?"
what-students-learn:
  - "turn a broad learning goal into a task someone can attempt"
  - "write and test instructions for another learner"
  - "decide what evidence would show progress in understanding"
card_order: 70
---

# Design the AI Assignment

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Each student chooses something they struggled to understand in another class and designs an AI-assisted exercise to help a classmate learn it. The classmate then tries the exercise while the designer watches. The test is useful partly because instructions that seem obvious to their author may make much less sense to someone following them.

The assignment adapts Ethan Mollick and Lilach Mollick's [“Assigning AI: Seven Approaches for Students, with Prompts”](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4475995) (2023). Here, students choose what role AI should play and take responsibility for designing the activity.

## Preparation and submission

Students need a difficult concept they can check against a course text, worked solution, or other reliable reference. Struggling with it identifies a problem to teach; it doesn't guarantee that their explanation is correct. Check the concepts and arrange peer pairings before class.

The submission consists of the exercise and separate reflection. **Suggested addition:** include the tester's notes and one proposed revision so the designer can distinguish what the peer test showed from what they hoped it would show.

## Designing the exercise

Begin by reading approaches to AI-assisted learning, such as the Mollicks' examples. Ask students to consider what each asks the learner to do and how an instructor could tell whether it helped.

Students then pick a difficult concept from another course: a statistical idea, a chemistry procedure, or an argument in a dense reading. They design an exercise with four parts:

1. A specific learning goal and a reason for learning it.
2. Instructions for using AI, including sample prompts and opportunities to follow up when an explanation doesn't help.
3. Work the learner produces along the way.
4. A task that shows what the learner can now explain or do.

The fourth part needs particular attention. “Understand standard deviation” doesn't tell a tester what to submit. Explaining an example, applying the concept to a new case, or identifying an error gives the designer something to assess.

Students also write a separate reflection of about 250 words on their design: which prompts helped, where AI explanations fell short, and what remains uncertain.

## The assignment prompt

{% capture design_prompt %}
You are a teacher trying to help students learn with AI. Pick a concept or skill you struggled to understand in another class. Design a short exercise that uses AI to help a classmate actually learn it — not just get an answer. Explain what they should learn and why, how they should use AI (with sample prompts), what they should produce, and how they (and you) will know that they understood it.
{% endcapture %}

{% include typography/callout.html type="prompt" title="assignment prompt" text=design_prompt %}

## Making the learning task testable

**Constructed example — not a student design.** “Ask AI to explain standard deviation, then summarize it” mainly tests whether the learner can repeat an explanation.

A stronger exercise asks the learner to compare two small datasets with the same mean but different spread, predict which has the larger standard deviation, and justify that prediction before requesting AI feedback. A new pair of datasets tests whether they can apply the distinction. The designer checks the examples against a trusted worked solution; the tester's explanation supplies evidence of understanding beyond agreement with AI.

## Testing it with a classmate

Students post the exercises before class, then trade and try them. Testers record where they got confused, which AI responses helped, and what they could do by the end. Ask them to report on their own attempt before evaluating the design in general.

The class discussion compares the learning tasks. Did the exercise ask the tester to use an explanation, or mostly to read and repeat it? What evidence would justify the designer's claim that someone learned something?

## What to grade

Grade the design and reflection, with attention to:

- a clear, worthwhile learning goal;
- instructions someone else can follow;
- a reason for the chosen use of AI;
- an activity that lets the learner demonstrate understanding;
- specific reflection on prompts, responses, and revisions.

A tester's difficulty is useful information for the designer. It needn't mean the assignment deserves a poor grade. What matters is whether the design gave them a reasonable task and whether its author can explain what needs changing.

## Before the peer test

Check that topics were difficult for the designers themselves and that the exercises ask for more than an AI explanation followed by a summary. Make sure every tester has an assignment to try; a missing post otherwise costs someone else their class time.
