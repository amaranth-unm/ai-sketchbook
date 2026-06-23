---
layout: sketchbook                                          # required — always this value
title: Your Sketch Title                                    # required
summary: "One sentence: what students do, and why it's worth trying."   # required — drives the listing card and the "Basic idea" box below
thumbnail: "images/your-image.jpg"                          # optional — put the image file in teaching/images/; omit for a text-only card
date: 2026-06-22                                            # optional — shown on the listing card
status: rough                                               # optional — rough | lightly tested | tested | refined
type: activity                                              # optional — short label, e.g. "activity" or "assignment"
effort: "30 min in class"                                   # optional — shown as "Format" in the summary box
tools:                                                       # optional — AI tools used, if any
  - any AI tool
level: any                                                   # optional — who this is for, e.g. "any", "intro", "advanced"
tags:                                                        # recommended — powers the /tags/ browsing page
  - your-tag
key-question: "The question this activity helps answer."    # recommended — shown on the listing card
what-students-learn:                                         # recommended — shown as "What students learn" in the summary box
  - one concrete takeaway
  - another concrete takeaway
skills:                                                       # optional — shown as "You gain"; a transferable skill, distinct from the takeaways above
  - a transferable skill students practice
card_order: 99                                                # optional — sort position on the listing page; check sibling files and pick the next number
---

# Your Sketch Title

> **Before you start:** duplicate this file into the `teaching` folder under a new name — lowercase, dashes, no leading underscore (e.g. `my-sketch.md`). Jekyll won't publish a filename that starts with `_`. Then delete this line.

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Open with a sentence or two: what you tried, and why.

{% include typography/pullquote.html text="A short, quotable line that captures the core insight of this sketch." %}

## The Setup

Walk through what you actually did, step by step — enough that someone else could run it themselves.

## The Prompt

{% include typography/sketch-prompt.html text="The exact prompt you gave students or the AI tool." %}

## Why It Works

Explain the pedagogical logic — why this surfaces something worth learning, not just a clever use of AI.

## What to Watch For

{% include typography/callout.html type="warning" text="A caveat, failure mode, or thing to double-check before you run this." %}
