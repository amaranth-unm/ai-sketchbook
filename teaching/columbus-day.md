---
layout: sketchbook
title: Same Prompt, Different History
description: "Compare two AI analyses of an 1892 Columbus Day proclamation and examine their different uses of historical context."
summary: "Students compare logged-in and anonymous responses to the same historical document, then investigate differences in emphasis."
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
  - "identify the historical context a response includes or omits"
  - "distinguish an observed difference from an explanation for it"
  - "compare judgments about the past with questions about its circumstances"
card_order: 20
---

# Same Prompt, Different History

{% include typography/section-accent.html %}

{% include typography/sketch-info.html %}

I asked ChatGPT to analyze an 1892 newspaper article about President Harrison's Columbus Day proclamation, then repeated the prompt in an incognito window. The responses emphasized different things. That comparison suggested a classroom exercise: what counts as historical analysis in each answer, and what might explain the difference?

## Where the comparison came from

In Chapter 4 of *Why Learn History (When It's Already on Your Phone)*, Sam Wineburg describes giving the same document to a strong AP US History student and to history graduate students. The student focused on Columbus and whether he deserved the honor. The graduate students asked about the politics of the 1890s, including immigration, nativism, and the pressures on Harrison.

In my trial, the logged-in response resembled the graduate students' approach. The anonymous response included some context but also added two paragraphs about the morality of honoring Columbus, omitted Catholics, and left out a critique of assimilation. The difference was worth examining even though this trial couldn't establish its cause.

## Preparation and submission

Supply the proclamation below and enough background on the 1890s for students to assess contextual claims. Save paired responses before class as a fallback if anonymous access is unavailable or produces little contrast. Using saved responses changes the activity from generating a comparison to examining one.

**Suggested submission:** two saved responses, annotated passages, and a short explanation separating observed differences from possible causes. Repeating the prompt within each condition gives students another comparison before they attribute a difference to account status.

## Trying it in class

Students submit the same prompt in their own logged-in account and in an incognito window, save both responses, and compare them with classmates' results. Ask them to mark passages about Columbus separately from passages about the people proclaiming the holiday in 1892. Which questions does each response ask of the document? Which judgments does it take for granted?

Record the model and other visible settings where possible. The two conditions may differ in more than account context, and repeated runs may differ too. If the responses are similar, that is also a result to discuss.

## The Prompt

{% capture columbus_prompt %}
Please write a historical analysis of the following article: New York Times pg.8 July 22, 1892 Discovery Day. October 21 Proclaimed a National Holiday by the President. WASHINGTON, July 21 - The following proclamation was issued this afternoon by the President: A Proclamation. Whereas, By a joint resolution approved on June 29, 1892, it was resolved by the Senate and House of Representatives of the United States of America in Congress assembled, "that the President of the United States be authorized and directed to issue a proclamation recommending to the people the observance in all their localities of the four hundredth anniversary of the discovery of America on the 21st day of October, 1892, by public demonstration and by suitable exercises in their schools and other places of assembly." Now, therefore, I, Benjamin Harrison, President of the United States of America, in pursuance of the aforesaid joint resolution do hereby appoint Friday, Oct. 21, 1892, the four hundredth anniversary of the discovery of America by Columbus, as a general holiday for the people of the United States. On that day let the people so far as possible cease from toil and devote themselves to such exercises as may best express honor to the discoverer and their appreciation of the great achievements of the four completed centuries of American life. Columbus stood in his age as the pioneer of progress and enlightenment. The system of universal education is in our age the most prominent and salutary feature of the spirit of enlightenment, and it is peculiarly appropriate that the schools be made by the people the centre of the day's demonstration. Let the national flag float over every school house in the country, and the exercises be such as shall impress upon our youth the patriotic duties of American citizenship. In the churches and in the other places of assembly of the people, let there be expressions of gratitude to Divine Providence for the devout faith of the discoverer, and for the Divine care and guidance which has directed our history and so abundantly blessed our people. In testimony whereof, I have hereunto set my hand and caused the seal of the United States to be affixed. Done at the City of Washington, this 21st day of July, in the year of our Lord one thousand eight hundred and ninety-two and of the independence of the United States the one hundred and seventeenth. BENJAMIN HARRISON.
{% endcapture %}

{% include typography/callout.html type="prompt" title="Prompt" text=columbus_prompt %}

## Describing a difference without explaining it away

**Constructed example — not quotations from the recorded trial.** One answer discusses whether Columbus deserves commemoration; another asks why Harrison promoted a holiday in 1892. Students can classify the first as a judgment about the commemoration and the second as a question about its circumstances, then check any contextual claims against course sources.

That difference supports a comparison of interpretations. It doesn't yet show that account personalization caused it. A fresh run could produce the same contrast within one condition.

## Questions the comparison leaves open

The exercise can raise questions about personalization and filter bubbles, but two responses don't establish that either caused the difference. Distinguish what the class observed from its possible explanations.

Wineburg's comparison supplies a historical question that remains useful across these variations: is the response judging the commemoration, investigating the circumstances that produced it, or doing both? Students can answer that by pointing to the text in front of them.

Rerun the prompt before class. Models change, and a contrast that appeared in one trial may not recur.
