---
layout: sketchbook
title: AI as Second Opinion
summary: "Students form their own first impression of old primary sources, ask AI for its take, then go back to the originals to find where AI's version was right, flattened, or wrong."
thumbnail: "images/peters-diet-and-health-cover.jpg"
thumbnail-credit: "Cover of Lulu Hunt Peters, *Diet and Health, with Key to the Calories*, 1918."
thumbnail-position: "center 16%"
date: 2026-09-25
status: tested
type: assignment
effort: "reading post, run twice with escalating independence"
tools:
  - any AI tool
level: any
author: "Fred Gibbs, History"
context: "HIST 410 History of Diet and Health (upper-division; remote asynchronous summer course), UNM"
last-run: "Summer 2026"
handout: "https://fredgibbs.net/courses/diet-health-expertise/schedule#wed-78-natural-and-moral-diets-of-the-1800s"
tags:
  - source evaluation
  - interpretation
  - historical thinking
  - online teaching
key-question: "What does AI see in a primary source, and what does it smooth over?"
what-students-learn:
  - that tone, voice, audience, and style carry much of a primary source's meaning
  - that AI is good at the gist of a text and weak on its texture
  - that a first impression of their own is worth having before asking anyone else
  - how to sample a long historical text without reading all of it
card_order: 100
---

# AI as Second Opinion

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Old books are hard to read cover to cover and easy to ask AI about. This assignment uses both facts. Students sample a small set of primary sources (in my case, nineteenth- and early twentieth-century diet books) and form their own first impression. Then they ask AI for its overview, treat it as a rough second opinion, and go back to the originals to see where it holds up. They write a comparison of the texts, but the real discovery is the gap between what AI noticed and what they saw for themselves.

{% include typography/pullquote.html text="Tone, voice, audience, and the kinds of evidence an author reaches for are exactly what AI smooths out, and exactly what makes a primary source worth reading." %}

{% include typography/callout.html type="note" title="Part of a course" text="One of several AI-first assignments in a remote, asynchronous course. [Start With the AI Answer](../policy/start-with-the-ai-answer.md) explains how they fit together, alongside the assignments that ask for no AI." %}

## The Setup

**Offer a landscape, not a reading list.** Give students four or five digitized sources from the same period and ask them to pick two. They're sampling, not reading five books: title page, preface, table of contents, and pages from throughout, read like artifacts. Who is the author talking to? What problem do they think they're solving? What kind of authority are they trying to project?

**First impression before AI.** Students spend a few minutes with each text and write down their own quick take before prompting anything. Everything else gets measured against this baseline.

**Ask AI for an overview.** What does each author seem to argue, who is the audience, what authority does each project? The answer is a second opinion, not an interpretation.

**Go back to the originals.** Students find specific passages that confirm, complicate, or challenge the AI's overview, paying attention to tone, voice, audience, and evidence.

**The post** includes their own first impression, one useful AI impression, one place the original confirmed it, one place the original complicated or corrected it or made it look generic, and a comparison of the two texts built on specific examples.

**Run it again, with more independence.** A week or two later, with a new set of sources (three this time, from a different period), students write their own prompts instead of relying on a generic "compare these texts." They might ask AI to compare rhetorical strategies, surface assumptions about bodies or evidence, or identify what each author seems most anxious about. The post now includes the prompts themselves, and the comparison is organized around one or two lenses: rhetorical style, continuity with earlier sources, or how each author establishes expertise.

## The Prompt

A basic prompt is fine for the first round. You want the kind of competent overview the originals will complicate:

{% capture second_prompt %}
I'm comparing two texts for a history course: [author, title, year] and [author, title, year]. Give me a basic overview of each: what the author seems to argue, what audience the text addresses, and what kind of authority the author projects.
{% endcapture %}

{% include typography/callout.html type="prompt" title="first-round prompt" text=second_prompt %}

In the second round, students write their own prompts. The examples to give them are lenses, not wording: compare rhetorical strategies, surface assumptions about evidence, explain unfamiliar terms, or name what each author is most worried about.

## Why It Works

The first impression before AI is the key move. Without it, students read the originals primed by AI's version and mostly find what it told them to find. With it, there are three perspectives on the page (theirs, AI's, and the text's), and the analysis starts where they disagree.

Old texts make a natural test case. AI can usually say what a nineteenth-century diet book argues. It's much shakier on how the book sounds: one author's breezy confidence, another's defensive hedging, the appeals to personal experience or laboratory science. Those details tell a historian who a text was for and why it persuaded anyone, and students find them only by going back to the page.

Running it twice turns a structured exercise into a habit. The first round shows students what the back-and-forth looks like; the second asks them to design it.

## What to Grade

The grade rests on the comparison and on the three-way conversation among the student's impression, AI's, and the text.

- **Strong:** the first impression is clearly the student's own; the place where the original complicated AI's answer is specific and explained; the comparison is organized around a lens and built on quoted or cited details from both texts.
- **Middling:** all the parts are there, but the comparison drifts toward two summaries, or the "complication" of AI's view is generic.
- **Weak:** mostly summary, with little sign the student went back to the originals.

In the second round, add the student's prompts to the criteria: did they interrogate the sources, or just ask for a comparison?

## What to Watch For

{% include typography/callout.html type="warning" text="Try the sources in AI yourself first. Well-known texts get detailed, sometimes accurate overviews; obscure ones get confident generalities or confusion with a different book. Both are useful, but you should know which you're assigning." %}

- The comparison collapses into two summaries side by side. Asking for one or two organizing lenses helps.
- Students skip the first impression or write it after the fact. Ask for it first in the post.
- Old typography, like the long *s* that looks like an *f*, slows students down for the first few pages. Warn them in advance.
- A short walk-through of how to sample a long book (what to look at, in what order) pays off in both rounds. I used a video.
