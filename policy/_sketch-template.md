---
layout: sketchbook                                          # required — always this value
title: Your Sketch Title                                    # required
summary: "One sentence: the policy move this sketch tries."  # required — drives the listing card and the "Policy aim" box below
thumbnail: "images/your-image.jpg"                          # optional — put the image file in policy/images/; omit for a text-only card
date: 2026-06-22                                            # optional — shown on the listing card
status: rough                                               # optional — rough | lightly tested | tested | refined
type: policy sketch                                          # optional — short label
effort: "course policy + assignment labels"                  # optional — shown as "Format" in the summary box
tools:                                                       # optional — AI tools this policy assumes or names
  - any AI tool
level: any                                                   # optional — who this applies to, e.g. "any", "intro courses"
tags:                                                        # recommended — powers the /tags/ browsing page
  - policy language
key-question: "The question this policy answers."           # recommended — shown on the listing card
what-students-learn:                                         # recommended — shown as "What students learn" in the summary box
  - one concrete thing the policy clarifies for students
  - another concrete thing
card_order: 99                                                # optional — sort position on the listing page; check sibling files and pick the next number
---

# Your Sketch Title

> **Before you start:** duplicate this file into the `policy` folder under a new name — lowercase, dashes, no leading underscore (e.g. `my-policy.md`). Jekyll won't publish a filename that starts with `_`. Then delete this line.

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Open with a sentence or two: what problem this policy is trying to solve, and for whom.

{% include typography/pullquote.html text="A short, quotable line that captures the core idea behind this policy." %}

## The Setup

Describe the situation this policy responds to — what was unclear or unworkable before it.

## Policy Language

Give the actual language, structure, or labels — rename this heading to match what you're sharing (e.g. "Assignment Labels," "Syllabus Language," "Levels of Disclosure").

## Why It Works

Explain the reasoning — why this framing, and what it makes visible that a generic policy wouldn't.

## What to Watch For

{% include typography/callout.html type="warning" text="A caveat, edge case, or place this policy could fail or be gamed." %}

## What I Would Do Differently

Be honest about what you'd change if you wrote this again.
