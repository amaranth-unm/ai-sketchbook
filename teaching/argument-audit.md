---
layout: sketchbook
title: Argument Audit
summary: "Students use AI-generated objections to test whether a thesis is vague, vulnerable, or persuasive."
thumbnail: "images/puzzle-krypt.jpg"
thumbnail-credit: 'Puzzle, photo by Muns (derivative by Schlurcher), 2009. [CC BY-SA 2.0](https://creativecommons.org/licenses/by-sa/2.0/), via Wikimedia Commons.'
date: 2026-04-09
status: rough
type: activity
effort: "~30 min in class"
tools:
  - any AI tools
level: any
author: "Fred Gibbs, History"
tags:
  - writing
  - interpretation
key-question: How can AI help sharpen writing skills instead of replace them?
what-students-learn:
  - the difference between tone and analytical precision
  - what makes an objection substantive vs. generic
  - how vague writing produces vague critique
card_order: 10
---

# Argument Audit

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Most students meet critique at the end, when a draft is nearly done and feedback feels like polish. This exercise pulls it forward. AI supplies a stack of objections on demand, and students have to decide which are noise and which just found a hole in their argument.

{% include typography/pullquote.html text="Vague objections often reveal vague writing. AI isn't a brilliant critic, but it forces students to say exactly what they're claiming." %}

## The Setup

Students bring a working thesis paragraph, an interpretive claim, or a partial draft. They paste it into an AI tool and ask for the three strongest objections it can come up with.

Then they annotate each objection and sort it into one of three piles:

- too generic to matter
- misreads the argument as written
- exposes a real gap, ambiguity, or unsupported leap

**The sorting is the assignment.** Students have to say *why* an objection fails instead of waving off the ones that are hard to answer. They take the third pile into their final revision.

## The Prompt

{% capture audit_prompt %}
Here is my argument: [paste your thesis paragraph or interpretive claim]. Generate the three strongest objections you can imagine to this argument. For each objection, be as specific as possible — refer to the actual claims I'm making, the evidence I'm relying on, or the logical moves I'm asking the reader to accept.
{% endcapture %}

{% include typography/callout.html type="prompt" 
title="Prompt" 
text=audit_prompt 
%}

## Why It Works

An objection only counts if it lands on the claim actually being made. To dismiss one, students have to pin down their scope, evidence, and stakes, which is exactly what revision needs. And AI objections make a useful foil: they sound authoritative while floating free of the text, so students see for themselves that a confident tone isn't the same as a precise point.

## What to Watch For

{% include typography/callout.html type="warning" text="AI's confidence can make thin counterarguments feel weightier than they are." %}

- Students may assume the AI knows better. It sometimes spots readings they missed, but much of what it produces is thin, repetitive, or detached from the text. Model the sorting once so they trust their own judgment.
- The draft has to be specific enough to test. If it's too early or too vague, the objections turn generic fast.

## What I Learned

A few minutes of modeling the sorting up front makes a big difference, especially with students who have never had to explain *why* an objection fails instead of just dismissing it.
