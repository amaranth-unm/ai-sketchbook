---
layout: sketchbook
title: Teaching Sketches
date: 2026-04-01
wide: true
---

{% assign section_pages = site.pages
  | where_exp: "item", "item.dir == page.dir"
  | where_exp: "item", "item.name != 'index.md'"
  | sort: "card_order" %}

# Teaching Sketches

Assignments, discussion setups, and classroom experiments for courses that want to engage AI seriously — not just acknowledge it exists. The common thread: AI as a tool for sharpening critical thinking, not bypassing it. Each sketch is self-contained and classroom-tested, with enough context that an instructor from any field could adapt it. Some will work best with collaborators: librarians, writing instructors, teaching-center staff, instructional technologists, or colleagues in fields where AI raises different questions.

<span class="section-accent teach"></span>

{% include nav/sketchbook-card-list.html pages=section_pages %}

[Browse all sketchbook tags →]({{site.baseurl}}/tags/)
