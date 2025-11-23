---
title: "New York Citi Data Analysis"
layout: single
author_profile: true
sidebar:
  nav: "navigation"
excerpt: "Completed data scraping, NLP, network visualization, and text mining."
permalink: /projects/nyc-citi-bikes/
---

## Overview
For this project, the goal was to analyze user behavior to help the business strategy department assess the current logistics model of bike distribution across the city, while also identifying expansion opportunities.

## Skills Used
<ul>
<li>Configured GitHub workflows (clone, push/pull, SSH keys) and built Python virtual environments using Anaconda to manage dependencies.</li>
<li>Retrieved structured and unstructured data using APIs and performed ethical web scraping by reviewing site permissions and implementing scraping libraries.</li>
<li>Applied text mining techniques, ran NLP algorithms, generated network-analysis-ready dataframes, and built network graphs with iterative improvements.</li>
<li>Merged, cleaned, and transformed datasets using Python (including apply() and lambda functions) to prepare data for analytical workflows.</li>
<li>Created bar charts, line charts, seaborn plots, FacetGrids, and geospatial visualizations with kepler.gl; evaluated visualization quality and interpreted results.</li>
<li>Designed, built, and deployed dashboards using Plotly and Streamlit (including multi-page apps), applying design principles and presenting analytical findings.</li>
</ul>

## Key Findings
<ul>
<li>As the weather warms up, the number of trips increase, with June through October showing the highest ridership.</li>
<li>The most popular station is Grove St PATH, followed by South Waterfront Walkway and Hoboken Terminal.</li>
<li>Electric bikes and classic bikes have similar distributions for ridership and at bike stations.</li>
<li>Members have the highest ridership during weekdays.</li>
</ul>

## Visuals

![How does weather influence ridership patterns?](https://rebeccameyer11.github.io/rebeccameyer/assets/images/CB_Weather.png)

*Figure 1: There is a clear positive correlation between temperature and ridership — as the weather warms up, the number of trips increase.*

![What are the top 10 most popular bike stations?](https://rebeccameyer11.github.io/rebeccameyer/assets/images/CB_Top-10-Bike-Stations.png)

*Figure 2: The Grove St PATH station stands out as the most popular station, recording significantly higher trip counts compared to other stations.*

![How does ridership differ on weekdays vs weekends??](https://rebeccameyer11.github.io/rebeccameyer/assets/images/CB_Ride-Type.png)

*Figure 3: Member rides were highest during the weekday and weekend, but casual riders were more active during the weekdays.*

## Final Deliverable
- <a href="https://github.com/rebeccameyer11/Citi_Bikes_Analysis" target="_blank">GitHub Repo</a><br>
- <a href="https://citibikesanalysis-qrqgtuhpdxhdd9g5eplksq.streamlit.app/" target="_blank">Streamlit URL</a><br>
- <a href="https://vimeo.com/1135090471?share=copy&fl=sv&fe=ci" target="_blank">Vimeo Presentation</a><br>
