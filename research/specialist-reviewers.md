---
layout: sketchbook
title: A Panel of Specialist Readers
summary: "Ask AI to review a draft article separately as each of the specific readers it will actually face — subfield expert, adjacent specialist, volume editor, fellow contributor."
thumbnail: "images/tacuinum-wine-appraisal.jpg"
date: 2026-08-22
status: tested
type: writing feedback
effort: "one prompt per reviewer; an afternoon to work through the responses"
tools:
  - any AI tool
level: researcher
author: "Fred Gibbs, History"
tags:
  - writing
  - peer review
  - prompting
results:
  - four distinct reviews of the same draft, each from a named vantage point
  - insights from every perspective that I had not considered
  - substantive revisions to the article
what-i-learned:
  - naming a specific reader produces sharper feedback than asking for feedback
  - every perspective mixed genuine insight with irrelevant suggestions
  - sorting the useful from the irrelevant is the actual work
card_order: 30
---

# A Panel of Specialist Readers

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

I had a draft article on medieval dietetics and the usual problem: the people best positioned to tell me what was wrong with it were busy, and I would not hear from them until the piece was already under review. So I simulated them. Instead of asking AI for feedback, I asked it to read the draft as four specific readers, one at a time.

{% include typography/pullquote.html text="Asking for feedback gets you feedback. Asking a named reader with a stake in the argument gets you an objection." %}

## The Experiment

The four readers were chosen to match the actual audience the article would meet:

- a **historian of medieval diet and health:** the closest subfield expert, the one who would know the sources
- a **historian of medicine with a modern focus:** an adjacent specialist who wouldn't share my period's assumptions
- the **volume editor:** concerned with fit, framing, and the shape of the collection
- **other chapter authors** in the volume: related topics, varied expertise, each with their own angle

I ran each as a separate prompt instead of asking for all four at once, and that mattered. One prompt asking for four perspectives tends to produce four paragraphs in one voice with different labels. Separate prompts let each reader work through the whole draft on its own terms and end up somewhere the others didn't.

## The Prompt

{% include typography/sketch-prompt.html label="prompt to give to any AI tool" text="You are a historian of medieval diet and health, reading a draft chapter for an edited volume. Read the draft below and respond as that reader would: what claims would you question, what evidence would you want, what would you push back on, and what does the argument assume that a specialist in your area would not grant? [paste draft]" %}

Then the same structure for each of the others, with the vantage point and its concerns swapped in: the volume editor asked about fit and framing, the modern historian of medicine about what the piece takes for granted on periodization and continuity.

## Results

Every reader raised something I hadn't considered, and every reader also offered suggestions that didn't much matter for what I was doing. No reader was uniformly useful, and none was useless.

The payoff: the irrelevant suggestions were irrelevant in *different ways*, depending on who was supposedly speaking. The adjacent specialist pushed on things the subfield expert took for granted; the editor cared about matters neither historian raised. Reading the four sets against each other made it easier to see which objections were artifacts of the framing and which were real gaps.

I revised the draft substantially. I think it's stronger for it, better defended at exactly the spots where a reader outside my subfield would have stopped and objected.

## What I Learned

{% include typography/callout.html type="warning" text="This doesn't replace peer review, and the simulated readers aren't the people they name. It's a way to find weak points before real readers do. Take the objections seriously as objections, not as evidence of what any particular scholar thinks." %}

A specific reader gets a specific response. "Review this draft" yields generic feedback; "read this as the volume editor" yields a point of view and, usefully, an agenda.

I haven't experimented enough to say how to do it better: how many readers is ideal, whether longer reader descriptions help, whether sharing the other reviews would sharpen or homogenize them. Those are the obvious next things to try.
