---
layout: sketchbook
title: Remixing Plato
summary: "Students remix Plato's worries about writing into a new dialogue about AI — building the characters themselves, then iterating with AI until each position is sharp."
thumbnail: "images/plato-academy-mosaic.jpg"
thumbnail-credit: '*Plato''s Academy*, mosaic from Pompeii, 1st century. National Archaeological Museum, Naples.'
thumbnail-position: "center 55%"
date: 2026-04-01
status: lightly tested
type: assignment
effort: "1–2 hours out of class"
tools:
  - any AI tool
level: anyone
author: "Fred Gibbs, History"
context: "HIST 300 Critical Thinking with AI (upper-division), UNM"
last-run: "Spring 2026"
handout: "https://fredgibbs.net/courses/critical-thinking-with-ai/dialogue-remix"
tags:
  - interpretation
  - prompting
key-question: "If Plato's worries about writing were recast as worries about AI, what would change and what would stay the same?"
what-students-learn:
  - what AI can and cannot preserve in philosophical argument
  - how old anxieties about new media resemble current debates about AI
  - how form and genre reshape meaning
  - that prompting requires the same clarity as writing
card_order: 10
---

# Remixing Plato

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

In the *Phaedrus*, Socrates worries that writing will give people the appearance of wisdom without the substance: a text can't answer back, and people will stop exercising their memories. Swap "writing" for "AI" and he could be posting this week. Students use AI to remix Plato's worries into a contemporary dialogue about large language models, still about memory, authority, and truth, and then ask what has changed and what hasn't. It has been a student favorite.

{% include typography/pullquote.html text="Prompting is a rhetorical skill as much as a technical one. It takes clarity about purpose, audience, and constraints, and students often learn that from a gloriously messy first attempt." %}

## The Setup

The first version of this assignment asked students to remix a passage into a new form: a text-message exchange, a TED talk, a Reddit thread. It made a playful warm-up, but students who hadn't grasped the original's argument had nothing to push against, and the remixes drifted into style without stakes. The current version builds understanding first and gives the remix an argument to carry.

**1. Warm up with AI as questioner.** After discussing the *Phaedrus* in class, students ask AI to quiz them on it, one question at a time, and then to help them apply it to AI. A second round widens the frame: what hopes and fears have surfaced about writing, the telegraph, radio, television, and the internet, and what do they have in common? A third asks what perspectives a modern dialogue about AI would need.

**2. Assign roles by hand.** Students define three to five characters, each with a clearly stated position. For example, a frightened academic who thinks AI produces "zombie" knowledge, a techno-optimist who sees a spectacular new tool, a purist worried that nothing is authored or trustworthy anymore. Characters can borrow the style of a literary or pop-culture figure, but the position still has to be spelled out, or every character ends up saying the same thing.

**3. Draft.** Students tell AI what they're making and why — a modern remix of the *Phaedrus* about AI — and paste in their role definitions.

**4. Revise and iterate.** Where does it flow, and where is it hard to follow? Are the positions distinct, or do they need sharpening? Students can ask AI to read the dialogue as a high school student would and name its key themes, or to suggest missing perspectives, and then decide whether those help or muddle.

**5. Refine.** Do the characters have personalities that match their positions? Does anyone dominate? Does the argument build? Can the prose be livelier without getting less clear?

**6. Post and read.** Dialogues go on a discussion board before class, and students read and respond to each other's in pairs. A reading on why people resist new technologies (Calestous Juma's *Innovation and Its Enemies*, in my version) makes a good follow-up: is Socrates a technological resister, or is he making a different kind of argument?

## The Prompt

{% capture remix_warmup %}
I am reading Plato's Phaedrus. Ask me three questions, one at a time, about what the point is. Use my answers to help me understand the broader point. Then, ask 3 questions one at a time to help me understand how to apply it to AI. What's similar and what's different?
{% endcapture %}

{% include typography/callout.html type="prompt" title="warm-up prompt" text=remix_warmup %}

{% capture remix_draft %}
Following Phaedrus and Platonic dialogues in general, create a ~1200-word conversation about AI based on the following roles: [PASTE IN YOUR ROLE DEFINITIONS]. [ADD ANY STYLISTIC ADVICE]
{% endcapture %}

{% include typography/callout.html type="prompt" title="drafting prompt" text=remix_draft %}

## Why It Works

The remix makes students state what the original is arguing before they can transpose it. They can't write a character who carries Plato's worry into the present without knowing what the worry is, and the warm-up puts AI to work on that understanding before any writing starts.

Transposing the argument also surfaces the course's central comparison on its own. Some of Socrates' concerns carry over to AI almost unchanged; others don't fit, and the misfit is informative. Students end up reasoning about what's new about AI and what is a very old anxiety about new media.

The character work turns prompting into a knowledge problem. Vague roles produce characters who blur together, and the fix is thinking harder about the positions, not finding a cleverer prompt. Moving between Plato's register and a contemporary one also shows students why the dialogue form stages ideas as exchanges instead of laying them out as arguments.

Asked to describe the assignment, one AI model offered a nice analogy: students are renovating a building with an unpredictable contractor who sometimes misreads the blueprint.

## What to Watch For

{% capture remix_warning %}
If students haven't grasped the larger issues the original raises, the remix has nothing to push against. Don't skip the warm-up, even for students who were in the class discussion.
{% endcapture %}

{% include typography/callout.html type="warning" text=remix_warning %}

- Underspecified roles produce characters who all sound alike. Ask to see the role definitions.
- AI's first drafts come out balanced and bland. The dialogue comes alive in the refining step, when students push for personality and a real argument.
- Too many characters muddle the argument. Three to five is plenty.
- Formatting matters: a dialogue pasted as one giant paragraph is unreadable for the peer-reading step.
