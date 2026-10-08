---
layout: sketchbook                                          # required — always this value
title: Your Sketch Title                                    # required
summary: "One sentence: what students do and what question the activity investigates."   # required — drives the listing card and the "Basic idea" box below
thumbnail: "images/your-image.jpg"                          # optional — put the image file in teaching/images/; omit for a text-only card
thumbnail-credit: "Creator, *Title*, date. Source."            # optional — caption and alt text for the image beside the summary box
date: 2026-06-22                                            # optional — shown on the listing card
status: rough                                               # optional — rough | lightly tested | tested | refined
type: activity                                              # optional — short label, e.g. "activity" or "assignment"
effort: "30 min in class"                                   # optional — shown as "Format" in the summary box
tools:                                                       # optional — AI tools used, if any
  - name the tool used, or the capabilities a proposed activity requires
level: any                                                   # optional — who this is for, e.g. "any", "intro", "advanced"
author: "Your Name, Department"                              # recommended — shown in the summary box; the citation uses the name before the comma
context: "HIST 1105 Making History (intro survey), UNM"       # recommended — the course where you ran it: number, title, level
last-run: "Spring 2026"                                       # recommended — most recent term you ran it; add the AI tools if it matters, e.g. "Spring 2026 (ChatGPT, Claude)"
handout: "https://example.edu/your-assignment-page"           # optional — link to the student-facing assignment as students saw it
tags:                                                        # recommended — powers the /tags/ browsing page
  - your-tag
key-question: "The question this activity helps answer."    # recommended — shown on the listing card
what-students-learn:                                         # recommended — shown as "Learning aims" in the summary box
  - one action or skill students will practice
  - another action or skill students will practice
card_order: 99                                                # optional — sort position on the listing page; check sibling files and pick the next number
---

# Your Sketch Title

> **Before you start:** duplicate this file into the `teaching` folder under a new name — lowercase, dashes, no leading underscore (e.g. `my-sketch.md`). Jekyll won't publish a filename that starts with `_`. Then delete this line.

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Start with the particular problem that prompted this sketch. Use the details you have: a reading, an output, an assignment that needed changing, or a task that took too long. If this is a proposal, say so. Don't turn an intended outcome into a claim about what happened.

Use only the sections you need below. Rename or combine them to fit the account. A pull quote is optional; the sketch doesn't need a slogan or a concluding lesson. Keep prompts and practical details someone would need to try it. Don't invent an experience or student reaction to make the prose more personal.

## Preparation

State prior reading or subject knowledge, materials to prepare, and tool capabilities needed. Say what students submit. Label new requirements as suggested adaptations if they differ from the activity as run.

## The activity

Describe what students do, in what order, and what they submit. Explain what AI does in the assignment and what practice students gain or give up by using it. Include the course context and any preparation or timing that mattered. Keep the instructions separate from your interpretation of the results. Label changes you would try next so they aren't mistaken for the activity you ran.

## The prompt

{% include typography/sketch-prompt.html text="The exact prompt you gave students or the AI tool. Label a proposed prompt as proposed." %}

## A worked example

Show a short example of the judgment students make. Use actual work only when you have the record and can share it. Otherwise label it **Constructed example**, identify invented passages or records, and do not present it as an observed outcome. See [STYLE-GUIDE.md](../STYLE-GUIDE.md).

## What happened

If you ran the activity, describe a particular response, difficulty, or change. An example of what a student did or what the tool produced is more useful than a general claim that students learned. If you haven't run it, use this space to explain what you hope to find out, or omit it.

## Assessment and adaptation

For graded work, explain what you look for and what needs revision. Let a well-supported account of an unhelpful exchange satisfy the task; don't require students to find a benefit or an error. Include the practical advice a colleague would need: a confusing instruction, a source to check, whether a free account suffices, or an option to use a supplied response. End with an unresolved question if there is one; you don't need to summarize the lesson again.
