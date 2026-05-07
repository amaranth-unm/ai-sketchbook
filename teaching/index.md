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

Assignments, discussion setups, and classroom experiments. The common thread: using AI in situations where critical thinking is the actual point, not an afterthought.

<span class="section-accent teach"></span>

{% include nav/sketchbook-card-list.html pages=section_pages %}

[Browse all sketchbook tags →]({{site.baseurl}}/tags/)
