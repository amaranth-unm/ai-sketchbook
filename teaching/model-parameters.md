---
layout: sketchbook
title: What Does Cilantro Taste Like?
description: "Students compare how small and large language models answer the same question, then experiment with model settings to see how parameters shape output."
summary: "A hands-on demo to show how model size and settings change what AI says — using one simple, relatable question."
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
key-question: "How to introduce students to the basics of AI output differences?"
what-students-learn:
  - AI is a spectrum of models, not one fixed thing
  - how temperature, token limits, and sampling shape output
  - what training data has to do with what a model knows

card_order: 5
---

# What Does Cilantro Taste Like?

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Open the [Allen AI Playground](https://playground.allenai.org/), pick the smallest model, and ask one question: *What does cilantro taste like?* Then pick the largest model and ask again. The gap between those two answers is a 20-minute lesson in how language models work.

{% include typography/pullquote.html text="'AI' isn't one thing. It's a spectrum of models, and the same question gets wildly different answers depending on which model, and which settings, you use." %}

## The Setup

Students open [playground.allenai.org](https://playground.allenai.org/) on their own devices, or you run it as a demo on the projector.

**Round 1: small model.**
Pick an older, lower-parameter model from the dropdown and submit the prompt. Small models tend to come back short, repetitive, or circular: cilantro described in terms of cilantro, thin generic sentences, sometimes a loop.

**Round 2: large model.**
Switch to the largest model and submit the same prompt. The difference is usually striking. Larger models describe cilantro's fresh, citrusy, herbal taste, and often mention the genetic variation that makes it taste like soap to roughly 10% of people. That detail is a good marker of depth.

**Round 3: settings.**
With the large model selected, play with the parameters:

- **Temperature.** Turn it up and responses get more varied and unpredictable; turn it down and they get focused and repetitive. Ask: what would "high temperature" writing look like in a student essay?
- **Max tokens.** Cap the length and watch the model stop mid-thought. It's a vivid way to show that answers are generated one token at a time, not retrieved.
- **Top-p.** This controls how the model samples possible next words. Lower values make it conservative; higher values add variety.

## The Prompt

{% include typography/sketch-prompt.html text="What does cilantro taste like?" %}

## Why It Works

Cilantro makes a perfect test question. Students can check the answer against their own taste buds, and the soap detail shows whether a model picked up real knowledge about the world or is producing plausible filler. It also opens a quick conversation about what "training data" means: the model knows cilantro can taste like soap because enough people wrote about it.

The settings round turns abstractions like temperature, tokens, and sampling into something students watch happen. Most arrive thinking AI is one fixed thing; they leave having seen otherwise in under half an hour.

## What to Watch For

{% include typography/callout.html type="warning" text="The models on the Allen AI Playground change over time. The contrast between small and large is the point, not any particular result. If the lineup or interface changes, just find the smallest and largest options." %}

It works best when students generate their own responses, so the class can see the variation. Even the same prompt to the same model gives slightly different output each time, which is worth a moment of discussion: everyone talks about "AI output" as one thing, and students benefit from seeing how much variety hides inside that phrase.
