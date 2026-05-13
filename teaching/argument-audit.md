---
layout: sketchbook
title: Argument Audit
activity: "Students use AI-generated objections to test whether a thesis is vague, vulnerable, or genuinely persuasive."
thumbnail: "images/960px-Puzzle_Krypt-2.jpg"
date: 2026-04-09
status: rough
type: activity
effort: "~30 min in class"
tools:
  - any AI tools
level: any
tags:
  - writing
  - argument
key-question: How can AI help sharpen writing skills instead of replace them?
what-students-learn:
  - the difference between tone and analytical precision
  - what makes an objection substantive vs. generic
  - how vague writing produces vague critique
card_order: 10
---

# Argument Audit

<span class="section-accent teach"></span>

{% include typography/sketch-info.html %}

Students often treat critique as something that happens after a draft is mostly finished — a late-stage polish rather than a genuine test of an idea. This exercise moves critique earlier. The AI becomes a machine for producing objections on demand, and the students' job is to decide which ones are generic noise and which ones expose a real weakness in the argument.

{% include typography/pullquote.html text="Vague objections often reveal vague writing. The point is not that AI is a brilliant critic. The point is that it forces students to consider alternate interpretations and clarify what exactly they are claiming." %}

## The Setup
Ask students to bring a working thesis paragraph, interpretive claim, or partial draft. They paste that argument into an AI tool and ask it to produce the three strongest objections it can imagine.

Students then annotate the objections and sort them into three buckets:

- objections that are too generic to matter
- objections that misunderstand the argument as written
- objections that actually expose a gap, ambiguity, or unsupported leap

**The sorting process is the assignment.** It makes students articulate *why* an objection fails instead of deciding to dismiss it because it's hard to work with.

Students carry this work into their final revision, leading to sharper prose and a more defensible claim.


## The Prompt

{% capture audit_prompt %}
Here is my argument: [paste your thesis paragraph or interpretive claim]. Generate the three strongest objections you can imagine to this argument. For each objection, be as specific as possible — refer to the actual claims I'm making, the evidence I'm relying on, or the logical moves I'm asking the reader to accept.
{% endcapture %}

{% include typography/callout.html type="prompt" title="Prompt" text=audit_prompt %}



## Why It Works
A counterargument is only strong if it lands on the actual claim being made. This exercise makes that concrete: defending an argument means specifying scope, evidence, and stakes — not just reasserting it with more confidence. Authoritative tone is not the same thing as analytical precision, and students can see that distinction clearly when working with AI-generated objections that sound reasonable but are detached from the actual text.


## What to Watch For
{% include typography/callout.html type="warning" text="The AI confidence can encourage students to put too much weight on counterarguments" %}

- Students can feel that AI knows more than they  do (which is true in terms of textual awareness), but they can underestimate their own ability to separate the wheat from the chaff. AI tends to generate objections that are thin, repetitive, or detached from the actual text, and students need to be primed to recognize this and categorize accordingly.
- Students already have something specific enough to test. If the draft is too early or too vague, the exercise becomes generic very quickly.

## What I learned
Brief instructor modeling of the sorting process helps orient students before they work independently — especially in classes where students haven't been asked to articulate *why* an objection fails rather than just dismiss it.