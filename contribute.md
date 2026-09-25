---
layout: sketchbook
title: Contribute a Sketch
description: "How to add your own teaching or research sketch to the AI Sketchbook."
scrollspy: true
---

# Contribute a Sketch

{% include typography/section-accent.html %}

If you've tried something with AI in a class or a research project and have something honest to say about how it went, this is the place for it. Rough drafts and partial experiments are welcome. We're not looking for polished success stories; the most useful sketches are often the ones where something went sideways.
{: .lede}

Your sketch is published under your name and licensed [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/), like everything else here: others can share and adapt it for noncommercial purposes, with credit to you, under the same license.

## The easy way: just email us

[Send a draft to amaranth@unm.edu](mailto:amaranth@unm.edu). A few paragraphs is plenty. It helps if you touch on:

- what you tried, and in what course or project
- the prompt or prompts you used
- what happened: what worked, what didn't, what surprised you
- what you'd change next time

We'll shape it into a sketch, handle the technical parts, and check the draft with you before it goes live.

## The hands-on way: submit through GitHub

The sketchbook runs on GitHub, a free platform for sharing files and hosting websites. If you'd like to build your sketch yourself and see it as a live webpage before sending it to us, here's how. Completely optional, but give it a try!

## 1. Create a GitHub account

Go to [github.com](https://github.com) and sign up. Any email works.

## 2a. Fork the repository

"Forking" makes your own copy of the site's files on GitHub. You can edit it freely without touching the live site.

- Go to [github.com/amaranth-unm/ai-sketchbook](https://github.com/amaranth-unm/ai-sketchbook)
- Click the **Fork** button near the top right
- Keep the default settings and name, and click the green `Create fork` button at the bottom right
- The page refreshes within 5–10 seconds
- Check the URL! The page looks the same, but you're now looking at a repository **under your own account**

{% include typography/callout.html type="tip" title="Contributing again later?" text="If you already have a fork from an earlier sketch, open it and click **Sync fork** before you start. Otherwise your copy is out of date, and your pull request could undo newer changes to the site." %}

## 2b. Turn on your preview website

Your fork holds the files that make the website. Now turn on your own copy of the website itself, so you can see your sketch as a webpage instead of a text file.

- Click the `Settings` tab near the top of the page
- Click `Pages` in the left menu
- Under **Branch**, change `None` to `main`
- Click `Save`
- Click the `Code` tab to get back to your repository's home page

{% include images/figure.html class="right" image-path="/assets/images/github-about-gear.png" alt-text="GitHub repository page showing the gear icon next to the About panel" caption="The gear icon next to **About** sets your website URL." width="35%" %}

- Click the gear icon near the upper right
- Check the box for "Use your GitHub Pages website" and click `Save changes`
- The link that appears next to the gear now goes to your preview site

## 3. Open the editor

From your fork's `Code` tab, press the **`.` (period) key**. A full text editor opens in your browser, with nothing to install.

It looks intimidating because it can do a lot. You only need two parts: the list of files on the left and the editor on the right.

## 4. Create your sketch file

Each section (`teaching`, `policy`, and `research`) has a `_sketch-template.md` file inside its folder, already set up with the right fields and comments marking what's required and what's optional. Don't edit the template itself; copy it.

- In the file list, open the folder that fits your sketch: `teaching`, `policy`, or `research`
- Right-click `_sketch-template.md` and choose **Copy**, then right-click the same folder and choose **Paste**
- Rename the copy in lowercase with dashes and no leading underscore, like `citation-test.md` or `mapping-with-ai.md`. (A leading underscore tells the site not to publish a file, which is why the template never appears on the live site.)
- Open your new file and follow the instructions at the top: fill in the front matter, delete the "before you start" line, and write your sketch

Put your name and department in the `author` field, like `"Jane Doe, Anthropology"`. That's how you're credited on the page and in its suggested citation. For teaching sketches, fill in `context` (the course where you ran it) and `last-run` (the term) too, and add a `handout` link if the student-facing assignment is online.

**Adding images:** drag image files from your computer into the section's `images` folder in the file list. Then refer to them as `images/your-file.jpg`, for example in the `thumbnail` field.

## 5. Commit your changes

Your edits save as you go, but you need to send them to your repository on GitHub, which rebuilds your preview site.

- Click the branch icon in the left sidebar (it looks like a small network diagram)
- Type a short message describing your change, like "add citation-test sketch", and click **Commit & Push**

## 6. Check your site

The rebuild takes a minute or two.

- Go to your repository's `Code` tab
- Click the URL at the top of the `About` panel on the right
- Find your sketch and check that it looks right

If your changes don't appear after a few minutes, click the **Actions** tab. A red ✗ means something in your file broke the build, often a stray quotation mark in the front matter or an include that lost its closing `%}`. Compare your file with the template, or [email us](mailto:amaranth@unm.edu) and we'll sort it out.

## 7. Submit your sketch

Go back to your fork at `github.com/YOUR-USERNAME/ai-sketchbook`.

- Click **Pull requests** near the top
- Click **New pull request**
- Click **Create pull request**
- Add a short note and click **Create pull request** again

That sends your sketch to us for review. We'll either merge it into the live site or send you feedback. By submitting, you agree to publish it under the site's [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.

## Questions?

Email [amaranth@unm.edu](mailto:amaranth@unm.edu). We're happy to help you get unstuck at any step.
