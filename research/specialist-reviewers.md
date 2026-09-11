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

I had a draft article on medieval dietetics and the usual problem: the people best positioned to tell me what was wrong with it were busy, and I would not hear from them until the piece was already under review. So I approximated them. Instead of asking AI for feedback on the draft, I asked it to read the draft as four specific people, one at a time.

{% include typography/pullquote.html text="Asking for feedback gets you feedback. Asking a named reader with a stake in the argument gets you an objection." %}

## The Experiment

The four readers were chosen to match the actual audience the article would meet:

- a **historian of medieval diet and health** — the closest subfield expert, the one who would know the sources
- a **historian of medicine with a modern focus** — an adjacent specialist who would not share my period assumptions
- the **volume editor** — concerned with fit, framing, and the shape of the collection
- **other chapter authors** in the volume — related topics, various expertises, each with their own angle of approach

I ran each as a separate prompt rather than asking for all four at once. That mattered. A single prompt asking for four perspectives tends to produce four paragraphs in one voice, differentiated by label. Separate prompts let each reader work through the whole draft on its own terms and arrive somewhere the others did not.

## The Prompt

{% include typography/sketch-prompt.html label="prompt to give to any AI tool" text="You are a historian of medieval diet and health, reading a draft chapter for an edited volume. Read the draft below and respond as that reader would: what claims would you question, what evidence would you want, what would you push back on, and what does the argument assume that a specialist in your area would not grant? [paste draft]" %}

Then the same structure for each other reader, with the vantage point and its concerns swapped in — the volume editor asked about fit and framing, the modern historian of medicine asked what the piece takes for granted about periodization and continuity.

## Results

Every one of the four produced something I had not considered. They also each produced suggestions that were not especially relevant to what I was doing. That ratio held across all four perspectives — no reader was uniformly useful, and none was useless.

The productive part was that the irrelevant suggestions were irrelevant in *different ways*, depending on who was ostensibly speaking. The adjacent specialist pushed on things the subfield expert took for granted; the editor cared about matters neither historian raised. Reading the four sets against each other made it easier to see which objections were artifacts of the framing and which were real gaps.

I revised the draft substantially as a result. I think it is more robust for it — better defended at the places where a reader outside my immediate subfield would have stopped and objected.

## What I Learned

{% include typography/callout.html type="warning" text="This is not a substitute for actual peer review, and the simulated readers are not the people they name. It is a way to find weak points before real readers do — the objections are worth taking seriously as objections, not as evidence about what any particular scholar thinks." %}

The main finding is that specificity in the reader produces specificity in the response. "Review this draft" yields the generic register of feedback; "read this as the volume editor" yields something with a point of view and, usefully, an agenda.

I did not experiment enough to have advice on doing it better — how many readers is optimal, whether the reader descriptions should be longer, whether feeding back the other reviews would sharpen or homogenize them. Those seem like the obvious next things to try.
