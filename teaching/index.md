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

Assignments, discussion setups, and classroom experiments for courses that want to engage AI seriously, not just acknowledge it exists. The common thread is using AI to make student thinking more visible, more discussable, and sometimes a little stranger in useful ways.
{: .lede}

{% include typography/callout.html type="note" title="How to read these" text="Treat each teaching sketch as adaptable rather than prescriptive. Some are quick classroom activities; others are assignment frames. The setup sections are there to make adaptation easier, and the caveats are often where the most useful teaching questions live." %}

</div>

{% include nav/sketchbook-card-list.html pages=section_pages %}

[Browse all sketchbook tags →]({{ '/tags/' | relative_url }}){: .tag-browse-button}
{: .tag-browse-cta}
