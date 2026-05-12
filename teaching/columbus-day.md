---
layout: sketchbook
title: Historical Source Evaluation
description: "A teaching sketch that uses AI-generated historical argument to examine filter bubbles."
summary: "Students prompt AI to analyze a short newspaper article from 1892 and compare results across accounts and incognito mode."
thumbnail: "images/columbus-day.png"
date: 2026-04-09
status: refined
type: activity
effort: "45–60 min in class"
tools:
  - ChatGPT
level: any
tags:
  - source evaluation
  - filter bubbles
  - research skills
skills:
  - comparing interpretations of a source
  - identifying how framing shapes meaning
  - applying historical thinking frameworks
what-students-learn:
  - how context shapes historical interpretation
  - what filter bubbles look like in practice
  - the difference between pronouncing and puzzling about sources
card_order: 20
---

# Historical Source Evaluation

<span class="section-accent teach"></span>

{% include typography/sketch-info.html %}

Ask AI to perform a historical analysis of a short article from 1892 announcing President Harrison's establishment of Columbus Day as a federal holiday. Students will see different analyses generated when they're logged into their personal account versus incognito mode — and that difference becomes the lesson.

{% include typography/pullquote.html text="When some historical context goes missing, the meaning of the narrative changes dramatically. Students experience this firsthand rather than taking it on faith." %}

## The Setup

This works best with students working individually so they can compare the diversity in responses using their own accounts as well as the variety that might emerge from incognito chats.

The activity is grounded in Sam Wineburg's *Why Learn History When It's Already on Your Phone* (Chapter 4). Wineburg gave the same document — a short *New York Times* article from July 22, 1892 about Columbus Day — to a high-achieving AP US History student (Jacob) and to a group of history graduate students. Jacob talked about what Columbus did and whether honoring him is justified. The graduate students immediately began wondering about late nineteenth-century US politics — immigration, nativism, Harrison's political pressures. Jacob issued pronouncements; the graduate students raised questions.

ChatGPT, when responding to a logged-in account, produced something closer to the graduate students' approach: contextual, attentive to immigration and national identity debates of the 1890s. Responding anonymously, it still addressed historical context — but added two paragraphs on the moral dimension of honoring Columbus, left out Catholics, and dropped any critique of assimilation. Different account, different history.

## The Prompt

{::nomarkdown}
<div class="sketch-prompt">
  <span class="sketch-prompt-label">prompt</span>
  Please write a historical analysis of the following article: New York Times pg.8 July 22, 1892 Discovery Day. October 21 Proclaimed a National Holiday by the President. WASHINGTON, July 21 - The following proclamation was issued this afternoon by the President: A Proclamation. Whereas, By a join resolution approved on June 29, 1892, it was resolved by the Senate and House of Representatives of the United States of America in Congress assembled, "that the President of the United States be authorized and directed to issue a proclamation recommending to the people the observance in all their localities of the four hundredth anniversary of the discovery of America on the 21st day of October, 1892, by public demonstration and by suitable exercises in their schools and other places of assembly." Now, therefore, I, Benjamin Harrison, President of the United States of America, in pursuance of the aforesaid joint resolution do hereby appoint Friday, Oct. 21, 1892, the four hundredth anniversary of the discovery of America by Columbus, as a general holiday for the people of the United States. On that day let the people so far as possible cease from toil and devote themselves to such exercises as may best express honor to the discoverer and their appreciation of the great achievements of the four completed centuries of American life. Columbus stood in his age as the pioneer of progress and enlightenment. The system of universal education is in our age the most prominent and salutary feature of the spirit of enlightenment, and it is peculiarly appropriate that the schools be made by the people the centre of the day's demonstration. Let the national flag float over every school house in the country, and the exercises be such as shall impress upon our youth the patriotic duties of American citizenship. In the churches and in the other places of assembly of the people, let there be expressions of gratitude to Divine Providence for the devout faith of the discoverer, and for the Divine care and guidance which has directed our history and so abundantly blessed our people. In testimony whereof, I have hereunto set my hand and caused the seal of the United States to be affixed. Done at the City of Washington, this 21st day of July, in the year of our Lord one thousand eight hundred and ninety-two and of the independence of the United States the one hundred and seventeenth. BENJAMIN HARRISON.
</div>
{:/nomarkdown}

## Why It Works

This exercise gives students concrete, firsthand experience with filter bubbles while practicing historical thinking. The Wineburg contrast between Jacob and the graduate students gives the class a frame: are we pronouncing, or are we puzzling? AI makes that distinction visible in real time, and the incognito comparison adds a second layer — the same tool, shaped by different contexts, producing different histories.

## What to Watch For

{% include typography/callout.html type="warning" text="As LLM training sets include more material on historical thinking, AI may become less likely to leave out relevant context — which would reduce the contrast between logged-in and incognito responses. The exercise may need updating as models improve." %}
