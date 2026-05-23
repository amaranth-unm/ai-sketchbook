---
layout: sketchbook
title: Policy Sketches
date: 2026-05-22
wide: true
---

{% assign section_pages = site.pages
  | where_exp: "item", "item.dir == page.dir"
  | where_exp: "item", "item.name != 'index.md'"
  | sort: "card_order" %}

# Policy Sketches

Syllabus language, assignment rules, and course-level frameworks for thinking through how AI belongs in learning.

These are not model university policies, and they are not meant to settle the question of AI in higher education. They are decision tools: ways to name a course posture, clarify assignment expectations, and make local choices visible. The point is not to produce one rule for every class. The point is to help instructors, librarians, programs, departments, and other campus partners ask better questions about what AI is allowed to do, what students must still demonstrate, and where a policy might fail.

<span class="section-accent policy"></span>

{% include typography/callout.html type="note" title="How to read these" text="Treat each policy sketch as a starting point. Some offer syllabus language, some offer assignment-level rules, and some offer a vocabulary for institutional conversation. Adapt the language to your course, your students, your campus rules, and the expertise of the people already working on AI literacy, research support, accessibility, academic integrity, and student success." %}

## A Loose Map

The policy sketches mix levels on purpose:

- **Course-level framing** helps instructors name the role AI plays across a semester.
- **Assignment-level language** helps students know what is allowed for a particular task.
- **Process documentation** helps make student judgment visible without turning every case into a detection problem.
- **Caveats and redo paths** help policies stay pedagogical rather than purely punitive.

The sketches are written from classroom and humanities research contexts, but many are easier to use with partners. A citation exercise might become stronger with a librarian. A disclosure policy might benefit from a writing program or teaching center. A research workflow might need archival, metadata, accessibility, privacy, or social-scientific expertise.

{% include nav/sketchbook-card-list.html pages=section_pages %}

[Browse all sketchbook tags →]({{site.baseurl}}/tags/)
