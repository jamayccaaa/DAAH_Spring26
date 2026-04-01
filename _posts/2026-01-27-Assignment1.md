---
title: "Assignment 1"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - Assignment
  - Corpus
---

## Assignment 1 - WORKING WITH A CORPUS (draft)

## Introduction
At first, I was planning to use Filipino revolutionary texts from the Philippine Revolution. However, I faced challenges along the way. When I was working with the word cloud, it only showed me Filipino sentence markers instead of meaningful words, which made it hard to get useful insights. Now, my focus has shifted to exploring books about adventure and escaping ordinary life, such as the following:

* _Alice’s Adventures in Wonderland_ (11)
* _Peter Pan (Peter Pan and Wendy)_ (16)
* _The Wind in the Willows_ (289)
* _Treasure Island_ (120)
* _Around the World in Eighty Days_ (103)

Out of these texts, I initially only knew two: Alice’s Adventures in Wonderland and Peter Pan. I knew both stories revolved around escaping ordinary life or going on adventures. I wanted to understand what makes these stories feel like travelling or going on an adventure, what it’s like to be in a completely new world, to step out of your usual bubble, and what usually happens during these kinds of adventures. What does it mean to enter a new world and break free from your routine? What typically happens during these journeys? Films like Peter Pan and Alice in Wonderland are more than just entertaining, they also reflect ideas about growing up (Lisa Duffy, 2021). Duffy explains that these stories do not just celebrate imagination, but also guide children toward letting go of their curiosity and individuality. They promote accepting social norms and expectations. This shift brings stability and helps reduce fear or uncertainty.

I wasn't sure what other texts to use, so I asked ChatGPT. It helped me find similar stories from Project Gutenberg that matched these two. That’s how I ended up adding three more texts. I didn’t know what the other stories were all about, but they seemed to focus on travel or adventure. So I took the risk and included them, then looked for similarities and interesting points across all of the texts.

I noticed that even if they aren't all fantasy, they share patterns in how adventure is shown. Some focus on physical travel, like sailing or exploring new places. Others dive into imaginary worlds. Despite these differences, all the texts involve leaving a familiar space, facing new situations, and experiencing change. The journey usually has dangerous or uncertain moments. These moments make the adventure feel more meaningful, not just thrilling. Overall, they all present travelling, entering new worlds, and experiencing adventure.

## ANALYSIS AND TOOLS (Voyant Tools and RMarkdown)

When I started placing all of the texts in both Voyant Tools and Posit Cloud and exploring them, the word cloud mostly showed random words from the books. It was also dominated by dialogue and character names such as “said,” “Alice,” and “Peter,” which reflects the narrative nature of the texts. Because of this, it was harder to immediately see deeper themes just from the most frequent words. I could see some words that I could connect to travel and adventure, but there weren’t many of them. So I decided to manually look for words in Voyant Tools. This connects to Ted Underwood's idea that with a smaller set of texts, researchers can tweak their methods, which helps them highlight certain themes better, especially when automated tools miss them. Because of this, I focused on words like _journey, dream, adventure, world, danger, and wonder_, terms that I could relate more clearly to travelling and adventure.

<div style="display: flex; gap: 20px; justify-content: center;">

  <figure style="text-align: center;">
    <img src="/DAAH_Spring26/assets/images/Search.png" style="width: 100%;">
    <figcaption>Searched words</figcaption>
  </figure>

  <figure style="text-align: center;">
    <img src="/DAAH_Spring26/assets/images/WordCloudRMarkdown.png" style="width: 100%;">
    <figcaption>Word Cloud</figcaption>
  </figure>

</div>

When I looked more closely at a wordcloud from RMarkdown, I noticed that one of the most consistent words across all five books that I can connect with travelling is “time.” This led me to assume and think that maybe in these texts, time plays an important role in adventure. The texts might be talking about the sense of urgency or pressure to act and experience things while you still can. Ideas like time-lost or time-wasted could possibly suggest that characters are pushed to leave their ordinary lives, go on adventures, and explore new worlds.

From the graph, I saw that “time” shows the highest and most consistent frequency in all five texts. In contrast, words like “adventure,” “dream,” and “escape” are less visible. This is intriguing because, while the stories focus on adventure and leaving ordinary life, “time” stands out more. It suggests that time plays a significant role in these journeys. It may reflect urgency, movement, or the notion that time can be lost or used during an adventure.

![red highlights](/DAAH_Spring26/assets/images/time-red.png)

I also explored the collocates table in Voyant Tools, and I noticed that some words associated with “time” were highlighted in red. This made me curious, so I decided to graph these collocates together to see if there was a pattern across the texts. I was thinking that maybe these words suggested something deeper, like the idea that not travelling or not using your free time well could lead to losing or wasting time.

![time](/DAAH_Spring26/assets/images/time-.png)

When I looked at the results, I noticed that phrases like “time lost” appeared as common collocates across the texts. This stood out to me because it connects to the idea that time is something valuable, and once it is gone, it cannot be taken back. This could suggest that there is a concern with wasting time, and it made me think that the idea of adventure might be connected to making the most out of time.

“Time lost” appears more frequently in _Around the World in Eighty Days_, although it is still present in all of the texts. This makes sense since the story is based on a limited time frame. Because of this, losing time feels more important, since it could affect whether they succeed or not. It shows that time is not just passing, but something that needs to be used carefully, which adds pressure to the journey.

At the same time, I am aware that I am only doing distant reading, so I cannot fully confirm what the authors intended to say. Seeing these repeated collocates made me more curious about how time is represented in these stories, and whether it plays a role in pushing characters to leave their ordinary lives and experience something new. However, since I am only using distant reading and collocate patterns, this is not a definite conclusion, but it suggests a possible connection between time, urgency, and the idea of going on adventures. Following Ted Underwood’s idea of a “relational mode of reasoning,” instead of looking for one fixed meaning, I look at patterns across the five texts as a group, using them to understand how themes like time and adventure appear in different ways depending on the story.

Overall, even if the word cloud does not directly highlight adventure-related words, looking deeper into the texts shows that themes like time, journey, and escape are still present across all five works.


## REFLECTION

Working on this project made me realize that distant reading is not always straightforward. At first, I thought that tools like _Voyant_ and _R Markdown_ would immediately show clear themes. I knew the texts centered on exploring, travel, and adventure. Therefore, I expected to find many words that highlighted these ideas. However, instead of that, I mostly saw common words like character names and dialogue. This made it challenging to quickly identify deeper meanings, revealing that word frequency alone doesn’t always show a text's themes. Because of this, I had to examine the data more closely. I couldn’t just focus on the most frequent words. This pushed me to think more critically about what the data truly shows.

Using _Voyant_ and _R Markdown_ showed me patterns in all texts at once. It’s hard to spot these through regular reading, especially when time is short. These tools made it easier to identify which words appear the most, examine collocates, and track how often certain words are used. This helped me get a general sense of the texts and their possible themes. However, I also realized that this does not guarantee a full understanding of the texts. The tools show patterns, but they do not explain the full meaning or context behind them, which means interpretation is still necessary.

Working with five texts is fine. However, adding more can become overwhelming or hard to handle, depending on the situation. I think it also depends on the type of texts. If the texts are long, then it would be difficult to handle since there will be hundreds of thousands of words that connect to each other. If I had more texts, I’d pick fewer or easier ones. This way, I could use my time better instead of waiting for texts to load or feeling stressed.

Additionally, I was really fascinated by _Voyant Tools_ because I found it much easier to navigate and understand compared to _R Markdown_. Whenever I open _R Markdown_, I tend to feel a bit intimidated and confused, which makes me lean more toward using _Voyant_. I find _Voyant Tools_ more user-friendly, especially when creating different types of data tables or visualizations to see the data more clearly. It feels more organized and visually appealing, which makes the analysis process easier to follow. I would definitely use _Voyant_ again if I need to.

When I tried both tools, I noticed they sometimes produced different word clouds. However, the differences weren't very big. This made me realize that even if tools are analyzing the same texts, the way they process or present the data can still vary. Both tools are helpful in their own ways, and it really depends on the user’s preference and familiarity with the tool.

Overall, this project made me realize that analyzing texts using digital tools is not as simple as I first thought. It requires both exploration and interpretation, not just relying on what the tools show.


## REFERENCES

Duffy, Lisa. “Transworld Travel in Postwar Animated Musicals.” Fantasy/Animation, 15 Jan. 2021, Transworld Travel in Postwar Animated Musicals

Underwood, Ted. “Appendix A: Data.” Distant Horizons: Digital Evidence and Literary Change, University of Chicago Press, 2019, pp. 174-184.
