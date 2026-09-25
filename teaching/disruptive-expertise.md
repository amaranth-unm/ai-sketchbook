---
layout: sketchbook
title: Disruptive Expertise
summary: "Each student researches one moment when a new technology upended how people made, shared, or trusted information — with heavy AI help and verified sources — and the class publishes the case studies together as a public website."
thumbnail: "images/amman-printers-workshop-1568.jpg"
thumbnail-credit: "Jost Amman, *Der Buchdrucker* (The Printer), woodcut from the *Ständebuch*, 1568. Deutsche Fotothek."
date: 2026-09-25
status: lightly tested
type: project
effort: "semester project: sources workshop, draft, presentation, peer review, final page"
tools:
  - any AI tool
  - NotebookLM
  - GitHub
level: any
author: "Fred Gibbs, History"
context: "HIST 300 Critical Thinking with AI (upper-division), UNM"
last-run: "Spring 2026"
handout: "https://fredgibbs.net/courses/critical-thinking-with-ai/disruptive-expertise-guide"
tags:
  - source evaluation
  - expertise
  - historical thinking
key-question: "What can earlier panics about new information technologies tell us about the debate over AI?"
what-students-learn:
  - how to orient quickly to an unfamiliar period, technology, and society
  - that AI is a useful research assistant and an unreliable authority
  - that arguments about new technologies repeat, with differences that matter
  - how to write public-facing history for a general reader
card_order: 90
---

# Disruptive Expertise

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

When printing arrived in Europe, critics worried about a flood of bad books. The telegraph raised fears about rumors spreading at the speed of wire; radio, about mass manipulation. Sound familiar? Each student takes one of those earlier moments and writes a short case study: what the technology was, what people hoped and feared, and what happened next. They research with plenty of AI help, but every claim gets checked against real sources. Together, the case studies become a public website that traces the pattern across centuries.

{% include typography/pullquote.html text="History won't hand us simple answers about AI, but it helps us ask better questions. And the research itself tests what AI can and can't do for historical work." %}

## The Setup

**Assign technologies, not topics.** The printing press, the telegraph, photography, radio, television, photocopying, personal computers, search engines, social media. Students usually start knowing almost nothing about theirs, and that's useful: they learn how to get oriented in an unfamiliar period with AI's help, and where that help runs out.

**The page has five required parts:**

1. **The technology:** what it was and when it emerged.
2. **The moment of disruption:** why people believed it might change society, especially the authority of experts.
3. **Contemporary reactions:** hopes *and* fears, with at least one historical primary source.
4. **What actually happened:** did the predictions come true?
5. **Connection to AI:** what this case helps us think about now.

**Then one more section: what might be lost.** Each page ends with an account of how the student used AI in research and writing, and what AI-assisted research tends to miss: which nuances, which sources, and how leaning on AI changed the process.

**Scaffold the research in class.** In a sources workshop, students gather and filter about twenty relevant sources into a source-grounded tool like NotebookLM and use it to sketch a preliminary narrative. Then a general chatbot becomes a sounding board: support the thesis, challenge it, find counterevidence and missing perspectives. Point out the difference between the grounded tool and the general one.

**Build in checkpoints.** Drafts go live on the site before a round of lightning presentations (topic, sources, how students steered AI, what's still uncertain). Each student then writes a short peer review of a classmate's page (coherence, sourcing, the AI connection, honest documentation of AI use) before submitting the final version.

**Publish it.** In my version, students each fork a shared GitHub repository, build their page in their own copy, and submit it through a pull request, so nobody can break anyone else's work. Any shared publishing platform would do; the public audience is what matters.

## The Prompt

Research prompts vary by student. Paired with a set of gathered sources, these do the most work:

{% capture de_prompt %}
What perspectives are missing from this account?
What sources would I need to find to tell a fuller story?
What historical context is missing but useful?
What do we NOT know about this topic, and why?
{% endcapture %}

{% include typography/callout.html type="prompt" title="prompts for the sources workshop" text=de_prompt %}

## Why It Works

Students arrive with strong opinions about whether AI is making us dumber. The project sends them to find out how the same fear played out with print or television, and whether it came true. Readings arguing that trust in a new medium has to be built, like Adrian Johns on print, tell them what to look for.

The research doubles as the lesson about AI. An unfamiliar technology is exactly where AI is most tempting and least trustworthy: quick at orientation, fluent about context, unreliable about specific evidence and quotations. The verified primary source and the closing section on what might be lost make students notice that in their own work.

The shared site gives each essay a reason to exist. Each page is small; together they reveal a pattern no single student could have found, which is a nice model of how knowledge gets built.

## What to Grade

The peer review criteria double as a grading checklist, which means students have seen the standard twice before the final version.

- **A coherent story:** a clear through-line from the technology to its disruption, the reactions, what happened, and the connection to AI. The AI connection feels earned, not tacked on.
- **All five parts,** including at least one real primary source and both hopes and fears in the contemporary reactions.
- **Grounded in evidence:** significant claims are sourced, and the page doesn't read as though AI wrote it.
- **An honest AI reflection:** the closing section engages seriously with what AI-assisted research missed, rather than offering a generic caution.
- **A finished public page:** readable headings and relevant images with informative captions.

## What to Watch For

{% include typography/callout.html type="warning" text="The AI connection section tends to be generic ('AI is also a disruptive technology that challenges expertise'). Ask for a specific parallel, and a specific difference, grounded in the case the student just researched." %}

- Primary sources are where AI is weakest and students most need help. Invented or misattributed quotations from historical figures are common; ask where each quotation was found.
- "Contemporary reactions" often captures only excitement or only fear. Ask for both.
- "What actually happened" slides into more history. The question is whether the predictions came true.
- The technical setup (forks, pull requests, page structure) takes real class time. Budget a demo and a help session, and don't let the site mechanics crowd out the research.
- The reflection on AI use is easy to write vaguely. Having peer reviewers ask whether AI use is "honestly documented" helps.
