---
layout: sketchbook
title: Design the AI Assignment
summary: "Students design an AI-assisted learning exercise on a concept they once struggled with, then trade assignments and find out whether someone else actually learns from it."
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
  - the difference between using AI to finish work and using AI to understand something
  - that evidence of learning has to be designed in, not assumed
  - how much a learning process depends on clear goals and iteration
  - how to write instructions clear enough for someone else to follow
card_order: 70
---

# Design the AI Assignment

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Teaching something is the fastest way to find out what you don't understand about it. This assignment puts students in the instructor's seat. Each student picks a concept from another class that they really struggled with (a statistical idea, a chemistry procedure, a dense reading) and designs a short exercise that uses AI to help someone else learn it. Then a classmate tries it in class while the designer watches.

{% include typography/pullquote.html text="Explaining a concept is easy for AI. Designing a process where someone can't skip the understanding is the hard part, and that's the part students have to build." %}

{% include typography/callout.html type="note" title="Inspired by" text="Ethan Mollick and Lilach Mollick, [\"Assigning AI: Seven Approaches for Students, with Prompts\"](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4475995) (2023), which gives instructors seven roles for AI, from tutor and coach to simulator and teammate. **The core change:** students do the assigning. They design the AI exercise themselves, then find out on each other whether it works." %}

## The Setup

**Read the frameworks first.** Before designing anything, students read a few approaches to AI-integrated assignments with a skeptical eye. Mollick and Mollick's "Assigning AI: Seven Approaches for Students" works well. Are the approaches really different, or one idea in seven costumes? Which would produce students who learned something, and which would produce students who know how to look like they did?

**Pick a hard topic.** It has to come from a class the student found difficult. Easy topics make easy assignments, and those teach nothing about how AI helps in a real struggle to learn.

**Design the exercise.** The assignment students write has four parts:

1. A clear statement of what the learner should understand, and why it's worth understanding.
2. Step-by-step instructions for how to use AI: sample prompts, general advice about prompting, and explicit instructions to iterate. Tutor, coach, role-play, practice questions, alternative explanations: whatever fits the concept.
3. What the learner should produce along the way.
4. How the learner shows that real learning happened.

**Build in evidence of learning.** Students find this part hardest, and it matters most. Good designs ask the learner to explain the concept in their own words, apply it to a new example, keep a record of key prompts and false starts, and show how they checked AI's explanations. The underlying test: can the learner now explain, apply, and question the idea better than they could at the start?

**Write a separate reflection.** About 250 words, apart from the assignment itself, on what designing it taught the student about AI and learning. Which kinds of prompts helped? Where did AI explanations fall short?

**Peer test in class.** Students post their assignments before class, then trade and try to learn from someone else's. Testers document what worked, what was confusing, where AI helped, and where it distracted. Each group reports back, and the discussion keeps circling one question: how do you keep the AI from doing the student's thinking?

## The Prompt

Students write the prompts here. What you give them is the design question:

{% capture design_prompt %}
You are a teacher trying to help students learn with AI. Pick a concept or skill you struggled to understand in another class. Design a short exercise that uses AI to help a classmate actually learn it — not just get an answer. Explain what they should learn and why, how they should use AI (with sample prompts), what they should produce, and how they (and you) will know that they understood it.
{% endcapture %}

{% include typography/callout.html type="prompt" title="assignment prompt" text=design_prompt %}

## Why It Works

Students who use AI regularly mostly use it to *finish* things. Designing for someone else drags the difference between finishing and learning into the open: a design that lets the learner paste in the question and copy out the answer falls flat in peer testing, in front of everyone.

Students also see learning goals and assessment from the inside. "Understand the concept" isn't testable until they decide what understanding looks like, and with AI in the picture, the process (prompts, revisions, checks) becomes better evidence than the polished product.

And their own struggle becomes expertise. The student who never quite got standard deviation knows exactly where the confusion lives, which is often more useful for designing a path through it than knowing the concept cold.

## What to Grade

Grade the design, not whether the tester ended up mastering the concept. A checklist gives students the target in advance:

- **A clear learning goal and motivation:** a specific concept or skill, and why it's worth learning.
- **A followable activity:** someone else could work through the instructions and attempt the same learning process.
- **Thoughtful use of AI:** AI supports learning rather than producing answers, and the design shows awareness of AI's strengths and limits.
- **Built-in evidence of learning:** the design asks the learner to show understanding changed — explanation in their own words, a transfer task, a record of the process.

The separate reflection counts too: strong reflections name specific kinds of prompts that helped or failed, rather than general impressions of AI.

## What to Watch For

{% include typography/callout.html type="warning" text="Weak designs are really an explanation with extra steps: ask AI to explain X, then summarize it. Push students toward activities that make the learner do something with the explanation: apply it, test it, catch AI getting it wrong." %}

- Students choose easy topics because they're easier to explain. Insist on something that was truly difficult; the assignment is supposed to be hard to write.
- The evaluation section gets vague ("the student will understand X"). Ask what, specifically, the designer would want to see.
- Peer testing needs the assignments posted before class. A missing assignment leaves a tester with nothing to do.
- Testers sometimes grade the assignment instead of trying to learn from it. Ask them to report on their own learning experience first, and critique the design second.
