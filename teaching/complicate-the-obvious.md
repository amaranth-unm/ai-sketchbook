---
layout: sketchbook
title: Complicate the Obvious
summary: "Students ask AI a question with a boringly familiar answer — what is a healthy diet? — then use the course to explain why that answer is neither timeless nor neutral."
thumbnail: "images/basic-seven-poster.jpg"
thumbnail-credit: '"Eat the Basic Seven Every Day," U.S. government poster, 1941–45. National Archives.'
date: 2026-08-21
status: tested
type: assignment
effort: "600-word essay, end of term"
tools:
  - any AI tool
level: any
author: "Fred Gibbs, History"
context: "HIST 410 History of Diet and Health (upper-division; remote asynchronous summer course), UNM"
last-run: "Summer 2026"
handout: "https://fredgibbs.net/courses/diet-health-expertise/healthy-diet-analysis"
tags:
  - historical thinking
  - expertise
  - prompting
  - online teaching
key-question: "What does a confident, ordinary answer take for granted?"
what-students-learn:
  - that practical advice carries a history and a set of assumptions
  - how authority gets constructed in a voice that sounds neutral
  - what a well-designed follow-up prompt can surface that a first answer hides
card_order: 40
---

# Complicate the Obvious

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Ask AI what a healthy diet is and you get an answer nobody would argue with: balance, vegetables, whole grains, less sugar, plenty of water, check with a professional. The advice may well be good. It is also thoroughly historical, built on particular ideas about bodies, evidence, moderation, responsibility, and who counts as an expert. Students take that unremarkable answer and make it strange, using a semester's worth of history as the solvent.

{% include typography/pullquote.html text="The task isn't to decide whether the advice is right. It's to explain why it sounds the way it does, and to notice what a confident answer makes invisible." %}

{% include typography/callout.html type="note" title="Part of a course" text="One of several AI-first assignments in a remote, asynchronous course. [Start With the AI Answer](../policy/start-with-the-ai-answer.md) explains how they fit together, alongside the assignments that ask for no AI." %}

## The Setup

Run it at the end of the term, so students can bring the whole course to bear on a thoroughly ordinary question.

**Before opening AI**, students jot down three course themes they expect to matter: regimen, moderation, quantification, moral discipline, official guidance, common sense. Writing these first keeps the exercise from turning into a reaction to whatever the model says.

**Two required prompts** set the baseline: the advice, then its justification. The second is where it gets interesting. Asked to defend itself, the model lays out its warrants (evidence, authority, expert consensus) that the practical tone of the first answer kept out of sight.

**Three follow-ups of the students' own** carry the assignment. They can't just ask for more detail; they have to use course material to pressure-test the answer. What would a scholar of nutritional discourse notice? What would a historian of dietary morality ask? Prompts about hidden assumptions, moral framing, measurement and risk, or which people and eating practices count as normal tend to crack the answer open.

**The write-up** runs about 600 words: the AI's answer in brief, the three follow-ups, at least one moment where a follow-up revealed something, several course readings used as interpretive tools, and an argument about what the answer says about modern expertise. Students also comment on the range across classmates' posts, which shows how much the "neutral" answer varies.

## The Prompt

{% capture obvious_prompt %}
What is a healthy diet? Give me practical advice for an ordinary adult.
{% endcapture %}

{% include typography/callout.html type="prompt" title="first required prompt" text=obvious_prompt %}

{% capture obvious_prompt2 %}
Why is this diet healthy? What evidence, assumptions, or expert knowledge supports this advice?
{% endcapture %}

{% include typography/callout.html type="prompt" title="second required prompt" text=obvious_prompt2 %}

Then at least three of their own, designed to reveal what the first answer hid. Good models to show the class: *What assumptions are you making about health, bodies, responsibility, culture, science, and food?* — *What parts of your answer reflect modern American assumptions rather than universal truths?* — *What kinds of foods, people, traditions, bodies, or economic realities are left out?*

## Why It Works

Historical context is easy to demonstrate on obviously strange material like humoral regimens, Victorian temperance diets, or wartime food charts. It's much harder on material that feels like plain fact. AI serves up plain fact on demand, in a voice of calm authority, which is exactly the hard case. Students practice treating today's consensus as a source with a history instead of the yardstick for measuring the past.

The follow-ups double as a check on the semester. A student who absorbed the course can write a prompt that opens up the moral and quantitative assumptions buried in "everything in moderation." A student who didn't asks for more advice. You can see the difference in the transcript.

And it leaves students with a useful way to think about AI: a compact, queryable specimen of contemporary common sense that will happily explain its own reasoning if you ask the right way.

## What to Grade

The grade rests on the historical analysis and the follow-up prompts, not on whether the student judged the AI's advice correct.

- **Strong:** original, specific analysis that uses several course readings to explain why the advice sounds the way it does; follow-ups that clearly surfaced something the first answer hid; close attention to expertise, assumptions, and what gets left out.
- **Middling:** some specific course connections, but the historical perspective, prompt design, or discussion of expertise could go further.
- **Weak:** describes the AI's answer without enough course material, or relies on general claims about diet culture.

## What to Watch For

{% include typography/callout.html type="warning" text="The most common failure is the verdict essay: students grade the advice as accurate or inaccurate and stop there. Say more than once that rightness isn't the question." %}

- Follow-ups drift into requests for elaboration instead of interrogation. Put a few strong and weak examples side by side before students start.
- Students gesture at course themes instead of citing readings. Requiring named sources keeps the essay from becoming a general critique of diet culture, which they could write without the course.
- The AI's answer is a moving target. Models, guardrails, and hedging shift, and answers vary by account and phrasing. Treat that variation as evidence: the spread across a class is itself a finding.
- Pasted transcripts crowd out analysis. Cap the quotation and grade the argument.
