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

Syllabus language, assignment rules, and course-level frameworks for thinking through how AI belongs in learning.

These are not model university policies, and they are not meant to settle the question of AI in higher education. They are decision tools for making local choices visible: what AI is allowed to do, what students are being asked to demonstrate, and where a policy might fail.

{% include typography/callout.html type="note" title="How to read these" text="Treat each policy sketch as a starting point. Adapt the language to your course, your students, your campus rules, and the expertise of people already working on AI literacy, research support, accessibility, academic integrity, and student success." %}

## A Loose Map

The policy sketches mix levels on purpose:

- **Course-level framing** helps instructors name the role AI plays across a semester.
- **Assignment-level language** helps students know what is allowed for a particular task.
- **Process documentation** helps make student judgment visible without turning every case into a detection problem.
- **Caveats and redo paths** help policies stay pedagogical rather than purely punitive.

Many of these sketches may become more useful with partners. A disclosure policy might benefit from a writing program or teaching center; assignment rules might be stronger with library, accessibility, academic integrity, or disciplinary input.

</div>

{% include nav/sketchbook-card-list.html pages=section_pages %}

[Browse all sketchbook tags →]({{ '/tags/' | relative_url }}){: .tag-browse-button}
{: .tag-browse-cta}
