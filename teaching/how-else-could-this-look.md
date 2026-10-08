---
layout: sketchbook
title: How Else Could This Look?
summary: "Students compare an encyclopedia entry’s allocation of attention with alternative versions organized around different historical questions."
thumbnail: "images/beef-burger-amarillo.jpg"
thumbnail-credit: "John Margolies, Beef Burger, Amarillo, Texas, 1976. Library of Congress."
date: 2026-09-12
status: lightly tested
type: activity
effort: "30–40 min in class"
tools:
  - chatbot with access to the encyclopedia entry
level: any
author: "Fred Gibbs, History"
context: "HIST 413 American Food (upper-division), UNM"
last-run: "Fall 2025"
handout: "https://fredgibbs.net/courses/american-food/schedule#nov-18-fast-food-frameworks-"
tags:
  - historical thinking
  - source evaluation
  - prompting
  - interpretation
key-question: "What did this article decide to be about, and what did that decision cost?"
what-students-learn:
  - "distinguish a passing mention from a developed explanation"
  - "support a criticism of a text with specific passages"
  - "explain the choices and omissions involved in reorganizing an article"
card_order: 50
---

# How Else Could This Look?

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

The reading was a long encyclopedia entry on fast food: thousands of words in a voice that made the subject seem settled. Students read it with AI however they liked, using summaries, outlines, or explanations. In class, we examined the article's organization: what received sustained attention, what appeared briefly, and what a different account might emphasize.

## Preparation and submission

Choose an entry students can access in full, identify its bibliographic details, and check that the tool receives the text. Students need practice distinguishing an article's topic from its argument. Prepare an example of a mention that doesn't develop an explanation.

**Suggested submission:** the pair's cited passage, alternative headings and opening paragraph, and a brief explanation of what they added and cut. Retain the prompts so the choices can be discussed.

## Reconstructing the article

Students who used AI bring their transcripts. Those who read without it bring their notes or recollections. Comparing what each retained is part of the activity.

For the first five minutes, put AI aside. Rebuild the article's structure on the board from memory: subjects, order, and approximate space given to each. That provides a shared starting point to check against the article.

Pairs then take an angle: labor, race and immigration, gender and domestic work, money, geography, sources, or the people doing the eating. They find where the article develops their subject, mentions it briefly, or leaves it out. The distinction between a mention and an explanation needs discussion. Ask pairs to show the passage behind their judgment.

Next, they ask AI to expand on something the article passes over, then draft an alternative set of headings and opening paragraph organized around their angle. In the final ten minutes, the class compares the alternatives. A labor history and a history of roads and land may make different claims about what fast food is. Each also needs to leave things out.

## Prompts to try

A general prompt is worth testing first:

{% include typography/sketch-prompt.html label="a starting prompt to examine" text="What does this article leave out?" %}

The answer may produce a plausible list without saying much about this article. Use it to explain why the pairs need to identify and support their own questions.

{% capture expand_prompt %}
The article mentions [X] only in passing. Explain what a historian working on [X] in this period would actually want to say about it — the evidence, the people involved, the arguments in the field.
{% endcapture %}

{% include typography/callout.html type="prompt" title="expanding the gap" text=expand_prompt %}

{% capture rewrite_prompt %}
Rewrite this encyclopedia entry with [X] at the center rather than at the edges. Give me the section headings and the first paragraph, so I can see what the article would be organized around.
{% endcapture %}

{% include typography/callout.html type="prompt" title="the speculative move" text=rewrite_prompt %}

{% capture cost_prompt %}
What would this new version have to leave out to make room? Who or what becomes marginal in it?
{% endcapture %}

{% include typography/callout.html type="prompt" title="the follow-up that keeps it honest" text=cost_prompt %}

## When an omission matters

**Constructed example — this is an invented passage, not a quotation from the assigned entry.** An article says “Expansion relied on low-paid workers,” then devotes several sections to brands and advertising. A pair proposes organizing it around shifts, wages, and recruitment.

Their criticism needs more than “labor is missing.” They should explain how the brief mention leaves the role of labor in expansion undeveloped, then specify which brand histories they would shorten. The new organization proposes a historical argument; any added claims still need sources.

## What surprised me

A summary could retain the main claims while losing the proportions of the article. Reconstructing its emphasis gave students a reason to return to the reading and inspect something the summary hadn't preserved.

The alternative articles also gave the discussion somewhere to go. Students had to make choices about organization themselves, including what to cut. Much of the useful discussion happened in pairs as they worked out what to ask next and whether the response addressed it. AI supplied alternative arrangements to examine; students still had to justify the emphasis of each and check any added historical claims. A version to compare would have the pairs write the alternative outlines themselves.

## Where the activity can drift

- **A generic list of omissions replaces reading.** Require the passage where a topic appears and stops, or an explanation of how its absence affects the argument.
- **Pairs accept the first response.** Ask to see their second and third prompts and why they changed the question.
- **Generated rewrites introduce unsupported details.** Treat statistics, quotations, and historical claims as proposals needing verification.
- **Every omission becomes a fault.** Bring the word limit back into the discussion. What should make room for the proposed addition, and why?
