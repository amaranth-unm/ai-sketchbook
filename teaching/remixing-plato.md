---
layout: sketchbook
title: Remixing Plato
summary: "Students define characters and use AI to recast Plato’s argument about writing as a dialogue about AI."
thumbnail: "images/plato-academy-mosaic.jpg"
thumbnail-credit: '*Plato''s Academy*, mosaic from Pompeii, 1st century. National Archaeological Museum, Naples.'
thumbnail-position: "center 55%"
date: 2026-04-01
status: lightly tested
type: assignment
effort: "1–2 hours out of class"
tools:
  - text chatbot
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
  - "explain a philosophical position well enough to write a character"
  - "compare an argument across historical settings"
  - "revise a dialogue when its characters fail to disagree clearly"
card_order: 10
---

# Remixing Plato

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

In the *Phaedrus*, Socrates worries that writing will give people the appearance of wisdom without its substance. A text can't answer questions, and its readers may stop exercising their memories. Students use AI to carry those worries into a dialogue about AI itself, then consider which parts of the argument survive the move.

Students have enjoyed this assignment. My first version asked for a change of genre: a text-message exchange, a TED talk, a Reddit thread. The difficulty was that students who hadn't understood the original argument had little to work with. The current version gives more time to understanding the positions before drafting the dialogue.

## Preparation and submission

Supply the relevant passage from the *Phaedrus* and discuss its argument before the warm-up. Students need enough understanding to evaluate the questions AI asks and the positions it generates.

**Suggested submission:** character descriptions, dialogue, and a short passage-based comparison naming one concern that carries over and one that changes. The original handout records the assignment as run.

## What AI does in this assignment

Generating the dialogue gives students a draft whose arguments they can examine and revise. It also removes the work of composing the exchanges, where a writer may discover that a position is harder to defend than it first appeared. Defining characters and evaluating their dialogue practice only part of that work.

For a course that needs more practice composing an argument, one adaptation would be to have students write a short exchange before generating a comparison. They could then explain which version makes a stronger argument and where the differences matter.

## Preparing and drafting

1. **Use AI as a questioner.** After discussing the *Phaedrus*, students ask AI to quiz them one question at a time, then help them apply the argument to AI. A second round compares hopes and fears about writing, the telegraph, radio, television, and the internet. A third asks which perspectives a modern dialogue would need.

2. **Write the character descriptions.** Students write three to five roles themselves, each with a position and reasons for holding it. One might argue that students need to compose an argument to understand it; another that generated drafts give them more arguments to examine. A third might question who deserves credit for the resulting work. Borrowing a character's style is fine, but the student still has to explain the argument that character will make.

3. **Generate a draft.** Students tell AI what they're making and paste in their role definitions.

4. **Read and revise.** Can a reader tell the positions apart? Where does the argument become hard to follow? Students can ask AI to identify the dialogue's themes or suggest a missing perspective, then decide whether the suggestion helps. They refine the voices and exchanges as well as the claims.

5. **Share the dialogue.** Students post before class and read each other's work in pairs. In my course, Calestous Juma's *Innovation and Its Enemies* follows the assignment. It gives us further questions: which objections to a technology were justified, who stood to gain or lose, and how far can the comparison with Socrates take us?

## The prompts

The warm-up below is a proposed revision. It asks students to work from a supplied passage and leaves room for more than one reading. The questions AI generates also need checking against the text.

{% capture remix_warmup %}
I am reading this passage from Plato's Phaedrus: [PASTE PASSAGE]. Ask me three questions, one at a time, about its argument. Ask me to support my answers with words from the passage. If my reading seems doubtful, point to the passage that raises a difficulty rather than simply supplying a verdict. Then ask me three questions, one at a time, about whether the argument applies to AI. Include a question about where the comparison breaks down.
{% endcapture %}

{% include typography/callout.html type="prompt" title="proposed warm-up prompt" text=remix_warmup %}

The drafting prompt used in the assignment was:

{% capture remix_draft %}
Following Phaedrus and Platonic dialogues in general, create a ~1200-word conversation about AI based on the following roles: [PASTE IN YOUR ROLE DEFINITIONS]. [ADD ANY STYLISTIC ADVICE]
{% endcapture %}

{% include typography/callout.html type="prompt" title="drafting prompt" text=remix_draft %}

## Where the comparison changes

**Constructed example — paraphrases, not quotations from Plato or student work.** One character argues that relying on an external text weakens memory. Another replies that a chatbot can answer follow-up questions, unlike the written text under discussion.

That reply identifies a difference but doesn't establish that the answers are reliable or that the learner understands them. Students return to the supplied passage to decide which concern the reply addresses and which remains. A dialogue that treats all worries about writing as interchangeable misses this distinction.

## What to discuss

The important comparison is between the original argument and the one students have made. Ask them to identify a concern that carries over and one that changes or becomes harder to apply. The dialogue should give them passages to examine, rather than requiring a general verdict about whether old anxieties repeat.

Role definitions also give students something to revisit when the generated characters sound alike. A vague description leaves the model much of the intellectual work. Revising it requires the student to decide what the character believes, why, and what another character could object to.

## What needs attention

- Leave time for the warm-up, even after a class discussion. The earlier version showed me how much the remix depends on understanding the source.
- Ask to see the role definitions alongside the dialogue. They help explain the result.
- Three to five characters is enough to manage. More can make the disagreement difficult to follow.
- First drafts can be bland or turn into consecutive speeches. Revision should address how characters respond to each other.
- Require readable dialogue formatting before the peer-reading step.
- Check that students can use a text chatbot with the passage supplied. For an adaptation that doesn't require individual accounts, an instructor could generate a shared dialogue from students' role definitions and have the class examine it together.
