---
title: "Assignment 2"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - Assignment

---
# Manual Geocoding vs Automated Geocoding [Ready for Grading]

## Introduction

Southern Arabia is written by Theodore Bent and Mabel Bent. They both traveled multiple times across the region, including parts of Bahrain, Oman, and the Hadhramaut region in Yemen. Through these journeys, they gathered information, observations, and stories about Southern Arabia and later turned them into a book. Southern Arabia was first published in 1900, after Theodore’s death. The book reflects their experiences while traveling and documenting the places they encountered.

For this assignment, I created a map based on the places mentioned in the text using both Recogito and PositCloud. Many of the locations in the book were mentioned without much explanation or exact information about where they are located. Some places were only briefly mentioned in passing, while others were described through nearby landmarks instead of clear coordinates or modern place names. Because of this, it can sometimes be difficult for readers to fully understand or imagine the places being described in the text. By annotating and geocoding these locations, I was able to connect the text to real places on a map, making the work easier to follow and understand. Seeing the places visually on a map made the journey in the book feel more real and easier to trace. Instead of just reading about unfamiliar names, I could actually follow the movement of the travelers across different regions.

## Manual Geocoding

Using Recogito to annotate and manually geocode a long passage took me a lot of time. I had to check each location one by one. I had to search for place names, compare them with maps or other references, and make sure the locations matched the context of the text. At first, the process felt tiring, especially when some places were difficult to identify and really needed time to search for. As I kept going, I saw that manual geocoding made me focus more on the text. I became more aware of how the authors described places, landmarks, routes, and nearby regions during their travels. It almost felt like reconstructing their journey step by step instead of simply tagging locations on a map.

<figure style="text-align: center;">
    <img src="/DAAH_Spring26/assets/images/AutomatedGeocoding.png" style="width: 100%;">
    <figcaption>Automated geocoding result from Recogito</figcaption>
  </figure>

One of the most difficult parts of manual geocoding was identifying historical place names. Because it was written during the late 19th century, a lot of the places in Southern Arabia are very different from what we use today. They are either rarely used now or have different spellings compared to their modern versions. There were moments when I searched a place directly in Recogito, Wikipedia, or Google Maps, and nothing appeared because the name had changed over time. Sometimes the spelling used in the text reflected older English transliterations of Arabic names, which made searching even more difficult. Because of this, I had to try different spellings, search for similar pronunciations, and sometimes even research the historical background of a place to determine whether it matched the location being referred to in the text. I also had to rely heavily on context clues from the passage itself. I would look at the locations mentioned before and after the place, study the route of travel, and compare nearby regions in order to make a more informed guess. This process taught me that manual geocoding requires more interpretation than I thought. It is not just about putting points on a map, but also about understanding the narrative and historical context of the text itself.

<div style="display: flex; gap: 20px; justify-content: center;">

<figure style="text-align: center;">
    <img src="/DAAH_Spring26/assets/images/identifying_names.png" style="width: 100%;">
    <figcaption>Examples of places that have different names in the text and in open street maps</figcaption>
  </figure>

</div>

## Automated Geocoding

Aside from using Recogito for manual annotation and geocoding, I also explored automated geocoding using Posit Cloud with the files provided to us that were connected to the same text. Automated geocoding was much faster and did not even take 20 minutes to produce results. The machine was able to quickly identify possible place names and connect them to coordinates through databases and algorithms. This made me understand why automated tools are very useful for large datasets and digital humanities projects that involve huge amounts of textual information.

<iframe src="https://jamayccaaa.github.io/SouthernArabia/" width="100%" height="500"></iframe>

One thing I noticed in the automatically geocoded map was that multiple place names were sometimes grouped into a single coordinate. In one case, many unrelated locations from Southern Arabia were assigned to the same point in Colombia, even though the text mainly discusses regions around the Arabian Peninsula. This shows how automated geocoding systems can incorrectly match locations when relying mostly on databases and name recognition instead of contextual understanding.

<div style="display: flex; gap: 20px; justify-content: center;">

<figure style="text-align: center;">
    <img src="/DAAH_Spring26/assets/images/columbia.png" style="width: 100%;">
    <figcaption> Multiple placenames in one point/place </figcaption>
  </figure>

</div>

## Comparing the two

When I compared the two maps, I noticed clear differences in how the data was presented. The manually geocoded map looked more accurate and detailed because each location was carefully checked one by one. The points and circles felt more connected to the actual places being described in the text, which also made the results feel more connected to the journey and narrative itself. Since I manually reviewed the locations, I was able to use context clues, nearby landmarks, and the flow of the journey to decide where places should be placed on the map. At the same time, I also noticed that there were fewer points and circles on the manually geocoded map. This is probably because there were some places that I was unable to identify or confidently locate while annotating the text manually. Some locations were too vague, historical, or difficult to search, so I had to leave them out to avoid placing them incorrectly.

Compared to this, the automatically geocoded map from PositCloud was much faster to generate and included more points on the map. However, some places were grouped too generally or placed incorrectly. There were cases where the system connected a place name to the wrong location simply because another place with a similar name existed in its database. Some place names were also connected to modern locations that were geographically far from the Hadhramaut region, even though the surrounding text clearly suggested a different location. In some instances, multiple place names were grouped into one point even if they referred to different places in the text.

I also noticed that the mismatches between manual and automated geocoding were not completely random. Many of the mistakes followed similar patterns. Historical names, vague references, and uncommon spellings created the most errors in the automatically generated dataset. In both Recogito and PositCloud, the system often suggested places with similar spellings even if those locations were far from the actual region mentioned in the text. Looking at both maps side by side made me realize how differently humans and machines “read” a text. Humans understand context, nearby locations, and the relationships between places, while machines mostly rely on matching words to database entries and algorithms.

## Reflection

With this assignment, it made me realize one major difference between human and machine approaches. Humans understand context more naturally. While manually geocoding, I was able to recognize spelling differences, historical references, and connections between nearby locations. Even when a place was unclear, I could still judge it better, I focused on the journey's flow and the details in the text. Machines, however, do not really “understand” the story being told. They identify patterns, compare names with databases, and generate matches based on probability. Because of this, automated systems can struggle with ambiguity, especially in historical texts where names may have changed over time.

Another thing I realized during this assignment is that manual geocoding feels more personal and interpretive, while automated geocoding focuses more on speed and efficiency.Manual work takes more time, but it made me pay closer attention to the material. Each spot demands attention and thoughtful decisions. I became more familiar with the region's geography because I needed to research each place carefully. Automatic geocoding, meanwhile, is much faster and more practical when working with large amounts of data. However, speed does not always mean accuracy. Some of the automatically generated points still needed to be checked manually to confirm whether they were correct.


## Conclusion

Before this activity, I mostly viewed mapping tools as systems that automatically provide correct answers. But after comparing manual and automated geocoding, I realized that technology still depends heavily on the quality of the data and the context it is given. Historical texts are especially difficult because place names, languages, and borders change over time. A machine can process information quickly, but it cannot fully understand historical nuance in the same way humans can. However, this made me appreciate the value of combining both methods together. Automated geocoding can quickly generate initial results and process large amounts of information, while human interpretation can improve accuracy and provide a deeper understanding of the text and locations. Instead of replacing humans, automated systems work better as tools that assist researchers.

Comparing both methods, I think manual geocoding is more reliable when it comes to understanding context and making careful decisions, especially for historical texts like Southern Arabia. However, automatic geocoding is much more time efficient and practical for large-scale projects. With today’s technology and better digital tools, automatic geocoding can really help make research faster and easier. At the same time, human checking is still necessary because machines can make mistakes or misunderstand unclear place names. In the end, I think the best approach is to use both together. 

## Links
[Recogito](https://recogito.pelagios.org/document/3tc6koyke3yj62 )
[PositCloud HTML](https://147ebb8ff69a4d55b788ba409e4a7465.app.posit.cloud/file_show?path=%2Fcloud%2Fproject%2FvisualizingSouthernArabia.html)

# READY FOR GRADING