---
layout: sketchbook
title: Narrate the Slides
summary: "Students compare an AI narration of historical images with details they can interpret using the course."
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
  - "support an interpretation with visual and textual details"
  - "examine the connections a narrative makes between sources"
  - "explain what a short caption leaves out"
card_order: 110
---

# Narrate the Slides

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

For a day without an assigned reading in my history of diet and health course, I gave students a deck of historical images without added captions or narration. They asked AI for one sentence per slide, linking each image to the next. Then they went back through the deck to examine details that the resulting story had passed over.

This is part of a remote, asynchronous course on the history of diet and health. [Start With the AI Answer](../policy/start-with-the-ai-answer.md) describes the course design.

## Preparation and submission

Students need relevant course readings to interpret the images. Retain source and date information separately from the unnarrated deck so claims can be checked afterward. Test the image upload; supplying a shared narration is an alternative when students can't use image-capable tools.

The submission is the short post described below. **Suggested revision:** allow students to analyze a caption's well-supported choice as well as an omission or error; they needn't find a fault in every selected image.

## Preparing the deck

Choose ten to twenty images related to the course so far and put them in a rough order. Dense advertisements, crowded illustrations, charts, and posters offer plenty to examine. Leave the images' own text visible, but don't add your explanation of them.

Students give the deck to a tool that can read images and ask for the connecting captions below.

## The Prompt

{% capture slides_prompt %}
Here is a slide deck of historical images: [attach or upload the slides]. Write one sentence for each slide that captions it and connects it to the next slide, so the result reads as a single narrative. Give me a bulleted list, one sentence per slide.
{% endcapture %}

{% include typography/callout.html type="prompt" title="prompt to give students" text=slides_prompt %}

## Looking again

With the captions available for comparison, students return to the images. Ask them to find details the captions overlooked, oversimplified, or misread: small print, a figure in the background, figures on a chart, or assumptions about who eats what.

Their short post has three parts:

- a brief observation about the generated narrative;
- a close examination of two or three slides, using the course to assess the narrative's treatment of specific details;
- a brief comparison with one classmate's post.

They don't need to paste the generated captions into the post. Quotations should serve the analysis of particular images.

## From detail to interpretation

**Constructed example — invented poster and caption.** A wartime poster links food choices to national service. AI captions it as advice to eat a balanced diet. A student points to the appeal to service and uses course material to explain how the poster makes eating a civic obligation.

A stronger post also asks what justifies connecting this poster to the next slide. A shared theme doesn't establish that one campaign influenced another.

## What to discuss and grade

The prompt asks the model to connect the slides, so the class should examine the connections as well as the omissions. What supports the transition from one image to the next? Would another order suggest a different account? These questions apply to our own historical narratives too.

Grade the close examination of the chosen slides. Strong work identifies a detail and explains its historical significance using course concepts. A post that lists omissions needs more explanation; a general complaint about vagueness needs a specific example.

## What to watch for

Check that the tool received the images. A link it cannot open may still produce plausible captions. Uploading images or a PDF export makes it easier to establish what was supplied.

Keep the deck connected to the course so students have knowledge to bring to it. If many choose the same striking slides, use their comparisons to discuss what drew their attention and whether they interpreted the details in the same way.
