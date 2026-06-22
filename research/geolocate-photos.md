---
layout: sketchbook
title: Photos to Map Pins
experiment: "Create an interactive map with pins for hundreds of photos, using GPS metadata already embedded in your phone's images — in under an hour."
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

<span class="section-accent research"></span>

{% include typography/sketch-info.html %}

I was curious how well AI coding agents could help me create a map of images with a simple prompt.

It took less than an hour to go from a folder of images to a live web map with clickable pins. 

The workflow requires no prior coding knowledge and generalizes to any collection of geolocated images — field photographs, urban documentation surveys, monuments, public art, whatever.

The process described here produced the website [Cats of Marrakech](https://jeseyfried.github.io/cats-of-marrakech/).

{% include typography/pullquote.html text="From download to interactive map in under an hour — with no code written by hand." %}

## The Experiment
During March 2026, I traveled to Marrakech and photographed street cats throughout the medina. With location services enabled in the phone's Camera app, GPS coordinates were embedded in the metadata of every image. By the end of the trip, I had over 200 photos of cats — and 200 precise locations.

I used the [Xanthan](https://xanthan-web.github.io/) web framework, specifically the portfolio template, to start with a simple static website that I could easily update. The template gives you a clean GitHub repository with the files and folders needed for a small website.

After copying the photos into the `images` folder in a GitHub repository, I described the goal to GitHub Copilot in plain language. Copilot wrote all the necessary code: a YAML data file extracting GPS coordinates from each image's metadata, and an updated `map.html` that reads that file and places a clickable pin for each photo. 

No manual data entry, no coordinate lookup, no figuring out how to copy and paste code I didn't understand.

## The Prompt

{::nomarkdown}
<div class="sketch-prompt">
  <span class="sketch-prompt-label">prompt to give to Copilot</span>
  Please create a new YML file in the _data folder that lists each of the images in assets/images. The YML file should include geographic location extracted from the metadata of each image. Then edit map.html so that the map uses the newly created YML file. The overall goal is to have a pin on the map for each of the photos, and when a user clicks on the pin, the image appears.
</div>
{:/nomarkdown}


## Results
Starting with a folder of photos, I produced the website [Cats of Marrakech](https://jeseyfried.github.io/cats-of-marrakech/) in about half an hour.

The major takeaway is that an AI assistant can turn hundreds of geolocated photos into a browsable map very quickly. I could get started because I already knew the basics of the [Xanthan](https://xanthan-web.github.io/) website templates, but those take only about 15 minutes to learn.

Keep in mind that geolocation precision from phones varies. Photos taken inside buildings may have pins placed across the street or several meters off. This is a limitation of phone GPS rather than the workflow itself — but it matters if spatial precision is central to the research question.

## What I Learned

{% include typography/callout.html type="warning" text="Before AI, even something as straightforward as putting pins on a map could take a full day without previous coding experience. Now it can take under an hour, and the AI assistant can explain how the code works along the way." %}

AI coding agents are lowering the barrier for small digital scholarship projects. Even quickly produced maps like this one can expand understandings of human geography through dense, localized image collections. You might consider this for a reconstruction of pilgrimage journeys or migration routes using photographic evidence. 

There is also potential for experimenting with point of view and perspective by mapping where documentation happens. The ease of this process allows for quickly capturing histories of urban development, neighborhood change, or informal space.
