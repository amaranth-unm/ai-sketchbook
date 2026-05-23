---
layout: sketchbook
title: When AI Could Read What Archivists Couldn't
experiment: "To create an AI agent to work with Gemini and Claude to bulk process 300 images of archival documents and enable full-text search of medieval handwriting."
thumbnail: "images/apr-11-aca-cr-r2053-f4r-violant-img10.jpg"
date: 2026-04-09
status: tested
type: processing sources
effort: "downloaded document images; two hours to set up; automated run of ~12hr/register"
tools:
  - Gemini
  - Claude
  - Open Claw
level: researcher
tags:
  - big data
  - paleography
  - agentic AI
results:
  - built an agentic pipeline for bulk document processing
  - combined multiple LLMs to improve transcription accuracy
  - enabled full-text search of handwritten archival sources
what-i-learned:
  - how to design a multi-model agentic pipeline
  - the difference between usable and citable transcription quality
  - trade-offs between cost, time, and accuracy at scale
card_order: 10
---

# When AI Could Read What Archivists Couldn't

<span class="section-accent research"></span>

{% include typography/sketch-info.html %}

I wanted to know if AI LLMs could translate a notoriously difficult medieval script (Gothic secretarial) from the late fourteenth century. The government of Spain hosts a website called [PARES](https://pares.cultura.gob.es/pares/en/inicio.html) which contains over a million digitized images of archival documents — including much of the material in the Archive of the Crown of Aragon. These documents have been digitized but never transcribed at scale.

{% include typography/pullquote.html text="Combining Gemini and Claude produces usable handwriting recognition for late fourteenth-century Gothic secretarial hand — something even specialized HTR platforms couldn't reliably achieve." %}

## The Workflow

{% capture text %}
In early February 2026, uploading a PARES image to Gemini produced a transcription of better quality than what I had gotten from the specialized HTR platform [Transkribus](https://www.transkribus.org/), even after training a model there with 60 documents of ground-truth transcriptions. Soon after, I started combining results from Gemini and Claude to increase transcription quality further.

By March, I was using agentic AI — specifically Open Claw — to obtain usable HTR and translations for entire registers. The pipeline runs as follows: Open Claw downloads images from PARES, passes each one to Gemini and Claude for parallel transcription, merges the outputs, and writes the result to a text file. A final instruction to Open Claw combines all image-level text files into a single CSV.

{% endcapture %}

{% include images/figure-wrap.html
  class="left"
  width="50%"
  caption="An example of a folio from an ACA register, ACA CR R2053 f4r. The script has been notoriously difficult and abbreviations are frequent."
  image-path="images/apr-11-aca-cr-r2053-f4r-violant-img10.jpg"
  text = text
%}


[Register 1819](https://jonathanseyfried.net/aca-reg1819-transcriptions/) was the first complete register I processed. [Register 2053](https://jonathanseyfried.net/aca-reg2053-transcriptions) — the third — produced notably higher quality output, suggesting that prompt refinement and model improvements between February and March made a measurable difference.

## Results

This pipeline worked successfully and using two different models to hone accuracy of transcriptions and create and audit trail greatly improved my confidence in the transcriptions. It also made clear the kinds of errors that routinely surfaced and exposed some of the contours of the "jagged frontier".

With this workflow I was able to analyze image archives at scale, and the pipelinwe could be applied to any collection of historical images.

It takes about 12 hours to generate transcriptions from a 300-page register, and API costs run approximately $75 per register. 

The resulting text enables discovery through full-text search but is not reliable enough for citation-level accuracy — dates in particular remain inconsistent even after pipeline refinements.


## What I Learned

{% include typography/callout.html type="note" text="It is possible to use agentic AI to generate big data from handwritten documents previously unavailable for automated text recognition." %}

This opens the possibility for full-text keyword search for names and toponyms across entire registers. It is effective to leverage multiple LLMs to check and correct each other's work. Even though the transcriptions and translations were far from perfect, I was surprised at how well the LLMs transcribed the script and expanded abbreviations.