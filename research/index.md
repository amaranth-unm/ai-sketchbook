---
layout: sketchbook
title: Research Sketches
description: "Workflow experiments, analysis techniques, and methodological notes — ways AI has proven useful (and useless) in actual humanities scholarship."
css: sketchbook.css
date: 2026-04-01
---

{% assign section_pages = site.pages
  | where_exp: "item", "item.dir == page.dir"
  | where_exp: "item", "item.name != 'index.md'"
  | sort: "card_order" %}

# Research Sketches

Workflow experiments, analysis techniques, and methodological notes — ways AI has proven useful (and useless) in actual humanities scholarship.

<span class="section-accent research"></span>

{% include nav/sketchbook-card-list.html pages=section_pages %}

[Browse all sketchbook tags →]({{site.baseurl}}/tags/)
