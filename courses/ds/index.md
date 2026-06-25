---
layout: default
title: DS Seminar
---

# Data Science Seminar: Time Series Imputation

**Lecturer:** [Mourad Khayati](https://mkhayati.github.io)  
**Teaching Assistant:** Quentin Nater  
**Level:** Master (5 ECTS), Fall 2026  
**Location:** Fribourg
---


## Overview

The data science seminar involves presentations covering recent topics in data science. The area of this year’s seminar is **time series imputation**. As part of the seminar, we will study research papers that propose algorithms for imputing missing values. These papers present methods for reconstructing incomplete sensor data by applying various replacement strategies to estimate missing segments.

Imputation offers benefits on two levels. At the data processing level, the completed time series can be adequately utilized in a wide range of Machine Learning (ML) tasks, such as classification and forecasting. At the data management level, properly imputed time series can be more effectively stored and maintained, one reason why many Time Series Database Systems (TSDBs) have begun to incorporate native support for missing value imputation.

---

## Structure

The goal for the students is to learn how to critically read and study a research paper, describe it in a report, and present it in front of an audience. Under supervision, students will select one paper to study and compare it with related work. This seminar aims to help students gather in-depth knowledge of an advanced topic and develop the skills required to describe a complex problem from the time series field in the form of both a presentation and a written report.

Students will also learn how to integrate an algorithm into a library, benchmark it against other algorithms, and perform the required unit tests. For this purpose, we will use [ImputeGAP](https://imputegap.readthedocs.io), a comprehensive library designed for time series imputation analysis.

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

> Attendance at both seminar sessions is mandatory. Due to high demand, participation is limited to a maximum of 10 participants. Students interested in joining the seminar must submit a motivation letter outlining their academic background and explaining their reasons for selecting this seminar.

---

## Schedule

**Kickoff Meeting** 

Organization of the seminar: *Tue, 22.09.2026, 14:15–16:00* — Room TBA

**Introduction Seminar Material** 

Library introduction and paper assignment: *Tue, 29.09.2026, 14:15–16:00* — Room TBA

**First Presentation Session** 

Report deadline of Batch 1: *Tue, 10.11.2026*

Office meeting with students from Batch 1: *Tue, 17.11.2026 (all day)* — Room C433

Presentations of Batch 1: *Tue, 24.11.2026, 14:15–19:00* — Room TBA


**Second Presentation Session** 

Report deadline for Batch 2: Tue, 24.11.2026

Office meeting with students from Batch 2: *Tue, 01.12.2026 (all day)* — Room C433

Presentations of Batch 2: *Tue, 08.12.2026, 14:15–19:00* — TBA


**Final Deliverables**

Final Report: *Tue, 12.01.2027*

Code Inspection: *Tue, 19.01.2027 (all day)* — Room C433



---

## Paper Assignment

Papers are distributed on a first-come, first-served basis.

| Presenter     	  		| Date       | Paper  	|
| --------      	  		| --------   | -------- |
|  		| 25.11.2025 | SAITS: Self-attention-based imputation for time series, ESWA’23 |
| 	    | 25.11.2025 | Missing Value Imputation on Multidimensional Time Series, VLDB’21 |
| 	    | 25.11.2025 | BayOTIDE: Bayesian Online Multivariate Time Series Imputation with Functional Decomposition, ICML’24 |
|  		| 25.11.2025 | Biased Temporal Convolution Graph Network for Time Series Forecasting with Missing Values, ICLR’24 |
| 	    | 25.11.2025 | NuwaTS: a Foundation Model Mending Every Incomplete Time Series, arXiv’24 |
| 	    | 25.11.2025 | Filling the Gaps: Multivariate Time Series Imputation by Graph Neural Networks, ICLR’22  |
| 	    | 09.12.2025 | CSDI: Conditional Score-based Diffusion Models for Probabilistic Time Series Imputation, NeurIPS’21 |
| 		| 09.12.2025 | ReCTSi: Resource-efficient Correlated Time Series Imputation via Decoupled Pattern Learning and Completeness-aware Attentions, KDD'24  |
| 	    | 09.12.2025 | GP-VAE: Deep probabilistic time series imputation, AISTATS’20 |
| 	    | 09.12.2025 | Networked Time Series Imputation via Position-aware Graph Enhanced VAEs, KDD’23 |
| 	    | 09.12.2025 | Mining of Switching Sparse Networks for Missing Value Imputation, KDD’24 |
| 	    | 09.12.2025 | TimesNet: Temporal 2D-Variation Modeling for General Time Series Analysis, ICLR'23 |
| 	    | 09.12.2025 | TimesNet: Temporal 2D-Variation Modeling for General Time Series Analysis, ICLR'23 |



