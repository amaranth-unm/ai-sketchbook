---
layout: sketchbook
title: Take the AI Draft to the Archive
summary: "Students have AI write a short history of a narrow topic, critique it, then test it against unpublished material in a physical collection — and write about what the model could never have known."
thumbnail: "images/archive-manuscript-division.jpg"
thumbnail-credit: "Harris & Ewing, *The Manuscript Division in the Library of Congress*, c. 1930s. Library of Congress."
date: 2026-09-25
status: rough
type: assignment
effort: "two parts: short critique, then an archive visit and ~1000-word essay"
tools:
  - any AI tool
level: any
author: "Fred Gibbs, History"
context: "HIST 1105 Making History (intro survey), UNM"
handout: "https://fredgibbs.net/courses/making-history/campus-history-ai"
tags:
  - source evaluation
  - historical thinking
  - archives
key-question: "What does the archive know that the model doesn't — and why can't it?"
what-students-learn:
  - that fluent, specific-sounding history can rest on nothing checkable
  - that most of the historical record has never been digitized, and so is invisible to AI
  - that archives are shaped by decisions about what was worth keeping, just as AI output is
  - how to find and work with unpublished material in a physical collection
card_order: 60
---

# Take the AI Draft to the Archive

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Most assignments that pit AI against "real research" check the model against a book or a website, which mostly tests how well it summarizes. This one sends students somewhere the model has never been. They ask AI for a short history of a narrow topic, pick it apart, then carry that draft into a physical collection of letters, minutes, clippings, photographs, and planning files to find out what the record says. The final essay fuses both and has to account for every difference.

{% include typography/pullquote.html text="Most of the past was never digitized. A model can only be confident about what it was trained on, and the manuscript box is where students see the edge of that." %}

## The Setup

The project runs in two parts, with a class discussion in between.

**Pick a topic that is narrow, local, and held somewhere.** A building, an organization, a protest, a local business, a neighborhood institution, a person who mattered to one place. The sweet spot is a topic the internet has barely touched but a nearby collection holds in boxes: university special collections, a local historical society, county records, a church or company archive. Broad topics fail both ways: the AI draft is competent and the archive is overwhelming. A shared sign-up sheet keeps topics from doubling up.

**Part 1: generate and critique.** Students prompt for a ~600-word history, asking for specific dates, people, and sources, and save the response *unedited*. That draft is the baseline for everything that follows. Then they write a short critique (3–5 sentences) quoting one passage that seems reliable and one that seems suspicious or thin, and explaining why. Just as valuable is the byproduct: a list of specific claims to check. Drafts and critiques go up before class, and the discussion compares how differently the model handled different topics.

**Part 2: the archive.** Students bring their list of claims to the reading room. Published histories are fine for orientation, but the assignment asks for unpublished material: manuscript boxes, not just the reference shelf. An archivist is the best guide here, so let them know what students are looking for.

**Write the real essay.** Students reshape the AI draft into a short public-facing history (~800–1000 words) built on what they found, with scanned images, captions that say why each item matters, and citations precise enough (collection, box, folder) that a reader could find the same document.

**The required comparison section.** The essay ends with an AI–Archive Comparison that quotes the original draft and sorts its claims: confirmed, contradicted, or simply absent from the record. Then the reverse question: what did the archive contain that the AI draft never mentioned, and why couldn't it have?

## The Prompt

{% capture archive_prompt %}
Write a short history (~600 words) of [your topic]. Include specific dates, events, people, and sources where possible.
{% endcapture %}

{% include typography/callout.html type="prompt" title="prompt to give students" text=archive_prompt %}

The prompt is deliberately plain. Asking for specifics and sources pushes the model toward claims that can be checked, and toward citations that may or may not exist.

## Why It Works

Check AI against published or digitized sources and it all comes down to accuracy (did it get the date right?), and the models keep getting better at that. Unpublished material changes the question from *accuracy* to *access*. The letters, minutes, and photographs in a manuscript box were never in any training set. When the draft is silent or generic where the box is rich, students are looking at a structural limit that no better prompt could fix.

Part 1 forces a close reading before a verdict. Students have to decide what in the AI draft is checkable, what only sounds specific, and what could describe almost any topic with a few nouns swapped. That list of claims turns an archive visit from browsing into an investigation.

The best essays notice that it cuts both ways. The archive is no neutral corrective to AI; it reflects someone's decisions about what was worth keeping, how to catalog it, and what to call it. A student who finds the gap in the box (the group that left no records, the meeting with no minutes) has learned the AI draft's lesson from the other direction.

## What to Grade

Grade each part on engagement, not on whether the AI draft turned out to be accurate or the archive turned out to be rich.

**The critique (Part 1)**
- **Strong:** quotes specific lines from the draft; separates claims that can be checked from claims that can't be verified without specialist knowledge; honest reasoning, even when uncertain.
- **Weak:** a vague impression ("it seemed made up") with no quotations.

**The essay (Part 2)**
- **Strong:** archival evidence throughout, with specific sources cited down to box and folder; the AI–Archive Comparison quotes the draft and names concrete differences; captions explain why each image matters.
- **Middling:** the archive visit is evident but the engagement is thin, and the comparison stays general ("AI can be inaccurate").
- **Weak:** could have been written without visiting the archive.

## What to Watch For

{% include typography/callout.html type="warning" text="Check with the collection before you assign it. Confirm that there are materials on the likely topics, that the reading room can handle a class's worth of requests, and what the rules are — pencils only, lockers, retrieval times, scanning. An archivist who knows students are coming is an enormous help." %}

- Comparisons drift toward "AI can sometimes be inaccurate." Requiring direct quotations from the unedited draft, sorted into confirmed / contradicted / absent, keeps the comparison concrete.
- Students treat the published history on the reference shelf as the archive. It's useful context, but the assignment only works if they open a box.
- The archive doesn't always cooperate. Say up front that a thin box, honestly described, is still evidence.
- Names change. Buildings, organizations, and places often had earlier names, and cataloging is imperfect. Students who search only the current name often conclude that nothing exists.
- Students edit the AI draft before saving it, and the baseline disappears. Say plainly that the unedited draft is a primary source for this assignment.
- Plan for at least an hour in the reading room, plus retrieval time, and let students hold a box for a second visit.
