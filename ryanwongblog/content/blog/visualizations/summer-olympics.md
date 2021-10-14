---
title: "Summer Olympics"
description: "Data exploration and visualizations with summer olympics data."
image: "images/post/summer_olympics/preview.jpg"
date: 2021-10-13
draft: false
author: "Ryan Wong"
tags: ["Visualization", "Python", "Web Scraping"]
categories: ["Visualization"]
---

This post seeks to explore and visualize trends with summer olympics data.
&nbsp;
[Link to Github Repository](https://github.com/ryanwonghc/summer-olympics-viz)

#### 1. What proportion of the years gold medals did the winning country win?
<p align="center">
  <img src="/images/post/summer_olympics/proportion_gold_winner.jpg"/>
</p>
Apart from 1904 which was a huge outlier (USA won 78% of the available gold medals), the winner of each olympics typically win about 20-40% of the available gold medals (mean: 26.76%). There is a slight downward trend in the proportion of gold medals won by the winning country which suggests that the competition to win gold medals is becoming more and more intense. 

&nbsp;
&nbsp;

To dive deeper into causes of USA dominance in 1904:
&nbsp;
There were only 12 nations competing in the 1904 olympics. Furthermore, the US had 5x more athletes than all the other nations combined (523 of the 630 athletes represented the US).
&nbsp;

**Why did so few countries countries send athletes to the olympics?**
&nbsp;
&nbsp;
This was only the third modern olympics, so there were not too many countries participating/invited to begin with (21 nations participated in the prior Olympics). This was also the first olympics hosted out of Europe (most countries participating in the early olympics were European countries), and St. Louis was a less than ideal location to host it (it was originally planned for Chicago; previous host cities were Athens and Paris), further contributing to the low number of visiting countries.

#### 2. What proportion of the years gold medals did the top 3 countries win relative to each other and the rest of the competition?
<p align="center">
  <img src="/images/post/summer_olympics/proportion_gold_top3.jpg"/>
</p>

Throughout the course of the olympics, on average, the top 3 nations win more medals than the rest of the competition combined. This data however is skewed by the earlier years of the competition where the winners were often much more dominant than the rest of the competition. If we only look at data from the last 10 olympics, we see that the top 3 nations win ~40% of the gold medals.

<p align="center">
  <img src="/images/post/summer_olympics/proportion_gold_top3_last10.jpg"/>
</p>

Looking at the number of medals won (gold, silver, bronze) we see the other countries make up an event larger proportion of the total.

<p align="center">
  <img src="/images/post/summer_olympics/proportion_medals_top3_last10.jpg"/>
</p>

#### Further Exploration
This article will be continuously updated with new content. In the future, I would like to test the following hypotheses:
- The more economically developed a country is, the higher the probability of them being competitive in the olympics (winning more medals)
    - people in economically developed countries have greater freedom to pursue and focus on sport. They also have more resources to train with. Economically developed countries can send more athletes to the games (more athletes qualify) and the athletes have bigger odds of winning their event.
- The host country performs better at each olympics
    - The host country can add sports to the list of events, and they can add events that they are good at
    - The home country's athletes will generally have the most supporters cheering for them at each event (harder for people to travel to support their country)


