---
layout: sketchbook
title: Research Sketches
description: "Workflow experiments, analysis techniques, and methodological notes: ways AI has proven useful, uneven, and sometimes odd in actual scholarship."
date: 2026-04-01
wide: true
---

{% assign section_pages = site.pages
  | where_exp: "item", "item.dir == page.dir"
  | where_exp: "item", "item.name != 'index.md'"
  | where_exp: "item", "item.listed != false"
  | sort: "card_order" %}

<div class="section-intro" markdown="1">

# Research Sketches

Workflow experiments, analysis techniques, and methodological notes: ways AI has proven useful, uneven, or surprisingly limited in actual scholarship.
{: .lede}

{% include typography/callout.html type="note" title="How to read these" text="Treat each research sketch as a field note from an experiment. The point is not that a tool solved the problem, but what it made possible, what it got wrong, and what expertise was still needed around archives, metadata, data ethics, accessibility, privacy, method, or research computing." %}

</div>

{% include nav/sketchbook-card-list.html pages=section_pages %}

[Browse all sketchbook tags →]({{ '/tags/' | relative_url }}){: .tag-browse-button}
{: .tag-browse-cta}
