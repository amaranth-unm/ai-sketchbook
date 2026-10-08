---
layout: sketchbook
title: AI Reading Investigation
summary: "Students compare their first reading of an article with an AI discussion and explain what changed, if anything."
thumbnail: "images/rembrandt-scholar-at-his-study.jpg"
thumbnail-credit: "Rembrandt, *A Scholar Seated at a Desk*, 1634. National Gallery Prague."
date: 2026-09-25
status: tested
type: assignment
effort: "~400-word post after reading with AI"
tools:
  - chatbot with access to the assigned article
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
key-question: "How does discussing a reading with AI affect a student’s interpretation?"
what-students-learn:
  - "test a proposed interpretation against passages in an article"
  - "identify where a summary changes or oversimplifies an argument"
  - "develop a reading question from an initial uncertainty"
card_order: 80
---

# AI Reading Investigation

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

In my history of diet and health course, students read Steven Shapin's “Trusting George Cheyne.” I wanted them to consider why people trusted Cheyne and what that trust tells us about expertise. I gave them a sequence of AI prompts to help investigate the article, followed by a short post explaining what they checked in the text.

This is part of a remote, asynchronous course on the history of diet and health. [Start With the AI Answer](../policy/start-with-the-ai-answer.md) describes the course design.

## Preparation and submission

Students need the full article and relevant course discussions about expertise. Test that the tool can read the supplied text and demonstrate checking a suggested passage. The proposed submission below consists of initial notes and a 400-word post; the linked handout preserves the assignment as given.

## A sequence for a difficult reading

Before using AI, students write two or three notes about what they think the article is doing and what confuses them. These provide something to compare with their later interpretation.

Each stage of the sequence has a different purpose. Students can adapt it to the reading and follow up where necessary:

1. **Get oriented:** identify the question, argument, and use of evidence.
2. **Map the problem:** make a table of the factors the author discusses, the evidence for each, and uncertainties. In this article, the factors concerned Cheyne's credibility.
3. **Clarify concepts:** explain a term in context and identify something to check on returning to the article.
4. **Locate evidence:** suggest passages to reread and what to look for in them.
5. **Compare interpretations:** propose three readings and the evidence supporting or complicating each.
6. **Connect with the course:** develop specific connections to themes already discussed.
7. **Refine a student idea:** respond to the student's own tentative interpretation and identify what it would need to establish.

This sequence gives AI work we often ask students to practice: identifying an argument, selecting passages, and proposing interpretations. It gives students suggestions to test against the article, but limits their practice making those first judgments. If that independent reading is the aim, an adaptation would be to begin with students' interpretations and use only step 7.

For a shorter exercise in assessing AI's reading, use orientation, evidence-finding, and interpretation-testing: steps 1, 4, and 5.

## Opening and closing prompts

{% capture reading_prompt %}
I am reading [author, title] for a course on [subject]. Give me a concise orientation to the article: what question is the author asking, what is the main argument, how is evidence used, and what historical problem is the author trying to solve? Do not provide a flat, high-level summary of topics. Focus on the argument and evidence.
{% endcapture %}

{% include typography/callout.html type="prompt" title="first prompt in the sequence" text=reading_prompt %}

{% capture reading_prompt7 %}
I need to write my own reading reflection. Here is my current possible angle: [paste your own rough idea]. Based on our discussion, give me a few ways I might sharpen or complicate it. Do not write the reflection for me. For each suggestion, tell me what evidence from the article I would need to verify before using it.
{% endcapture %}

{% include typography/callout.html type="prompt" title="last prompt in the sequence" text=reading_prompt7 %}

## A revised post

For another run, I'd stop requiring students to report a useful suggestion and a passage they understood better. Those requirements make an unsuccessful exchange difficult to describe honestly.

Ask for about 400 words addressing:

- a suggestion they accepted, rejected, or remained unsure about, and why;
- a claim they checked against the article and what they found;
- a passage for which the exchange changed, confirmed, or confused their reading;
- their own answer to the central historical question.

Ask for the initial notes too, so students can explain what changed or stayed the same. A well-supported account of an unhelpful exchange should meet the assignment's requirements. The post should spend its space on passages and interpretations rather than retelling the chat.

## Testing a proposed reading

**Constructed example — no quotations from Shapin or student work.** AI proposes that readers trusted an expert solely because his recommendations were effective. A student finds a passage discussing the expert's character and relationships. They quote that passage, explain how it complicates “solely,” and revise the account of credibility.

If the passage instead supports the proposed interpretation, the same process can justify accepting it. The post needs the evidence and reasoning, not a required story about catching AI out.

## Assessing the work

Look for specific passages, an explanation of what was checked, and a defensible answer to the historical question. Completing the post doesn't establish that a student read carefully. Their explanation needs to show why a passage supports or complicates a claim.

Give the same attention to agreement and disagreement with the model. Accepting a claim needs evidence; rejecting it needs reasons. Students shouldn't have to manufacture an error or a benefit to complete the task.

## Preparing the reading

Try the sequence yourself first. Answers can differ considerably depending on whether the tool has the article or is answering from its title. Make access to the text explicit in the instructions, and check the passages the model recommends. Knowing the reading's particular difficulties will help you respond when students encounter them. State which tool or account students can use and how they should supply the article. Another adaptation would be to provide one generated response for everyone to examine, avoiding the need for individual accounts.
