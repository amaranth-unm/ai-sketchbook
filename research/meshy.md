---
layout: sketchbook
title: Generate 3D Prints from 2D Drawings
description: "Creating a scale model of an IUD from the 1970s using AI-generated 3D files."
summary: "AI can transform a historical line drawing into a 3D-printable file, adding a tactile dimension to research that images alone can't provide."
experiment: "AI can transform a historical line drawing into a 3D-printable file, adding a tactile dimension to research that images alone can't provide."
thumbnail: "images/meshy-screenshot.jpg"
thumbnail-position: "10% 50%"
date: 2026-04-09
status: tested
type: data work
effort: "30–60 min"
tools:
  - Meshy.ai
level: any
tags:
  - 3D printing
  - material culture
results:
  - generated 3D-printable files from 2D historical images
  - reconstructed material culture objects for research
  - incorporated tactile elements into research presentations
what-i-learned:
  - how AI interprets 2D drawings to generate 3D geometry
  - where AI corrects vs. faithfully represents source material
  - what tactile artifacts add to historical interpretation
card_order: 30
---

# Generate 3D Prints from 2D Drawings

<span class="section-accent research"></span>

{% include typography/sketch-info.html %}

3D printing, even via plastic facsimiles, can be a powerful way to understand the physicality of an object. Until recently, though, prints usually required carefully scanned or digitally constructed models.

The experiment here was whether AI can help turn a line drawing into a 3D-printable object.

{% include typography/pullquote.html text="It's one thing to see a line drawing. It's an entirely different experience to hold a replica in your palm and imagine its use." %}

History doctoral candidate Edrea Mendoza researches public health sex education initiatives in Mexico in the 1970s. In the course of that research, she encountered drawings of IUDs manufactured in Mexico during that decade — devices that represented a broader government push for population control. She wanted replicas. It's one thing to see a line drawing; it's another experience entirely to hold a replica in your palm and imagine its use.


## The Workflow
The input is simply an uploaded image. Meshy interprets the drawing, generates a 3D mesh, and exports a file ready for a standard 3D printer.

{% include images/figure.html
  width="100%"
  image-path="images/meshy-screenshot.jpg"
  alt-text="Screenshot of IUD drawing uploaded in Meshy"
  caption="A 2D IUD drawing uploaded to Meshy.ai."
%}


## Results
The free (for basic use) web app [Meshy.ai](https://www.meshy.ai/) uses AI to generate 3D-printable files from 2D images. 

Previous Meshy experiments at [Amaranth](https://amaranth.unm.edu/) with high-resolution photographs of museum objects had produced distorted results, even when using the multi-image option. 


{% capture text %}
The tool sometimes "corrects" what it interprets as imperfections. When we uploaded a 2D drawing of a Middleton Cross, Meshy smoothed and regularized the asymmetries that were part of the original design. For objects where exact appearance matters, experimenting with Meshy settings may be necessary to avoid unwanted "corrections."
{% endcapture %}

{% include images/figure-wrap.html
  image-position="right"
  image-width="60%"
  caption="Screenshot of what Meshy.ai produced for a Middleton Cross."
  image-path="images/meshy-middleton.jpg"
  text=text
%}


But line drawings worked differently: given less visual noise to interpret, Meshy produced accurate representations.



## What I Learned

{% include typography/callout.html type="note" text="AI tools can reliably create printable 3D models from 2D drawings, at least for simple diagrams." %}

When historians present findings, they typically rely on images — slides, reproductions, scans. Sometimes an image connects clearly to the argument; sometimes it remains implicitly related. 

3D prints like these IUDs offer a different possibility: the tactile occupying the same status as the visual in research presentations. AI-assisted 3D generation dramatically lowers the barrier to that kind of work. 

This workflow can extend to any material culture object that survives as a 2D record: architectural drawings, artifact illustrations, anatomical diagrams. Like many AI workflows, strengths and limitations sit right next to each other, so every drawing is its own experiment. But it is quick enough to try that the experiment itself can be revealing.
