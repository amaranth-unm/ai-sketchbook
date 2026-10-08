---
layout: sketchbook
title: Citation Test
summary: "Students check an AI-generated bibliography against catalogs, publisher records, and the sources themselves."
thumbnail: "images/eniac-beck-snyder.jpg"
thumbnail-credit: 'Glen Beck and Betty Snyder program the ENIAC, Ballistic Research Laboratory, c. 1947. U.S. Army photo.'
date: 2026-03-28
status: refined
type: activity
effort: "30–40 min in class"
tools:
  - ChatGPT
  - Claude
level: any
author: "Fred Gibbs, History"
tags:
  - source evaluation
  - AI literacy
key-question: "How can AI output help students learn scholarly integrity?"
what-students-learn:
  - "verify bibliographic details using independent records"
  - "check whether an annotation represents its source"
  - "document the evidence for accepting or questioning a citation"
card_order: 20
---

# Citation Test

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Ask AI for a reading list on a focused scholarly topic, then track down the sources together. The exercise gives students practice checking the parts of a citation and deciding whether its annotation describes the source accurately.

Some lists contain invented or garbled references. Others hold up better. Either way, students need to show how they checked them.

## Preparation and submission

Make sure students can access a catalog and publisher or journal records. Test the topic beforehand and save a list for use if a tool is unavailable. Students don't need to know the literature already, but may need a demonstration of searching an exact title.

**Suggested submission:** a verification table with each citation, records consulted, discrepancies or confirmation, and a judgment about its annotation. Mark unresolved searches as unresolved.

## Checking the list

Choose a topic narrow enough to produce a scholarly bibliography but unfamiliar enough that students will need to look things up. Ask for eight to ten works. Students can check them individually or work in teams, with each team reporting on two or three citations.

Use library catalogs, publisher pages, journal databases, and Google Scholar to ask:

- Does the author exist?
- Does the exact title exist?
- Do the journal, publisher, and year match?
- Does the source address the topic claimed in the annotation?

A failed search is a reason to investigate further. It isn't enough on its own to declare a source invented. Record where the group looked and what it found.

## The Prompt

{% capture citation_prompt %}
Give me a reading list of 8 to 10 important scholarly works on [topic]. Include author, full title, journal or publisher, year, and a one-sentence note about why each source matters.
{% endcapture %}

{% include typography/callout.html type="prompt" title="Prompt" text=citation_prompt %}

## Checking more than existence

**Constructed example — not a real citation or search result.** A generated entry gives the correct author, title, and year but claims that a book explains workers' reactions to a factory closure. The catalog confirms the book exists; its introduction instead defines its subject as municipal finance.

The student can confirm the bibliographic details while questioning the annotation. They should cite the introduction and state what further reading would resolve the mismatch. Finding a real book doesn't settle whether it belongs in this bibliography.

## Ask the model to check too

{% capture citation_prompt2 %}
Verify each citation for accuracy and tell me precisely how you verified or generated these citations.
{% endcapture %}

{% include typography/callout.html type="prompt" title="A follow-up prompt" text=citation_prompt2 %}

Compare the follow-up with the students' findings. Does it supply a usable link, correct a citation, or simply repeat its assurance? Its explanation of how a reference was generated is another claim to check. It doesn't give the class direct access to the process that produced the first answer.

## Preparing for the activity

Try the prompt before class so you know what kinds of references it produces. If the citations are accurate, students can examine the annotations and selection: why these sources, and what do they contribute? The exercise needn't depend on catching the tool fabricating a book.

The most useful discussion starts with a particular citation and the work required to verify it. Ask what made it look trustworthy initially and what evidence eventually justified or changed that impression.
