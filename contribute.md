---
layout: sketchbook
title: Contribute a Sketch
description: "How to add your own teaching or research sketch to the AI Sketchbook."
scrollspy: true
---

# Contribute a Sketch

<span class="section-accent default"></span>

If you've tried something with AI in a class or a research project — and you have something honest to say about how it went — this is the right place for it. Rough drafts and partial experiments are welcome. We're not looking for polished success stories.

Here's how to add your sketch. You don't need to know anything about GitHub to start.

---

## 1. Create a GitHub account

GitHub is the entirely free service that stores the files behind this site. Go to [github.com](https://github.com) and sign up. Any email works.

---

## 2a. Fork the repository

"Forking" means making your own personal copy of the site files — you can edit it freely without touching anything on the live site.

- Go to [github.com/amaranth-unm/ai-sketchbook](https://github.com/amaranth-unm/ai-sketchbook)
- Click the **Fork** button near the top right
- We want the default settings and name, so just click the green  `Create fork` button at the bottom right.
- You'll see the page refresh within 5-10 seconds.
- Notice the URL! It looks like nothing on the page changed, but you are now looking at a repository **UNDER YOUR OWN ACCOUNT**.  


## 2b. Enable your website
You now have a "local" copy of the repository, which is all files that make the website work. Now, let's enable your own working copy of the website itself, so you can see how your essay looks as a webpage (instead of just the text file that you're editing).  


- Click the `Settings` nav link near the top of the page
- Click the `Pages` link on the left nav
- Click the button that says `None` and change it to `main`
- Click the `Save`  button
- Click the `Code` tab to get back to your repository home folder. 

{% include images/figure.html class="right" image-path="/assets/images/github-about-gear.png" alt="GitHub repository page showing the gear icon next to the About panel" caption="The gear icon next to **About** sets your website URL." width="35%" %}

- Click the gear icon near the upper right
- Check the box for "Use your GitHub Pages website" and click `Save Changes`
- Now the link that appears next to the gear will take you to your website.

---

## 3. Open the editor

From your forked repository Code tab, press the **`.` (period) key** on your keyboard. This opens a full text editor in your browser — no software to install.

It looks intimidating because there is a lot of potential features to use. But we just want a list of files on the left and our files to open on the right. The interface is simply a way of viewing and editing text files.

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

## 5. Commit and Rebuild
You work is basically saved as you work, but you need to tell GitHub to officially move your working files into your repository and rebuild your website.

- Click the branch icon in the left sidebar (it looks like a small network diagram). 
- Type a short message describing your change — like "add citation-test sketch" — and click **Commit & Push**.

---

## 6. Check your site
- Go to your repository `Code` tab
- Click on the URL at the top of the `About` panel on the right
- Verify your changes are working



## 7. Submit your sketch
Go back to your forked repository at `github.com/YOUR-USERNAME/ai-sketchbook`.

- Click **Pull requests** near the top
- Click **New pull request**
- Click **Create pull request**
- Add a short note and click **Create pull request** again

That sends your sketch to us for review. We'll take a look and either merge it into the live site or send you a note with feedback.

---

## Questions?

Reach out at [amaranth@unm.edu](mailto:amaranth@unm.edu) — we're happy to help you get unstuck at any step.
