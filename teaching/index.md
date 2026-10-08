---
layout: sketchbook
title: Teaching Sketches
date: 2026-04-01
wide: true
---

{% assign section_pages = site.pages
  | where_exp: "item", "item.dir == page.dir"
  | where_exp: "item", "item.name != 'index.md'"
  | where_exp: "item", "item.listed != false"
  | sort: "card_order" %}

<div class="section-intro" markdown="1">

# Teaching Sketches

Classroom activities and assignments, with prompts, course context, and notes for trying them yourself. Check each sketch's status and handout to see how much has been tried and what students were asked to do.
{: .lede}

</div>

{% include nav/sketchbook-card-list.html pages=section_pages %}

[Browse all sketchbook tags →]({{ '/tags/' | relative_url }}){: .tag-browse-button}
{: .tag-browse-cta}
