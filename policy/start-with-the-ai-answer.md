---
layout: sketchbook
title: Start With the AI Answer
author: "Fred Gibbs, History"
summary: "In a fully online course where AI use is invisible anyway, build the main assignments around AI output and grade the critical thinking layered on top, while keeping a few assignments where the thinking has to start with the student."
thumbnail: "images/ics-advertisement-1898.jpg"
thumbnail-credit: "International Correspondence Schools advertisement, *Locomotive Engineering*, 1898. University of Scranton."
date: 2026-09-25
status: rough
type: course design
effort: "whole-course design"
context: "HIST 410 History of Diet and Health (upper-division; remote asynchronous summer course), UNM"
last-run: "Summer 2026"
handout: "https://fredgibbs.net/courses/diet-health-expertise/"
tools:
  - any AI tool
level: any
tags:
  - course design
  - assessment
  - online teaching
key-question: "If you can't see how students work, what if the assignment starts where AI would have?"
what-students-learn:
  - that an AI answer is a starting point to interrogate, not a finished product
  - which kinds of thinking AI can help with and which have to be their own
  - how to check a confident answer against the actual sources
card_order: 50
---

# Start With the AI Answer

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

In a remote, asynchronous course, you never see students work. There's no classroom, no discussion to overhear, no drafts taking shape. If an assignment can be done by pasting the prompt into a chatbot, some students will, and nothing will tell you. So in a compressed summer course on the history of diet and health, I tried starting there. The major assignments hand students the AI answer up front and ask them to do something with it: check it, complicate it, find what it missed. A few assignments go the other way and ask students to start from their own thinking, with AI allowed only for polish afterward.

{% include typography/pullquote.html text="If AI will produce the first draft anyway, make the first draft the assignment's raw material, and grade what students do with it." %}

I'm not sure the assignments are great yet. But the approach, meeting AI at the start instead of trying to keep it out, seemed worth recording.

## The Setup

Each assignment names its own relationship to AI. The course leans AI-first, with a few deliberate exceptions.

**Start with AI output, then think on top of it:**

- **[AI Reading Investigation](../teaching/ai-reading-investigation.md):** a prompt sequence on a dense scholarly article, ending with what students verified and what they had to correct.
- **[AI as Second Opinion](../teaching/ai-as-second-opinion.md):** twice, students sample old diet books, get AI's overview, and go back to the originals to see where it holds up.
- **[Narrate the Slides](../teaching/narrate-the-slides.md):** AI captions an unnarrated deck of historical images; students find what the captions skipped.
- **A long secondary article on low-fat diets:** skim it with AI as much as you like, "iteratively and critically, not just lazily," then explain its history using the course.
- **[Complicate the Obvious](../teaching/complicate-the-obvious.md):** the end-of-term essay. Ask AI what a healthy diet is, then use the whole course to explain why that answer is historical.

**Start with your own thinking:**

- **Reading reflections:** students draft their own reactions. AI can polish grammar, or suggest what else to consider *after* they have their own ideas.
- **Final reflection:** no AI drafting at all, because AI can't fake the student's experience of the course. AI can smooth the writing once the student has an outline or draft.

## Policy Language

{% capture online_policy %}
Learning to use AI is an important skill in itself, but using it when you're supposed to be working through the friction of thinking on your own is like bringing a forklift into the weight room.

Each assignment specifies the level and type of AI use that's appropriate. Sometimes that's not using it at all; sometimes the whole assignment is AI-driven. Please respect the intended AI component of each assignment, and clearly separate your work from AI's work as asked.

One rule applies to every assignment: you must always differentiate your work from AI. If it even *seems* like vanilla AI (even if it isn't), you will need to redo the assignment for credit.
{% endcapture %}

{% include typography/callout.html type="prompt" title="From the course syllabus" text=online_policy %}

## Why It Works

It meets students where they already are. Online students will use AI; the only question is whether the assignment acknowledges it. Starting with AI output removes the temptation to pass it off as their own, because the output is already on the table. What earns credit is the layer on top: checking claims against the reading, spotting what the answer flattened, bringing course material to bear on it.

The critical thinking still happens, even if students aren't writing everything out themselves. Many of the assignments ask for specific moves (one claim verified, one corrected, one passage understood better, one place the original complicated the AI) that are hard to do without engaging with the sources.

The no-AI assignments keep the other half of the skill alive. Reflections are where students practice turning reading into their own interpretation, and the final reflection asks about an experience only they had. Putting both kinds side by side shows students that AI's role depends on what an assignment is for.

## What to Watch For

{% include typography/callout.html type="warning" text="AI can do the critique layer too. A student can ask AI to find the flaws in AI's answer and paste the result. The strongest defense is requiring specifics from the actual sources (quoted passages, page-level details, course readings by name), which a generic critique can't supply." %}

- The line between "polish" and "draft" in the no-AI assignments is hard to see from outside. The differentiate-yourself rule is what makes it enforceable.
- Asynchronous students can't ask a quick clarifying question mid-task, so each assignment has to state its AI role plainly and early. A short walk-through video can carry the trickier ones; I made one on how to sample an old book.
- AI answers change over the course of a term. Build that into the assignments instead of fighting it: variation across a class is evidence, too.

## What I'm Still Unsure About

Whether the critique students wrote was really theirs, and how I'd know. Whether starting with AI output anchors students to its framing more than it frees them from it. And whether the balance was right: an online course may need more no-AI practice early on, before students are asked to critique AI's version of a reading they haven't wrestled with themselves.
