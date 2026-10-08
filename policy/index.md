---
layout: sketchbook
title: Policy Sketches
date: 2026-05-22
wide: true
---

{% assign section_pages = site.pages
  | where_exp: "item", "item.dir == page.dir"
  | where_exp: "item", "item.name != 'index.md'"
  | where_exp: "item", "item.listed != false"
  | sort: "card_order" %}

<div class="section-intro" markdown="1">

# Policy Sketches

Syllabus language, assignment rules, and accounts of course design. Adapt these to what you want students to practice and to your campus rules.
{: .lede}

</div>

{% include nav/sketchbook-card-list.html pages=section_pages %}

[Browse all sketchbook tags →]({{ '/tags/' | relative_url }}){: .tag-browse-button}
{: .tag-browse-cta}
