---
layout: sketchbook
title: Narrate the Slides
summary: "AI writes a caption linking each image in an unnarrated slide deck to the next; students go back through the slides to find what the course lets them see that the AI story missed."
thumbnail: "images/stereopticon-slides-library-1923.jpg"
thumbnail-credit: "Children viewing stereopticon slides in the Children's Room of the Old Main Library, Cincinnati, 1923. Cincinnati Public Library."
date: 2026-09-25
status: tested
type: activity
effort: "short post; no reading that day"
tools:
  - any AI tool that can read images
level: any
author: "Fred Gibbs, History"
context: "HIST 410 History of Diet and Health (upper-division; remote asynchronous summer course), UNM"
last-run: "Summer 2026"
handout: "https://fredgibbs.net/courses/diet-health-expertise/schedule#fri-717-narrating-a-slide-deck"
tags:
  - source evaluation
  - interpretation
  - historical thinking
  - online teaching
key-question: "What does a smooth narrative leave out of the images it strings together?"
what-students-learn:
  - that images carry historical detail a connecting narrative tends to skip
  - that AI imposes a tidy story on a sequence whether or not the sources support one
  - how much course knowledge they bring to looking at a source
card_order: 110
---

# Narrate the Slides

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

A slide deck with no words is an argument waiting to be made. In a course on diet and health, I gave students a deck of historical images with no captions and no narration. They asked AI to write one sentence per slide, captioning each image and linking it to the next. Out came a neat little story. Then students went back through the slides to find everything that story had skipped.

{% include typography/pullquote.html text="AI will connect any sequence of images into a story. The question is what it had to ignore to make the story smooth." %}

{% include typography/callout.html type="note" title="Part of a course" text="One of several AI-first assignments in a remote, asynchronous course. [Start With the AI Answer](../policy/start-with-the-ai-answer.md) explains how they fit together, alongside the assignments that ask for no AI." %}

## The Setup

**Build the deck.** Ten to twenty images that relate to the course so far, in a rough order, with no text of your own. Busy images work best (dense advertisements, crowded illustrations, charts, posters with small print), because they give the narrative more to skip.

**Students generate the narration.** They give AI the slides and ask for one caption per slide, each connecting to the next, so they end up with something like a bulleted story.

**Then they look for themselves.** With the AI captions in hand, students go back through the slides hunting for what's there, in the image or the text, that connects to the course and never made it into the narration.

**The post** has three parts: a brief comment on what was interesting in the AI output overall; two or three slides examined in depth, with the historical perspective the AI narrative left out, flattened, or got wrong; and a brief comparison with one classmate's post. Students don't post the AI captions themselves; those are raw material for the analysis.

## The Prompt

{% capture slides_prompt %}
Here is a slide deck of historical images: [attach or upload the slides]. Write one sentence for each slide that captions it and connects it to the next slide, so the result reads as a single narrative. Give me a bulleted list, one sentence per slide.
{% endcapture %}

{% include typography/callout.html type="prompt" title="prompt to give students" text=slides_prompt %}

## Why It Works

One sentence per slide forces AI to decide what each image is *about*, and it almost always picks the most obvious answer. The fine print on an advertisement, a figure in the background of a poster, the numbers on a chart, who is shown eating what: all of it falls out of a caption whose job is to reach the next slide. Students notice what the course trained them to see precisely because the AI didn't.

It's also a compact demonstration of how narrative gets imposed. AI will spin a coherent through-line out of any sequence of images, and it's instructive to watch. Historians do the same when they turn sources into a story; the exercise shows what that costs.

And it's a light lift on a day with no reading. Students still do real analysis, just on images instead of a text.

## What to Grade

Grade the in-depth slides. The general comment and the classmate comparison are short by design.

- **Strong:** for each chosen slide, names specific visual or textual details the narrative skipped and explains what they mean historically, using course concepts.
- **Middling:** identifies what the AI missed, but the historical explanation is thin.
- **Weak:** critiques the AI narrative in general terms ("it was vague") without pointing at anything on the slides.

## What to Watch For

{% include typography/callout.html type="warning" text="Check that the AI can actually see the slides. Given a link it can't open, a model may politely say so — or it may produce plausible captions for images it never saw. Uploading the images or a PDF export is more reliable than sharing a URL." %}

- Students critique the AI narrative in general terms ("it was vague") instead of pointing at specific details in specific slides. Require the in-depth slides.
- The deck should be tied to the course. The analysis depends on students bringing course concepts to images the AI reads without them.
- Posts can look alike when everyone picks the most striking slides. The classmate comparison turns that into something to talk about rather than a problem.
