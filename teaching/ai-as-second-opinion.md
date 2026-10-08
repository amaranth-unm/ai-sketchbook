---
layout: sketchbook
title: AI as Second Opinion
summary: "Students compare their initial reading of historical diet books with an AI overview, then test both against the sources."
thumbnail: "images/peters-diet-and-health-cover.jpg"
thumbnail-credit: "Cover of Lulu Hunt Peters, *Diet and Health, with Key to the Calories*, 1918."
thumbnail-position: "center 16%"
date: 2026-09-25
status: tested
type: assignment
effort: "reading post, run twice with escalating independence"
tools:
  - chatbot with access to the selected texts
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
  - "sample a long historical text and form an initial interpretation"
  - "use tone, audience, and evidence to compare primary sources"
  - "check an overview against specific passages"
card_order: 100
---

# AI as Second Opinion

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

In my history of diet and health course, students sampled nineteenth- and early twentieth-century diet books, wrote an initial impression, and asked AI for an overview. They then returned to the books to see which parts of that overview held up. I wanted them to attend to how the authors addressed readers and established authority, as well as what dietary advice they offered.

This is part of a remote, asynchronous course on the history of diet and health. [Start With the AI Answer](../policy/start-with-the-ai-answer.md) describes the course design.

## Preparation and submission

Supply readable scans of the selected books and demonstrate sampling before expecting students to compare them. Check whether the tool receives the text rather than just its title. Students submit initial impressions and a source-based comparison; the second round also includes their prompts.

## The first round

Offer four or five digitized sources from the same period and ask students to choose two. Explain how to sample a long book: title page, preface, table of contents, and passages from several parts of the text. I used a short video to demonstrate this.

Before asking AI, students write a quick impression of each source. Who is the author addressing? What problem does the book claim to solve? What evidence or authority does it invoke?

Then they request an overview and return to the originals to locate passages that support, complicate, or contradict it. Ask them to examine tone and style as well as claims. A summary of advice may miss the difference between an author's breezy confidence and defensive hedging.

## The Prompt

{% capture second_prompt %}
I'm comparing two texts for a history course: [author, title, year] and [author, title, year]. Give me a basic overview of each: what the author seems to argue, what audience the text addresses, and what kind of authority the author projects.
{% endcapture %}

{% include typography/callout.html type="prompt" title="first-round prompt" text=second_prompt %}

## A revision to the reading post

The original post asked for a useful AI suggestion and passages that both supported and complicated the overview. For another run, I'd leave those outcomes open. Ask students to compare their first impressions with the overview, explain which suggestions they accepted or rejected, and support their judgments with passages from both books. An overview that added nothing, or one that held up on checking, should be possible to report.

The first impression gives them a point of comparison when they encounter the AI interpretation. It may help them notice where they were persuaded by it, or where their reading had already taken them in another direction.

## A second round

A week or two later, repeat the activity with three sources from a different period. This time students write the prompts. Suggest possible angles, such as rhetorical strategies, assumptions about evidence, or sources of authority, and let them decide how to pursue one.

The post includes those prompts and organizes the comparison around one or two questions. It should do more than place a separate summary of each book beside the others.

## Comparing an overview with a passage

**Constructed example — an invented book and overview.** AI describes a diet manual as practical advice for everyone. Its preface addresses households able to employ a cook and buy particular ingredients. A student uses that passage to narrow the claimed audience and compares it with the audience of the other source.

The point isn't simply that AI omitted a detail. The student explains how the assumed resources affect who could follow the advice. If the overview already identifies this audience, they can assess how well the passage supports it.

## What to grade

Look for a comparison supported by quoted or cited passages. Students should explain where a source supports, complicates, or leaves unresolved the AI account, and why that finding matters. In the second round, also consider how their prompts helped develop the comparison.

A completed sequence can still produce a general response. Ask for a closer reading when a student says the AI was vague without identifying what a passage adds.

## Before assigning the sources

Try asking about the books yourself, with the same access students will have. An answer based on an uploaded text may differ from one based only on a title. Be explicit about what students should give the tool.

Old typography can also slow reading. A brief explanation of features such as the long s helps students get started. Ask for their initial notes at the beginning of the post so they remain part of the comparison.
