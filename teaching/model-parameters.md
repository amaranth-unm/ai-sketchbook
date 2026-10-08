---
layout: sketchbook
title: What Does Cilantro Taste Like?
description: "Students compare how small and large language models answer the same question, then experiment with model settings to see how parameters shape output."
summary: "Compare answers to a question about cilantro, then change model settings and examine the differences."
thumbnail: "images/coriander-bunches.jpg"
thumbnail-credit: 'Bunches of coriander. Photo by Kpsudeep, 2020. [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), via Wikimedia Commons.'
date: 2026-03-01
status: lightly tested
type: activity
effort: "20 min in class"
tools:
  - Allen AI Playground
level: any
author: "Fred Gibbs, History"
context: "HIST 300 Critical Thinking with AI (upper-division), UNM"
last-run: "Spring 2026"
handout: "https://fredgibbs.net/courses/critical-thinking-with-ai/schedule#11-introduction-and-orientations"
tags:
  - AI literacy
  - prompting
key-question: "How do different models and settings change an answer to the same question?"
what-students-learn:
  - "compare specific features of model responses"
  - "change one setting at a time and describe its effect"
  - "distinguish differences between models from differences between settings"

card_order: 5
---

# What Does Cilantro Taste Like?

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

What does cilantro taste like? It's a question students can answer for themselves, and a useful one to put to several language models. In this activity, they compare answers in the Allen AI Playground, then change the settings and see what happens to the responses.

## Preparation and submission

No technical background is required. Check the playground before class and prepare saved answers if the relevant controls are unavailable. Choose two named models and record their visible settings; their parameter counts need not be the only difference.

**Suggested submission:** a small comparison table recording model, changed setting, response, and one observation. Distinguish a truncated answer from an inaccurate one, and repeat a setting before treating one answer as typical.

## Three rounds

Students open [playground.allenai.org](https://playground.allenai.org/) on their devices, or you run the comparison on a projector.

**First, try a small model.** Choose an older, lower-parameter model and submit the question. Look for circular descriptions, repetition, and details that say little about the taste. Save the answer for comparison.

**Then try a larger model.** Submit the same question. Larger models may offer a fuller description: citrus, herbs, or the soapy taste some people experience. Ask students which details are useful and which they would want to check. Mentioning the soap connection is a difference worth discussing, but it doesn't by itself demonstrate how well a model understands the subject.

**Finally, change the settings.** Use the same model and prompt for this round, changing one setting at a time:

- **Temperature:** compare the variation and repetition in responses at lower and higher settings.
- **Max tokens:** limit the output and watch where the answer stops. Does it finish its thought?
- **Top-p:** change the range of possible next tokens the model samples from and compare the wording.

## The Prompt

{% include typography/sketch-prompt.html text="What does cilantro taste like?" %}

## Comparing what actually changed

**Constructed example — invented outputs, not a playground result.** With one model and unchanged sampling settings, a short output limit yields “Cilantro tastes fresh and”; a longer limit allows the sentence to finish. This supports an observation about truncation. It doesn't show that the longer answer is more knowledgeable.

If a second model mentions a soapy taste, students can record that added detail. They cannot attribute it solely to size when training and other settings also differ.

## Discussing the differences

Ask students to point to a specific difference between two answers and identify what changed between the runs. Model size, training, and settings are different things; comparing two models doesn't isolate just one of them. The settings round gives the class a more controlled comparison.

It also helps to compare responses across students. Even when they use the same model and question, the answers may vary. That gives the class something more precise to discuss than whether “AI” gives a good answer.

## Before class

Check which models and settings the playground currently offers, and run the comparison once yourself. The available models change, so the examples above may not be the ones your class sees. If two answers are similar, keep that result in the discussion rather than treating the contrast as guaranteed.
