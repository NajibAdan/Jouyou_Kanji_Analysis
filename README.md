# Project: Investigating the Jouyou Kanji (常用漢字) 

## Introduction

The Jouyou kanji (literally regular use Chinese Characters) are a list of kanji characters and readings annouced officially by the Japanese Ministry of Education. Currently it's a list of 2,136 characters but it's not an exhaustive list of all the kanjis in regular use. It is intended as a literacy baseline for those who have completed compulsory education, as well as a list of permitted characters and readings for use in official government documents.

The dataset I used to investigate is from [kaggle](https://www.kaggle.com/datasets/anthaus/japanese-jy-kanji).  

## Structure Explanation
- `exploration.ipynb` contains my wrangling and exploration
- `explanatory.ipynb` is where I present my findings and insights

## Insights
- 50% of the jouyou kanji are taught in secondary grade
- 鬱 has the most number of strokes (29)
- Kanjis that were added in 2010 and 1981 were for the secondary grade
- Kanji with an old (kyuujitai) form have a minimum stroke number of 3 and a maximum stroke number of 20. Majority are in the 7-15 range with 11 having the most kanji. 
- The water radical (水) is the most common radical with 120 kanji. The radical 隶 had the least number of kanji.
- Only 121 kanji are similiar to it's radical (i.e where the kanji and radical are exactly the same)

## Recommendation
Maybe more insights could be found if we access to kanjis for the Kanji Kentei levels Pre-Level One and Level One.