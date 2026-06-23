---
layout: sketchbook                                          # required — always this value
title: Your Sketch Title                                    # required
summary: "One sentence: what you built or extracted, and what it's for."  # required — drives the listing card and the "Experiment" box below
thumbnail: "images/your-image.jpg"                          # optional — put the image file in research/images/; omit for a text-only card
date: 2026-06-22                                            # optional — shown on the listing card
status: rough                                               # optional — rough | lightly tested | tested | refined
type: data work                                              # optional — short label, e.g. "data work" or "processing sources"
effort: "less than 1 hour"                                   # optional — shown as "Format" in the summary box
tools:                                                       # optional — AI tools used
  - name a tool
level: any                                                   # optional — who this is for, e.g. "any", "researcher"
tags:                                                        # recommended — powers the /tags/ browsing page
  - your-tag
results:                                                      # recommended — shown as "Demonstrates" in the summary box and "Results" on the listing card
  - one concrete thing this workflow produced
  - another concrete thing
what-i-learned:                                               # recommended — shown as "What I learned" in the summary box
  - one thing you'd tell someone trying this themselves
  - another thing
card_order: 99                                                # optional — sort position on the listing page; check sibling files and pick the next number
---

# Your Sketch Title

> **Before you start:** duplicate this file into the `research` folder under a new name — lowercase, dashes, no leading underscore (e.g. `my-workflow.md`). Jekyll won't publish a filename that starts with `_`. Then delete this line.

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Open with a sentence or two: what you were curious about, and what you ended up doing.

{% include typography/pullquote.html text="A short, quotable line that captures the core insight of this workflow." %}

## The Experiment

Describe what you actually did, step by step — enough that someone else could reproduce it.

## The Prompt

{% include typography/sketch-prompt.html label="prompt to give to [tool name]" text="The exact prompt you gave the AI tool." %}

## Results

Describe what came out the other end, and link to it if it's public.

## What I Learned

{% include typography/callout.html type="warning" text="A limitation, gotcha, or thing that didn't work as expected." %}

What does this open up for others trying something similar?
