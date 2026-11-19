# JOUR 701 — Final Project: Datasets and Colab

**Assignment 5:** December 3 — in-person analysis-plan consultation (10%).  
**Assignment 6:** December 8 — final stakeholder presentation (30%).

All datasets below are **synthetic, fictional instructional data**. They do not describe actual participants, publications, or businesses. One row represents the unit stated in each group description. Each dataset includes numeric, categorical, and open-ended text columns.

## Get started

1. Find your group below and **download your CSV**.
2. Click **Open in Google Colab** for your group's starter notebook. It should open as an interactive notebook with text and code cells—not as a page of JSON.
3. In Colab, select **File → Save a copy in Drive** and work in your own copy.
4. Run the notebook's first code cell. When prompted, upload the CSV you downloaded in Step 1.
5. Review our Block 3 lecture slides and Colab examples. Adapt the methods to *your* variables; you do not need to write Python from memory.
6. Save your progress and be ready to show your work during the December 3 consultation.

## Group files

| Group and context | Dataset | Starter Colab notebook | Study type / rows |
|---|---|---|---|
| **1. Journalism and News Engagement** | [Download CSV](assets/data/group01_news_engagement.csv) | [Open in Google Colab](https://colab.research.google.com/github/KayChansiri/Course_research-methods-in-the-age-of-ai/blob/main/docs/labs/assets/notebooks/group01_starter.ipynb) | Observational content analysis of fictional news stories (187 rows) |
| **2. Sports Broadcasting and Gambling Content** | [Download CSV](assets/data/group02_sports_gambling.csv) | [Open in Google Colab](https://colab.research.google.com/github/KayChansiri/Course_research-methods-in-the-age-of-ai/blob/main/docs/labs/assets/notebooks/group02_starter.ipynb) | Simulated randomized two-condition viewing experiment (203 rows) |
| **3. Advertising and Consumer Behavior** | [Download CSV](assets/data/group03_graduation_photographer.csv) | [Open in Google Colab](https://colab.research.google.com/github/KayChansiri/Course_research-methods-in-the-age-of-ai/blob/main/docs/labs/assets/notebooks/group03_starter.ipynb) | Simulated cross-sectional survey of fictional USC students making a hypothetical photographer choice (176 rows) |
| **4. Social Media and Audience Engagement** | [Download CSV](assets/data/group04_ai_social_content.csv) | [Open in Google Colab](https://colab.research.google.com/github/KayChansiri/Course_research-methods-in-the-age-of-ai/blob/main/docs/labs/assets/notebooks/group04_starter.ipynb) | Simulated randomized two-condition experiment (192 rows) |
| **5. Social Media and Journalism** | [Download CSV](assets/data/group05_tiktok_news.csv) | [Open in Google Colab](https://colab.research.google.com/github/KayChansiri/Course_research-methods-in-the-age-of-ai/blob/main/docs/labs/assets/notebooks/group05_starter.ipynb) | Simulated randomized two-condition news-format experiment (217 rows) |
| **6. Advertising and Consumer Trust** | [Download CSV](assets/data/group06_influencer_advertising.csv) | [Open in Google Colab](https://colab.research.google.com/github/KayChansiri/Course_research-methods-in-the-age-of-ai/blob/main/docs/labs/assets/notebooks/group06_starter.ipynb) | Simulated randomized two-condition advertising experiment (231 rows) |

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
