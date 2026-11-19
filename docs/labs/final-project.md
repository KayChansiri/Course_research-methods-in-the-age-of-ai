---
layout: page
title: Final Project — Datasets and Colab
permalink: /final-project/
---

# JOUR 701 — Final Project: Datasets and Colab

**Assignment 5:** December 3 — in-person analysis-plan consultation (10%).  
**Assignment 6:** December 8 — final stakeholder presentation (30%).

All datasets below are **synthetic, fictional instructional data**. They do not describe actual participants, publications, or businesses. One row represents the unit stated in each group description. Each includes numeric, categorical, and open-ended text columns.

## Get started

1. Find your group below and download **your CSV** and **starter Colab notebook**.
2. Open [Google Colab](https://colab.research.google.com/), choose **Upload**, and select the `.ipynb` notebook.
3. In Colab, run the notebook’s first code cell and upload the downloaded `.csv` when prompted.
4. Make a copy in your Google Drive: **File → Save a copy in Drive**. Work in that copy.
5. Review our Block 3 lecture slides and Colab examples. Adapt the methods to *your* variables; you do not need to write Python from memory.
6. Save your notebook and be ready to show your work during the December 3 consultation.

## Group files

| Group and context | Data | Colab notebook | Study type / rows |
|---|---|---|---|
| **1. Journalism and News Engagement** | [Download CSV]({{ '/assets/data/group01_news_engagement.csv' | relative_url }}) | [Download starter notebook]({{ '/assets/notebooks/group01_starter.ipynb' | relative_url }}) | Observational content analysis of fictional news stories (187 rows) |
| **2. Sports Broadcasting and Gambling Content** | [Download CSV]({{ '/assets/data/group02_sports_gambling.csv' | relative_url }}) | [Download starter notebook]({{ '/assets/notebooks/group02_starter.ipynb' | relative_url }}) | Simulated randomized two-condition viewing experiment (203 rows) |
| **3. Advertising and Consumer Behavior** | [Download CSV]({{ '/assets/data/group03_graduation_photographer.csv' | relative_url }}) | [Download starter notebook]({{ '/assets/notebooks/group03_starter.ipynb' | relative_url }}) | Simulated cross-sectional survey of fictional USC students making a hypothetical photographer choice (176 rows) |
| **4. Social Media and Audience Engagement** | [Download CSV]({{ '/assets/data/group04_ai_social_content.csv' | relative_url }}) | [Download starter notebook]({{ '/assets/notebooks/group04_starter.ipynb' | relative_url }}) | Simulated randomized two-condition experiment (192 rows) |
| **5. Social Media and Journalism** | [Download CSV]({{ '/assets/data/group05_tiktok_news.csv' | relative_url }}) | [Download starter notebook]({{ '/assets/notebooks/group05_starter.ipynb' | relative_url }}) | Simulated randomized two-condition news-format experiment (217 rows) |
| **6. Advertising and Consumer Trust** | [Download CSV]({{ '/assets/data/group06_influencer_advertising.csv' | relative_url }}) | [Download starter notebook]({{ '/assets/notebooks/group06_starter.ipynb' | relative_url }}) | Simulated randomized two-condition advertising experiment (231 rows) |

## What you must do

**Assignment 5: December 3** — Explain your research question, primary X and Y, their variable types, the method you plan to use, the reasoning behind it, and your cleaning/analysis plan. Show progress in your Colab notebook. You do **not** need final significant results or a separate written report.

**Assignment 6: December 8** — Present your completed analysis and interpretation to a stakeholder audience in 8–10 minutes, followed by discussion. Show relevant Colab code and key outputs, a clear visualization, limitations, and how you checked any AI assistance. The syllabus does not require a separate notebook submission.

## Use AI as a tutor, not a substitute for judgment

If stuck, copy and adapt one of these prompts. **Do not paste the whole CSV into an AI chat.** Describe the columns or share a few fictional example rows.

**Understand the data**

> I am using a fictional JOUR 701 dataset. My question is: [question]. My columns include [names and types]. Help me identify X, Y, their types, and one statistical test from correlation, t-test, regression, ANOVA, or chi-square. Explain why, but do not write my full analysis.

**Inspect and clean**

> In Google Colab, my DataFrame is named `raw`. I need to check missing values and inconsistent spaces in category labels. Give me short pandas code for *one step at a time* and explain what each line does. I will decide how to handle missing data.

**Adapt lecture code**

> In class, we used [paste the relevant code excerpt]. My dataset uses X=`[column]` and Y=`[column]`. Show me the smallest necessary changes and explain them. Please avoid introducing methods we have not learned.

**Debug and interpret**

> My code [paste short code] gives this error/output [paste text]. Explain the likely cause and a minimal correction. Help me interpret the result without claiming causation that my study design does not support.

**Your responsibility:** Run the code yourself, check the output, explain your decisions, and acknowledge AI assistance when required. A significant p-value is not the goal.

## Scope

Choose **one primary statistical analysis** and provide a clear interpretation. A simple chart is expected. Your group can explore the open-ended text using Week 14 methods if useful, but text analysis is **optional**. Do not add advanced models, causal claims from surveys, or analyses not covered in class.
