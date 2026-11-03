---
layout: default
title: DS Seminar
---

# Data Science Seminar: Time Series Imputation

**Lecturer:** [Dr. Mourad Khayati](https://mkhayati.github.io)  
**Teaching Assistant:** Quentin Nater  
**Level:** Master (5 ECTS), Fall 2026  
**Location:** Fribourg

---

## Overview

The Data Science seminar consists of presentations on recent research topics in data science. This year’s seminar focuses on time series imputation, i.e., the problem of reconstructing missing values in sensor data. Participants will study research papers that propose imputation algorithms for incomplete time serie data, where missing values typically occur as contiguous blocks caused by sensor failures, transmission errors, or irregular sampling. The algorithms covered span several families: statistical methods (e.g., interpolation and regression-based techniques), matrix completion and low-rank decomposition methods, pattern-based search, and deep learning models (e.g., recurrent, generative, and attention-based architectures). These techniques reconstruct missing segments by exploiting the temporal dependencies within a series and the correlations across series.

Imputation matters at two levels. At the data processing level, it produces complete time series that downstream Machine Learning (ML) tasks such as classification and forecasting require as input, since most models cannot handle missing values natively and naive strategies like deletion or mean substitution introduce bias and distort temporal structure. At the data management level, accurately imputed time series support more efficient storage, compression, indexing, and query processing. For this reason, a growing number of Time Series Database Systems (TSDBs) provide built-in operators for gap filling and missing value imputation.

---

## Structure

The goal for the students is to learn how to critically read and study a research paper, describe it in a report, and present it in front of an audience. Under supervision, students will select one paper to study and compare it with related work. This seminar aims to help students gather in-depth knowledge of an advanced topic and develop the skills required to describe a complex problem from the time series field in the form of both a presentation and a written report.

Students will also learn how to integrate an algorithm into a library, benchmark it against other algorithms, and perform the required unit tests. For this purpose, we will use [ImputeGAP](https://imputegap.readthedocs.io), a comprehensive library designed for time series imputation analysis.

---

## Relying on AI Summaries

One of the core tasks of this seminar is describing a research paper in a report: students are asked to read a research paper, summarize it, and assess its strengths and weaknesses. The summary, however, is not the main outcome. The real challenge and learning happen along the way: making sense of unfamiliar notation and missing background, rereading sections that did not click the first time, spotting possible errors, and asking whether the paper’s arguments actually hold up. This is why it is highly recommended to not to outsource the task to AI. You might still end up with a decent summary, but you would skip the part that matters: forming your own judgments about research and having them challenged in discussion. That is how you learn to read critically and evaluate research on your own.

For a deeper discussion of why you need to be careful when using AI in seminars like ours, please read this [memo](https://amolvdeshpande.github.io/cmsc724-fall2026/note_on_ai_use.html).


---

## Evaluation and Expectations

The final grade depends on the quality of the report, presentation, integration quality, and active participation during the seminar. Each participant prepares a self-contained report of at least five pages and gives a presentation of 30 minutes. The report should:

* Describe the proposed algorithm in detail
* Include small running examples or counterexamples
* Explore extreme cases where the algorithm performs best and worst

Reproducibility consists of reproducing the same set of experiments introduced in the paper using a different setup (dataset, metric, parameters, etc.).

**Advice on how to:**

* Write the [report](https://cs.stanford.edu/~rishig/courses/ref/paper-reading-technical.pdf)
* Prepare the [presentation](http://www.matt.might.net/articles/academic-presentation-tips/)

> Attendance at both seminar sessions is mandatory. Due to high demand, participation is limited to a maximum of 10 participants. Students interested in joining the seminar must submit a motivation letter outlining their academic background and explaining their reasons for selecting this seminar. The letter needs to be sent by September 27 to: [mourad.khayati@unifr.ch](mailto:mourad.khayati@unifr.ch). 

---

## Schedule

**Kickoff Meeting** 

Organization of the seminar: *Tue, 22.09.2026, 14:15–16:00* — Room D230

**Introduction Seminar Material** 

Library introduction and paper assignment: *Tue, 29.09.2026, 14:15–16:00* — Room D230

**First Presentation Session** 

Report deadline of Batch 1: *Tue, 10.11.2026*

Office meeting with students from Batch 1: *Tue, 17.11.2026* — Room C433

Presentations of Batch 1: *Tue, 24.11.2026, 14:15–18:00* — Room D230


**Second Presentation Session** 

Report deadline for Batch 2: Tue, 24.11.2026

Office meeting with students from Batch 2: *Tue, 01.12.2026* — Room C433

Presentations of Batch 2: *Tue, 15.12.2026, 14:15–18:00* — Room  E040

**Final Deliverables**

Final Report: *Tue, 12.01.2027*

Code Inspection: *Tue, 19.01.2027* — Room C433

---

## Paper Assignment

Papers are distributed on a first-come, first-served basis.

<style>
  .paper-table table { border-collapse: collapse; width: 100%; }
  .paper-table th, .paper-table td { border: 1px solid #ccc; padding: 6px 10px; }
  .paper-table thead th { border-bottom: 2px solid #555; }
  /* thicker line between Batch 1 and Batch 2 */
  .paper-table tbody tr:nth-child(5) td { border-bottom: 3px solid #555; }
</style>

<div class="paper-table" markdown="1">


| Presenter     	  		| Date       | Paper  	|
| --------      	  		| --------   | -------- |
| Milena Kovatsch 	| 24.11.2026 | Naomi: Non-autoregressive multiresolution sequence imputation, NeurIPS 2019 |
| Zejun Yan 	| 24.11.2026 | Multivariate Time Series Imputation With Transformers, SPL 2022 |
| Maria Larsen 	| 24.11.2026 | ImputeINR: Time Series Imputation via Implicit Neural Representations for Disease Diagnosis with Missing Data, IJCAI 2025 |
| Vincent Adam 	| 24.11.2026 | Filling the Missings: Spatiotemporal Data Imputation by Conditional Diffusion, IJCAI 2025 |
| Louis Gérard 	| 24.11.2026 | Diffusion-based Time Series Imputation and Forecasting with Structured State Space Models, TMLR 2023 |
| Silvan Spiess 	| 15.12.2026 | Self-attention-based Diffusion Model for Time-series Imputation in Partial Blackout Scenarios, AAAI 2025 |
| Eva Bauer 	| 15.12.2026 | Gp-vae: Deep probabilistic time series imputation, AISTATS 2020 |
| Kacper Jozwiak 	| 15.12.2026 | Generative Semi-supervised Learning for Multivariate Time Series Imputation, AAAI 2021 |
| Yen Hoang Nguyen 	| 15.12.2026 | ReCTSi: Resource-efficient Correlated Time Series Imputation via Decoupled Pattern Learning and Completeness-aware Attentions, KDD 2024 |
| Willi Urban 	| 15.12.2026 | Investigating a Model-Agnostic and Imputation-Free Approach for Irregularly-Sampled Multivariate Time-Series Modeling, TMLR 2026 |


</div>




