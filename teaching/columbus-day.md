---
layout: sketchbook
title: Same Prompt, Different History
description: "A teaching sketch that uses AI-generated historical argument to examine filter bubbles and the difference between pronouncing and puzzling."
summary: "The same prompt to ChatGPT produces different histories depending on whether you're logged in or not — and that difference is the lesson."
key-question: "Does the same prompt give everyone the same history?"
thumbnail: "images/landing-of-columbus-vanderlyn.jpg"
thumbnail-credit: 'John Vanderlyn, *Landing of Columbus*, 1847. U.S. Capitol Rotunda.'
thumbnail-position: "center 35%"
date: 2026-04-09
status: refined
type: activity
effort: "45–60 min in class"
tools:
  - ChatGPT
level: any
author: "Fred Gibbs, History"
tags:
  - source evaluation
  - historical thinking
what-students-learn:
  - how context shapes historical interpretation
  - what filter bubbles look like in practice
  - the difference between pronouncing and puzzling about sources
card_order: 20
---

# Same Prompt, Different History

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

Students ask ChatGPT for a historical analysis of an 1892 newspaper article announcing President Harrison's proclamation of Columbus Day as a national holiday. Then they ask again in an incognito window. The two histories don't match, and working out why is the lesson.

{% include typography/pullquote.html text="Drop a little historical context and the whole story changes. Students watch it happen on their own screens instead of taking it on faith." %}

{% include typography/callout.html type="note" title="Inspired by" text="Sam Wineburg, *Why Learn History (When It's Already on Your Phone)*, Chapter 4, which gives the same 1892 document to a strong high school student and to history graduate students. **The core change:** the comparison runs between two AI responses, logged in and incognito, so students watch context reshape the history in real time." %}

## The Setup

Students work individually, so each can compare their own logged-in response with an incognito one, and then compare notes with classmates.

Wineburg gave the same document — a short *New York Times* article from July 22, 1892 about Columbus Day — to a high-achieving AP US History student (Jacob) and to a group of history graduate students. Jacob talked about what Columbus did and whether he deserved the honor. The graduate students went straight to late nineteenth-century politics: immigration, nativism, the pressures on Harrison. Jacob issued pronouncements; the graduate students asked questions.

Responding to a logged-in account, ChatGPT sounded like the graduate students: contextual, alert to 1890s debates over immigration and national identity. Responding anonymously, it still offered some context, but it added two paragraphs on the morality of honoring Columbus, left out Catholics, and dropped any critique of assimilation. Different account, different history.

## The Prompt

{% capture columbus_prompt %}
Please write a historical analysis of the following article: New York Times pg.8 July 22, 1892 Discovery Day. October 21 Proclaimed a National Holiday by the President. WASHINGTON, July 21 - The following proclamation was issued this afternoon by the President: A Proclamation. Whereas, By a joint resolution approved on June 29, 1892, it was resolved by the Senate and House of Representatives of the United States of America in Congress assembled, "that the President of the United States be authorized and directed to issue a proclamation recommending to the people the observance in all their localities of the four hundredth anniversary of the discovery of America on the 21st day of October, 1892, by public demonstration and by suitable exercises in their schools and other places of assembly." Now, therefore, I, Benjamin Harrison, President of the United States of America, in pursuance of the aforesaid joint resolution do hereby appoint Friday, Oct. 21, 1892, the four hundredth anniversary of the discovery of America by Columbus, as a general holiday for the people of the United States. On that day let the people so far as possible cease from toil and devote themselves to such exercises as may best express honor to the discoverer and their appreciation of the great achievements of the four completed centuries of American life. Columbus stood in his age as the pioneer of progress and enlightenment. The system of universal education is in our age the most prominent and salutary feature of the spirit of enlightenment, and it is peculiarly appropriate that the schools be made by the people the centre of the day's demonstration. Let the national flag float over every school house in the country, and the exercises be such as shall impress upon our youth the patriotic duties of American citizenship. In the churches and in the other places of assembly of the people, let there be expressions of gratitude to Divine Providence for the devout faith of the discoverer, and for the Divine care and guidance which has directed our history and so abundantly blessed our people. In testimony whereof, I have hereunto set my hand and caused the seal of the United States to be affixed. Done at the City of Washington, this 21st day of July, in the year of our Lord one thousand eight hundred and ninety-two and of the independence of the United States the one hundred and seventeenth. BENJAMIN HARRISON.
{% endcapture %}

{% include typography/callout.html type="prompt" title="Prompt" text=columbus_prompt %}

## Why It Works

Students get a firsthand encounter with filter bubbles while practicing historical thinking. Wineburg's contrast gives the class a question to carry: are we pronouncing, or puzzling? AI makes that distinction visible in real time, and the incognito comparison adds a second layer: the same tool, in different contexts, writes different histories.

## What to Watch For

{% include typography/callout.html type="warning" text="As models absorb more material on historical thinking, they may leave out less context, which would shrink the gap between logged-in and incognito answers. Rerun the comparison yourself before class; the exercise may need updating as models improve." %}
