---
layout: sketchbook
title: Photos to Map Pins
description: "A workflow experiment in vibe coding a website to display 200 geolocated photos of street cats."
summary: "Create an interactive map with pins for hundreds of photos, using GPS metadata already embedded in your phone's images — in under an hour."
thumbnail: "images/marrakech-thumbnail.jpg"
date: 2026-04-09
status: tested
type: data work
effort: "less than 1 hour"
tools:
  - GitHub Copilot
  - GitHub Pages
level: any
tags:
  - vibe coding
  - maps
  - agentic AI
skills:
  - extracting GPS metadata from image files
  - building a map visualization with AI-assisted coding
  - presenting geolocated data in a public-facing format
demonstrates:
  - how GPS metadata is embedded in image files
  - what vibe coding looks like in practice
  - how to turn a personal collection into a public-facing dataset
card_order: 20
---

# Photos to Map Pins

<span class="section-accent research"></span>

{% include typography/sketch-info.html %}

The process described here produced the website [Cats of Marrakech](https://jeseyfried.github.io/cats-of-marrakech/). It took less than an hour from downloading the images to a laptop to a live map with clickable pins. The workflow requires no prior coding knowledge and generalizes to any collection of geolocated images — field photographs, pilgrimage routes, urban documentation surveys.

{% include typography/pullquote.html text="From download to interactive map in under an hour — with no code written by hand." %}

## The Workflow

During Spring Break, I traveled to Marrakech and photographed street cats throughout the medina. With location services enabled in the phone's Camera app, GPS coordinates were embedded in the metadata of every image. By the end of the trip, I had over 200 photos — and 200 precise locations.

After copying the photos into an `assets/images` folder in a GitHub repository, I described the goal to GitHub Copilot in plain language. Copilot wrote all the necessary code: a YAML data file extracting GPS coordinates from each image's metadata, and an updated `map.html` that reads that file and places a clickable pin for each photo. No manual data entry, no coordinate lookup, no JavaScript written by hand.

## The Prompt

{::nomarkdown}
<div class="sketch-prompt">
  <span class="sketch-prompt-label">prompt to give to Copilot</span>
  Please create a new YML file in the _data folder that lists each the images in assets/images. The YML file should include geographic location extracted from the metadata of each image. Then edit map.html so that the map uses the newly created YML file. The overall goal is to have a pin on the map for each of the photos, and when a user clicks on the pin, the image appears.
</div>
{:/nomarkdown}


## Results

The major takeaway from this experiment is that in just a half hour an AI assistant can create a map with hundreds of your photos. The only coding knowledge required is the basic framework for the [Xanthan](https://xanthan-web.github.io/) website templates.

Keep in mind that geolocation data from phones is sometimes imprecise at the street level. Photos taken inside buildings may have pins placed across the street or several meters off. This is a limitation of phone GPS rather than the workflow itself — but it matters if spatial precision is central to the research question.

## What I Learned

{% include typography/callout.html type="warning" text="It is far easier than it used to be to transfer photos into a public-facing format." %}

Websites like this can expand understandings of human geography through dense, localized image collections. You might consider this for a reconstruction of pilgrimage journeys or migration routes using photographic evidence. There is also potential for experimenting with point of view and perspective by mapping where documentation happens. The ease of this process allows for quickly capturing histories of urban development, neighborhood change, or informal space.

