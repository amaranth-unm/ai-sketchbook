---
layout: sketchbook
title: Argument Audit
summary: "Students sort AI-generated objections to a draft, explain their decisions, and revise the claims that need work."
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
key-question: "Which objections would improve this argument, and which miss the point?"
what-students-learn:
  - "locate the claim an objection addresses"
  - "explain why a criticism is relevant or mistaken"
  - "revise an ambiguous or unsupported claim"
card_order: 10
---

# Argument Audit

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

A working thesis often needs criticism before it needs polishing. This exercise gives students a set of objections while there is still time to change the argument. Their job is to decide which objections deserve a revision and explain why.

## Preparation and submission

Students need a draft with a claim and supporting evidence, plus enough knowledge of the topic to judge criticism. Prepare a short sorting demonstration. For an adaptation without individual accounts, supply objections to a shared draft.

**Suggested submission:** the original claim, three annotated objections, and a revised paragraph explaining which criticism prompted the change. If no objection warrants revision, students should justify that judgment.

## Sorting the objections

Students bring a thesis paragraph, an interpretive claim, or a partial draft. They ask an AI tool for its three strongest objections, then annotate each one and sort it into a category:

- too generic to address the claim;
- based on a misreading of the draft;
- pointing to a gap, ambiguity, or unsupported step.

For each objection, students identify the passage it concerns and explain their decision. They revise in response to the third category. If an objection misreads the argument, they should also consider whether their wording made that reading possible.

## The Prompt

{% capture audit_prompt %}
Here is my argument: [paste your thesis paragraph or interpretive claim]. Generate the three strongest objections you can imagine to this argument. For each objection, be as specific as possible — refer to the actual claims I'm making, the evidence I'm relying on, or the logical moves I'm asking the reader to accept.
{% endcapture %}

{% include typography/callout.html type="prompt" 
title="Prompt" 
text=audit_prompt 
%}

## A sorting example

**Constructed example — the claim and objections below are invented.** Claim: “The library's longer opening hours caused the increase in borrowing because loans rose the next term.”

- “Libraries matter to communities” doesn't challenge this claim; it is too general.
- “Closing libraries reduces literacy” misreads a claim about longer hours.
- “Did enrollment or the number of available books also change?” identifies a gap in the causal inference.

A defensible revision would describe borrowing as increasing after the hours changed, while reserving the causal claim until competing explanations are checked.

## What needs modeling

Model the sorting before students begin, especially if they haven't had to explain why a criticism fails. Show how to distinguish an uncomfortable objection from an irrelevant one. Dismissing a criticism should require as much attention to the draft as accepting it.

The model's confidence can make a thin objection seem more substantial than it is. Ask students what the objection would require them to change, and why that change would improve the argument. If they can't answer, the objection may need more examination.

Very early drafts may produce only generic criticism. That can help a student recognize that the claim needs definition, but it gives them less to work with in this particular exercise.
