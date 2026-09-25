---
layout: sketchbook
title: Photos to Map Pins
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
author: "Fred Gibbs, History"
tags:
  - AI-assisted coding
  - maps
  - agentic AI
results:
  - extracted GPS metadata from image files
  - built a map visualization with AI-assisted coding
  - presented geolocated data in a public-facing format
what-i-learned:
  - how GPS metadata is embedded in image files
  - what AI-assisted coding looks like in practice
  - how to turn a personal collection into a public-facing dataset
card_order: 20
---

# Photos to Map Pins

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Could an AI coding agent turn a folder of photos into a map from one plain-language prompt? It could: this workflow produced [Cats of Marrakech](https://jeseyfried.github.io/cats-of-marrakech/), a live web map with a clickable pin for every photo.

No coding knowledge required, and it works for any collection of geolocated images: field photographs, urban surveys, monuments, public art.

{% include typography/pullquote.html text="From download to interactive map in under an hour, without writing a line of code by hand." %}

## The Experiment
During March 2026, I traveled to Marrakech and photographed street cats throughout the medina. With location services enabled in the phone's Camera app, GPS coordinates were embedded in the metadata of every image. By the end of the trip, I had over 200 photos of cats, and 200 precise locations.

I used the [Xanthan](https://xanthan-web.github.io/) web framework, specifically the portfolio template, to start with a simple static website that I could easily update. The template gives you a clean GitHub repository with the files and folders needed for a small website.

After copying the photos into the `images` folder in a GitHub repository, I described the goal to GitHub Copilot in plain language. Copilot wrote all the necessary code: a YAML data file extracting GPS coordinates from each image's metadata, and an updated `map.html` that reads that file and places a clickable pin for each photo. 

No manual data entry, no looking up coordinates, no pasting in code I didn't understand.

## The Prompt

{% include typography/sketch-prompt.html label="prompt to give to Copilot" text="Please create a new YML file in the _data folder that lists each of the images in assets/images. The YML file should include geographic location extracted from the metadata of each image. Then edit map.html so that the map uses the newly created YML file. The overall goal is to have a pin on the map for each of the photos, and when a user clicks on the pin, the image appears." %}


## Results
From the folder of photos to the finished site took about half an hour. I had a head start because I already knew the basics of the [Xanthan](https://xanthan-web.github.io/) templates, but those take only about 15 minutes to learn.

Phone geolocation varies in precision. Photos taken indoors may land across the street or several meters off. That's a limit of phone GPS, not the workflow, but it matters if spatial precision is central to your research question.

## What I Learned

{% include typography/callout.html type="warning" text="Before AI, even something as straightforward as putting pins on a map could take a full day without previous coding experience. Now it can take under an hour, and the AI assistant can explain how the code works along the way." %}

AI coding agents are lowering the barrier to small digital scholarship projects. Even a quick map like this one can deepen our sense of human geography through dense, local image collections. Imagine reconstructing pilgrimage journeys or migration routes from photographic evidence.

Mapping where documentation happens also opens up questions of point of view. Because the process is so easy, it can quickly capture histories of urban development, neighborhood change, or informal space.
