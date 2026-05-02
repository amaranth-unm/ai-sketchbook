---
layout: sketchbook
title: Contribute a Sketch
description: "How to add your own teaching or research sketch to the AI Sketchbook."
css: sketchbook.css
---

# Contribute a Sketch

<span class="section-accent default"></span>

If you've tried something with AI in a class or a research project — and you have something honest to say about how it went — this is the right place for it. Rough drafts and partial experiments are welcome. We're not looking for polished success stories.

Here's how to add your sketch. You don't need to know anything about GitHub to start.

---

## 1. Create a free GitHub account

GitHub is the service that stores the files behind this site. Go to [github.com](https://github.com) and sign up. Any email works.

---

## 2. Fork the repository

"Forking" means making your own personal copy of the site files — you can edit it freely without touching anything on the live site.

- Go to [github.com/amaranth-unm/ai-sketchbook](https://github.com/amaranth-unm/ai-sketchbook)
- Click the **Fork** button near the top right
- Click **Create fork** — that's it. You now have your own copy.

---

## 3. Open the editor

From your forked repository, press the **`.` (period) key** on your keyboard. This opens a full editor in your browser — no software to install.

---

## 4. Create your sketch file

In the editor's left panel, right-click the `teaching` or `research` folder and select **New File**. Name it something short and descriptive using all lowercase and dashes — like `citation-test.md` or `mapping-with-ai.md`.

Paste this starter template into your new file and fill it in:

```
---
layout: sketchbook
title: Your Sketch Title
description: "One sentence describing what this is."
summary: "One sentence for the card on the listing page."
css: sketchbook.css
status: rough
section: teach
tags:
  - your-tag
skills:
  - one concrete thing students or researchers gain
card_order: 10
---

# Your Sketch Title

<span class="section-accent teach"></span>

Write your sketch here. What did you try? What happened? What would you do differently?

## How It Works

## Sample Prompt

## Caveats
```

Change `section: teach` to `section: research` if it belongs in the research section.

---

## 5. Save your work

Click the branch icon in the left sidebar (it looks like a small network diagram). Type a short message describing your change — like "add citation-test sketch" — and click **Commit & Push**.

---

## 6. Submit your sketch

Go back to your forked repository at `github.com/YOUR-USERNAME/ai-sketchbook`.

- Click **Pull requests** near the top
- Click **New pull request**
- Click **Create pull request**
- Add a short note and click **Create pull request** again

That sends your sketch to us for review. We'll take a look and either merge it into the live site or send you a note with feedback.

---

## Questions?

Reach out at [amaranth@unm.edu](mailto:amaranth@unm.edu) — we're happy to help you get unstuck at any step.
