---
layout: archive
title: "Data"
permalink: /data/
author_profile: true
---

{% include base_path %}

<a href="https://stockjumpswebsite.github.io/stockjumps/files/BBDS_BigJumps_July2019.pdf" target="_blank">Read Our Paper</a> | <a href="https://docs.google.com/spreadsheets/d/1BtWwJ-DSvbxsfPoDShWBvEgVbbt65C1g5qiDQST4Sic/edit#gid=1174245246" target="_blank">View Our Data</a> | <a href="https://stockjumpswebsite.github.io/stockjumps/files/slidespdf.pdf" target="_blank">View Our Slides</a> | <a href="https://www.dropbox.com/s/sgq7t10c6dboiwc/WSJ_final.zip?dl=0">Download Articles (zip)</a>


<b>Broad Approach.</b> We train human analysts to read each newspaper article, and classify it into one of 16 categories.

Training coders: Before analysts started coding, they carefully read the audit guide <a href="https://stockjumpswebsite.github.io/stockjumps/files/coding_guide_pdf.pdf" target="_blank">Read Our Paper</a>, underwent a half-day training session and then coded 50 WSJ training articles. These WSJ training articles had already been coded up by us, enabling us to ensure our auditors were accurately coding (and to address any issues) before they coded the research sample.

Finding articles: For each newspaper and each day with a market move of more than 2.5%, human readers search the newspaper’s archive for relevant articles published the following day. The readers search the archive on a given date for articles the mention phrases like ‘stock market’, ‘wall street’, ‘S&P’, or ‘Dow Jones’.

Coding Articles: Readers are assigned to carefully review each article and categorize the article’s attribution of the cause of the stock market movement on the previous day based on the instructions in the audit guide <a href="https://stockjumpswebsite.github.io/stockjumps/files/coding_guide_pdf.pdf" target="_blank">.

<b>Data Fields</b>

Return: From 1926-present, this is the percent change in the CRSP Value-Weighted index.  Before 1926, this is the percent change in Global Financial Data’s DOW Extension.

Coder: Unique identifier for each analyst coding articles.

Primary/Secondary: Causes that are emphasized in the title or sub-title of the article are given more weight, as are causes that are specifically noted to be the primary driver of the day’s large movements. If an article mentions multiple causes but does not clearly denote a primary cause, the readers utilize the order in which the reasons are mentioned or discussed in the article as a tie breaker. 

Ease of Coding: How difficult it was to assign a primary cause to the market movement. The score ranges from 3 (Easy to code) for articles that rapidly and clearly identify the cause of the jumps to 1 (Hard to code) for articles that meander, offer several explanations or are hard to understand.

Journalist Confidence: Confidence with which an article advances an explanation for a given day’s market movements. This ranges from a Confidence score of 3 (high confidence) if the article’s author directly states that the move was driven by a specific factor, to a score of 1 (low confidence) if the author gives multiple potential reasons, or states that investors and analysts were unsure of the reason for a market movement.

Article Title: Coded article’s title.

Clarity: This is an index composed of 4 components (1) Confidence (2) Ease of coding (3) Agreement of primary codings with/across newspapers (4) Share of unknown codings.  We combine these into a ‘clarity index’ by normalizing each measure to a z-score (mean zero and standard deviation one) and averaging and then re-normalizing.

Clarity Date: When clarity index was computed.