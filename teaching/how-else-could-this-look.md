---
layout: sketchbook
title: How Else Could This Look?
summary: "Students read a long encyclopedia entry on fast food with AI, then spend class figuring out what the article decided to be about — and asking AI to draft the versions that were never written."
thumbnail: "images/beef-burger-amarillo.jpg"
thumbnail-credit: "John Margolies, Beef Burger, Amarillo, Texas, 1976. Library of Congress."
date: 2026-09-12
status: lightly tested
type: activity
effort: "30–40 min in class"
tools:
  - any AI tool
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
  - that a one-clause mention is how a text claims a subject without thinking about it
  - how an article's organization is an argument about what the subject is
  - that AI will name silences fluently and generically if you let it do the noticing
card_order: 50
---

# How Else Could This Look?

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

The reading was a long encyclopedia entry on fast food: thousands of words, authoritative, effectively unsigned, the kind of piece nobody reads closely and everybody feels they've absorbed. Students read it with AI however they liked — summary, outline, explanation. Then we spent class taking that reading apart. We weren't checking the summaries. We were working out what the article had decided fast food was *about*, and what else it could have been.

{% include typography/pullquote.html text="A topic mentioned once and dropped isn't covered. The one-clause mention is how an article claims a subject without having to think about it." %}

## The Setup

**Students arrive having read it with AI**, transcript in hand. Frame that as the assignment, not a confession. Nobody is getting caught, and a class that opens with suspicion gets defensive answers.

**The first five minutes run without AI.** From memory, the class rebuilds the article's skeleton on the board: what it covers, in what order, and roughly how much room each topic gets. Everything after depends on this baseline, and it's the version of the skill that survives when the tools are gone.

**Pairs each take an angle:** labor, race and immigration, gender and domestic work, money, geography, the sources the article rests on, the people doing the eating. Each pair sorts its angle into one of three grades: developed at length, mentioned in a clause and dropped, or absent. The middle grade is where the arguments start, so slow down there. Every claim has to point to the article itself, not to what the AI said about it.

**Then the pairs put AI back to work, twice.** First to expand: instead of *what's missing?*, they ask *tell me about this thing the article skipped*, which shows the class how big the gap is instead of just naming it. Then to speculate: they ask for the version of the article built around their angle, with section headings and an opening paragraph.

**The last ten minutes are the payoff.** Groups put their alternate articles side by side: fast food as labor history, as immigration history, as a story about roads and land, as a story about who cooks at home and who stopped. The question isn't which is best. It's what each version makes the subject *be*, and what each would have to cut to make room.

## The Prompt

Start with the prompt that doesn't work, because it's the one everyone reaches for first.

{% include typography/sketch-prompt.html label="the prompt to argue with" text="What does this article leave out?" %}

It answers instantly and plausibly (labor, race, gender, globalization) without requiring anyone to read anything. Say that out loud early.

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

That last prompt matters most. Without it, students settle on the comfortable conclusion that the marginalized version is simply the better article. With it, they find that every way of organizing a subject has its own edges, a much harder insight to reach by being told.

## Why It Works

An encyclopedia entry makes an ideal target because it presents itself as settled, comprehensive, and authorless, a consensus instead of someone's argument about what matters. Once students see that somebody decided franchising deserved four paragraphs and the workforce one clause, they can see the same kind of choice in textbooks, museum labels, syllabi, and anything else that arrives looking finished.

Reading with AI helped, which surprised me. A summary keeps the claims and drops the proportions, so reconstructing emphasis becomes visible work instead of something students assume they did. The gap between summary and article becomes evidence about how compression works.

The speculative rewrite gives the room its energy. Criticism from outside a text is cheap, and students know it. Building the alternative turns them from critics into authors. Deciding what an article *should* be about takes the same judgment as noticing what it *is* about, but it feels like a design problem instead of a grading exercise.

The pairs matter more than the AI. Most of the useful noise in the room is two people arguing about what to ask next: whether the question is too broad, whether the answer dodged, how to make the model commit to something specific. The questions they invent along the way (what got mentioned and dropped, whose absence matters most, how else the subject could be organized) work on any text, with no AI in sight. The tool is scaffolding for a habit, and scaffolding is meant to come down.

## What to Watch For

{% include typography/callout.html type="warning" text="The biggest trap is letting AI do the noticing. Ask a model what a text leaves out and you get a fluent, generic critique that sounds rigorous and requires no reading at all. Every silence a pair claims has to be shown in the article: the passage where the topic appears and stops, or the place it should have been and isn't." %}

- Pairs stop at the first answer. Asking them to show their second and third prompts, not their best result, changes behavior more than any encouragement to "prompt better."
- The speculative rewrites are confident, frictionless, and full of invented specifics: plausible statistics, tidy chronologies, scholars who may not exist. Treat each one as a proposal to check, never a finding.
- Cynicism creeps in: everything is a silence, every text is complicit, discussion over. Push back by insisting on cost. An entry has a word limit, so what does *this* omission do to the account of fast food that remains?
- Some students won't have used AI at all. They're the control group, and their sense of the article's emphasis is often sharper than anyone's. Say so.
