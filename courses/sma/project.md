---
layout: default
title: SMA Course
---

# Social Media Analytics Project

---
## Overview

In teams of 4 students, you will develop a tool to run analytics on large social networks. You will build upon 
the the different algorithms introduced during the semester and/or other external sources. Examples of such analytics from recent projects include Reconstructing Neural Connectivity, Influence Analysis in Social Botnets, Spotify Artists Featuring Analysis, Collaborative Filtering on Yelp, Predicting Affluence in Montreal Bike Sharing, Community Detection Within
the Swiss Train Network, Unveiling Polarization and Sentiment Analysis on Reddit Discussions, Reddit Cryptocurrency Comments Analysis.  The tool should integrate the full pipeline of social data analysis from data collection and curation to data management. Your project needs to comply with the pipeline described in Figure 1.


> Each team should ideally contain four members. Exceptions need to be discussed with the lecturers.  

---
## Project Components

### Network Analytics

Network analytics helps uncover insights and patterns in networks. In this course, you will learn algorithms applicable to real-world problems, such as community detection, information diffusion for marketing and influencer strategies, graph mining to detect unusual or malicious behavior, and recommendation systems tailored to individual interests.

The main task here is to implement a network analytics algorithm to uncover interesting patterns
and reveal key properties of a network’s behavior. You are encouraged to select from a wide range
of algorithms you will study throughout the course, e.g., community detection, social mining, social
recommendation, information diffusion, etc. The syllabus of the course can be useful in this regard.
You can also implement a new interesting network analytics task, not covered in the course, that you
deem relevant as a project idea (e.g., sentiment analysis, truth inference, etc.).

### Network Loading


Social networks capture data about entities, locations, dates, interactions, and more. This data can be obtained from various sources, including Snap, Network Repository, AMiner, Recommendation Repository, Gephi datasets, Newman networks, LibRec datasets, and Kaggle.
Your task is to choose a network source suitable for your analysis and load it into your tool. Ensure the network size matches your analysis needs, a very large network may be rich in information but slow to analyze, while a very small network allows faster analysis but may limit result quality.

### Network Exploration


Exploring interactions between nodes can reveal hidden patterns. Network measures help analyze these interactions to understand structural properties and node similarities. When choosing an exploration method, consider two factors: it should align with your analysis goals, e.g., centrality or similarity measures can reveal node influence and relationships—and it should be computationally feasible. For large networks, you may use a smaller simulated graph that preserves the original network’s properties.

Your task is to implement network measure algorithms to explore the network and uncover insights. Select measures suited to your analysis, and consider using a scaled-down graph if needed.

### Network Visualization

Visualization tools help uncover and communicate patterns in network data. Effective visualizations highlight key findings by plotting data distributions, combining multiple analytical dimensions, or displaying algorithm outputs, such as discovered communities or information flow—to reveal hidden relationships and assess results.

Your task is to use visualization tools to explore your network, clarify your analysis, and emphasize the insights you want to present.

---

### Evaluation Criteria
* Originality of your project
* Fulfillment of the general architecture
* Quality of your code (structure, design, consistency, scalabilty, correctness, etc)
* Working demo of your tool
* Quality of the report. Analysis of the efficiency, effectiveness, and the correctness of the implementations.

> The members of the groups will be graded individually

## Timeline

Date | Task
--- | ---
06.03.2026 | **Deadline for submission**: team members & project idea
10.03.2026 | Project plan presentations
24.03.2026 | `Check point 1` v1 demo (during exercise)
05.05.2026 | `Check point 2` v2 demo (during exercise)
22.05.2026 | `**Deadline for submission**: report and code 
26.15.2026 | Final presentations (during the course)

---

*The submission of artifacts should be on ILIAS.*