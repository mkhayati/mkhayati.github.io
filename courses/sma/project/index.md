---
layout: default
title: SMA Course
---

# Social Media Analytics Project

---
## Overview

In teams of 4 students, you will develop a tool to run analytics on large social networks. You will build upon the different algorithms introduced in the course and/or other external sources. Examples of such analytics from recent projects include Reconstructing Neural Connectivity, Influence Analysis in Social Botnets, Spotify Artists Featuring Analysis, Collaborative Filtering on Yelp, Predicting Affluence in Montreal Bike Sharing, Community Detection Within
the Swiss Train Network, Unveiling Polarization and Sentiment Analysis on Reddit Discussions, Reddit Cryptocurrency Comments Analysis.  The tool should integrate the full pipeline of social data analysis from data collection and curation to data management. 

> Each team should ideally contain four members. Exceptions need to be discussed with the lecturer.  

---

## Architecture
Your application should have a similar architecture:
![architecture](https://mkhayati.github.io/courses/sma/project/sma_architecture.png)


---
## Project Components

### Network Loading

Social networks capture data about entities, locations, dates, interactions, and more. This data can be obtained from various sources, including Snap, Network Repository, AMiner, Recommendation Repository, Gephi datasets, Newman networks, LibRec datasets, and Kaggle.

Your task is to choose a network source suitable for your analysis and load it into your tool. Ensure the network size matches your analysis needs, a very large network may be rich in information but slow to analyze, while a very small network allows faster analysis but may limit result quality.


### Network Visualization

Visualization tools help uncover and communicate patterns in network data. Effective visualizations highlight key findings by plotting data distributions, combining multiple analytical dimensions, or displaying algorithm outputs, such as discovered communities or information flow, to reveal hidden relationships and assess results.

Your task is to use visualization tools to explore your network, clarify your analysis, and emphasize the insights you want to present.


### Network Analytics

Network analytics helps uncover insights and patterns in networks. In this course, you will learn algorithms applicable to real-world problems, such as community detection, information diffusion for marketing and influencer strategies, graph mining to detect unusual or malicious behavior, and recommendation systems tailored to individual interests.

The main task here is to implement a network analytics algorithm to uncover interesting patterns
and reveal key properties of a network’s behavior. You are encouraged to select from a wide range
of algorithms you will study throughout the course, e.g., community detection, social mining, social
recommendation, graph completion, information diffusion, etc. The syllabus of the course can be useful in this regard.
You can also implement a new interesting analytics task, not covered in the course, that you
deem relevant as a project idea (e.g., sentiment analysis, truth inference, etc.).


### Network Exploration


Exploring interactions between nodes can reveal hidden patterns. Network measures help analyze these interactions to understand structural properties and node similarities. When choosing an exploration method, consider two factors: it should align with your analysis goals, e.g., centrality or similarity measures can reveal node influence and relationships, and it should be computationally feasible. For large networks, you may use a smaller simulated graph that preserves the original network’s properties.

Your task is to implement network measure algorithms to explore the network and uncover insights. Select measures suited to your analysis, and consider using a scaled-down graph if needed.

---

## Evaluation Criteria
* Originality of your project
* Fulfillment of the architecture
* Quality of your code 
* Working demo of your tool
* Quality of the report
* Final grade: demo 1 (20%) + demo 2 (20%) + final presentation & report (60%) 

> The members of the groups will be graded individually

---

## Timeline

Date | Task
--- | ---
04.03.2026 | `Deadline for submission`: group formation & project idea
05.03.2026 | Placement test results announcement
10.03.2026 | Project plan presentations (during the lecture)
24.03.2026 | `Check point`: v1 demo (during exercise)
05.05.2026 | `Check point`: v2 demo (during exercise)
22.05.2026 | `Deadline for submission`: report and code 
26.05.2026 | Final presentations (during the lecture)

---

*The submission of artifacts should be on ILIAS.*