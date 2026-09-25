---
layout: sketchbook
title: AI Reading Investigation
summary: "Students work through a dense scholarly article with a structured prompt sequence, then report what AI helped them see, what they verified, and what they had to correct."
thumbnail: "images/rembrandt-scholar-at-his-study.jpg"
thumbnail-credit: "Rembrandt, *A Scholar Seated at a Desk*, 1634. National Gallery Prague."
date: 2026-09-25
status: tested
type: assignment
effort: "~400-word post after reading with AI"
tools:
  - any AI tool
level: any
author: "Fred Gibbs, History"
context: "HIST 410 History of Diet and Health (upper-division; remote asynchronous summer course), UNM"
last-run: "Summer 2026"
handout: "https://fredgibbs.net/courses/diet-health-expertise/ai-reading-investigation"
tags:
  - interpretation
  - source evaluation
  - prompting
  - online teaching
key-question: "How can AI make a difficult reading more investigable without doing the reading for you?"
what-students-learn:
  - that a generic summary is the least useful thing AI can do with a reading
  - how to use AI to generate questions and interpretations, then test them against the text
  - where AI flattens the texture of a scholarly argument
card_order: 80
---

# AI Reading Investigation

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Some readings are hard because they're long, dense, or packed with unfamiliar context, and students will reach for AI whether you invite them to or not. So invite them, and shape what happens next. Instead of asking for a summary, students work through a sequence of prompts that treats AI as a smart but unreliable study partner. It helps them get oriented, name the argument, find the passages worth rereading, and try out interpretations. Then they go back to the article and check.

{% include typography/pullquote.html text="Ask a question, get a possible answer, go back to the text, check the evidence, revise your understanding. The back-and-forth between AI and article is the work." %}

{% include typography/callout.html type="note" title="Part of a course" text="One of several AI-first assignments in a remote, asynchronous course. [Start With the AI Answer](../policy/start-with-the-ai-answer.md) explains how they fit together, alongside the assignments that ask for no AI." %}

## The Setup

Pick an article with a clear question that is longer or denser than it needs to be, the kind students skim and misremember. Frame one or two central questions the reading answers. In the version I ran, the article was Steven Shapin's "Trusting George Cheyne," and the question was simple: why did people trust this person, and what does that reveal about how expertise worked?

**Before opening AI**, students jot down two or three quick notes: what they think the article is doing, and what seems confusing.

**Then the prompt sequence**, which students can adapt as they go. Each prompt does a different job:

1. **Get oriented** — the question, the argument, how the author uses evidence. Explicitly *not* a flat summary of topics.
2. **Map the central problem** — a table of the factors the author identifies (in my case, sources of Cheyne's credibility), what evidence in the article supports each, and what the model is uncertain about.
3. **Clarify key concepts** — plain definitions of the article's key terms, why they mattered in context, and a question to ask on returning to the text.
4. **Find evidence** — a checklist of passages to reread and what to look for in each. A reading guide, not a summary.
5. **Test interpretations** — three possible readings, what supports and complicates each, and which is most interesting.
6. **Connect to course themes** — specific, non-obvious claims a student could make in discussion.
7. **Sharpen your own angle** — the student pastes their own rough idea, and AI suggests ways to sharpen or complicate it, without writing it. For each suggestion, what would need verifying in the article?

**The post** (~400 words, written by the student) is organized around five points: one useful AI insight, one AI claim they verified in the article, one AI claim that was vague, wrong, or needed correction, one passage they understand better because of the exchange, and their own answer to the central question.

## The Prompt

The first prompt sets the tone for the sequence. Adapt the article, the course, and the emphasis:

{% capture reading_prompt %}
I am reading [author, title] for a course on [subject]. Give me a concise orientation to the article: what question is the author asking, what is the main argument, how is evidence used, and what historical problem is the author trying to solve? Do not provide a flat, high-level summary of topics. Focus on the argument and evidence.
{% endcapture %}

{% include typography/callout.html type="prompt" title="first prompt in the sequence" text=reading_prompt %}

{% capture reading_prompt7 %}
I need to write my own reading reflection. Here is my current possible angle: [paste your own rough idea]. Based on our discussion, give me a few ways I might sharpen or complicate it. Do not write the reflection for me. For each suggestion, tell me what evidence from the article I would need to verify before using it.
{% endcapture %}

{% include typography/callout.html type="prompt" title="last prompt in the sequence" text=reading_prompt7 %}

## Why It Works

The sequence models a better habit than the one students arrive with. Their default, "summarize this," flattens the article and gives them no reason to open it. Every prompt here points back into the text (a passage to reread, a claim to check, a piece of evidence to find), so the AI conversation becomes a trail of leads instead of a substitute.

The post makes verification the deliverable. Students name one claim they confirmed and one they had to correct, so they can't finish without going back to the article. Hunting for a vague or wrong claim teaches them what AI smooths out: tone, hedging, the texture of the evidence.

The last prompt flips the usual roles. The student brings the idea and AI plays critic, which keeps the reflection theirs while still putting AI to work at the writing stage.

## What to Grade

The grade rests on the movement between AI and the article: what the student checked, corrected, and understood better.

- **Strong:** careful engagement with the article, thoughtful use of AI, specific passages cited, and a clear answer to the central question.
- **Middling:** uses AI productively and refers to the article, but could be more specific, better verified, or more clearly connected to course themes.
- **Weak:** leans on AI summary, gives little evidence from the article, or doesn't explain what the student verified for themselves.

## What to Watch For

{% include typography/callout.html type="warning" text="Try the sequence yourself on the article first. Some articles are well represented in training data and some aren't, and whether students upload the PDF changes the answers considerably. Knowing what AI tends to get wrong about this particular reading helps you steer the discussion." %}

- Students skip the notes-before-AI step, which is what lets them notice how the AI changed their reading. Ask for those notes in the post.
- Posts drift into summary of the AI conversation. The five required points exist to prevent that; grade against them.
- The "claim I had to correct" can be manufactured: a trivial quibble offered to satisfy the requirement. Reward the students who explain *why* the AI version was too generic, not just that it was.
- The sequence is long. For a shorter version, orientation, evidence-finding, and interpretation-testing (prompts 1, 4, and 5) do most of the work.
