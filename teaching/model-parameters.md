---
layout: sketchbook
title: What Does Cilantro Taste Like?
description: "Students compare how small and large language models answer the same question, then experiment with model settings to see how parameters shape output."
summary: "A hands-on demo using AI Playground to show how model size and settings change what AI says — using one simple, relatable question."
thumbnail: "images/960px-_Coriander_.jpg"
date: 2026-03-01
status: rough
type: activity
effort: "20–30 min in class"
tools:
  - Allen AI Playground
level: any
tags:
  - model comparison
  - parameters
  - AI literacy
key-question: "How to introduce students to the basics of AI output differences?"
what-students-learn:
  - AI is a spectrum of models, not one fixed thing
  - how temperature, token limits, and sampling shape output
  - what training data has to do with what a model knows

card_order: 5
---

# What Does Cilantro Taste Like?

<span class="section-accent teach"></span>

{% include typography/sketch-info.html %}

Go to [Allen AI Playground](https://playground.allenai.org/), pick the smallest available model, and ask it one question: *What does cilantro taste like?* Then pick the largest model and ask the same question. The difference between those two answers is a 20-minute lesson in how language models actually work.

{% include typography/pullquote.html text="'AI' is not one thing. It's a spectrum of models, and the same question gets dramatically different answers depending on which model — and which settings — you use." %}

## The Setup

Have students open [playground.allenai.org](https://playground.allenai.org/) on their own devices, or run it as a class demo on a projector.

**Round 1 — small model:**
Select an older, lower-parameter model from the dropdown. Submit the prompt. Note what comes back: responses from small models tend to be short, repetitive, or circular — describing cilantro in terms of cilantro, producing thin or generic sentences, sometimes looping.

**Round 2 — large model:**
Switch to the largest available model and submit the same prompt. The difference is usually striking. Larger models typically describe cilantro's fresh, citrusy, herbal quality — and often mention the well-known genetic variation that makes it taste like soap to roughly 10% of people. That detail is a good marker of genuine knowledge depth.

**Round 3 — model settings:**
With the large model selected, experiment with the available parameters:

- **Temperature** — turn it up and the responses become more varied and unpredictable; turn it down and they become more focused and repetitive. Ask: what would "high temperature" writing look like in a student essay?
- **Max tokens** — cap the response length and watch the model cut off mid-thought. Useful for showing that responses aren't retrieved — they're generated one token at a time.
- **Top-p** — adjusts how the model samples from possible next words. Lower values make responses more conservative; higher values introduce more variety.

## The Prompt

{::nomarkdown}
<div class="sketch-prompt">
  <span class="sketch-prompt-label">prompt</span>
  What does cilantro taste like?
</div>
{:/nomarkdown}

## Why It Works

Cilantro is an ideal demo question because it has a concrete, sensory answer students can verify from their own experience — and because the soap-taste detail is a meaningful test of whether a model has encountered real knowledge about the world, or just plausible-sounding filler. The genetic variation angle also opens a brief but productive conversation about what "training data" actually means: the model knows about cilantro-as-soap because enough people wrote about it.

The parameter demo grounds abstract concepts — temperature, tokens, sampling — in something students can observe in real time rather than read about in a textbook. Most students arrive thinking AI is a single, fixed thing. This activity gives them a concrete counter-example in under 30 minutes.

## What to Watch For

{% include typography/callout.html type="warning" text="The specific models available on the Allen AI Playground change over time — the contrast between small and large models is the point, not any particular model name. If the playground changes its interface or model lineup, the activity still works; just find the smallest and largest options available." %}

The activity works best when students generate responses on their own devices so they can see variation across the class — even the same prompt to the same model will produce slightly different output each time, which is itself worth discussing.
