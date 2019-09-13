---
layout: archive
title: "Data"
permalink: /data/
author_profile: true
---

{% include base_path %}

<a href="https://stockjumpswebsite.github.io/stockjumps/files/paper1.pdf" target="_blank">Read Our Paper</a> 

<a href="https://www.google.com/sheets/about/" target="_blank">View Our Data</a>  

<a href="https://www.google.com/slides/about/" target="_blank">View Our Slides</a>  

<a href="https://github.com/stockjumpswebsite/stockjumps/blob/master/_pages/files/articles_1.zip?raw=true">Download Articles (zip)</a>

To measure policy-related economic uncertainty, we construct an index from three types of underlying components.

<b>News Coverage about Policy-related Economic Uncertainty</b>

Our first component is an index of search results from 10 large newspapers (USA Today, the Miami Herald, the Chicago Tribune, the Washington Post, the Los Angeles Times, the Boston Globe, the San Francisco Chronicle, the Dallas Morning News, the Houston Chronicle, and the WSJ). To construct the index, we perform monthly searches of each paper for terms related to economic and policy uncertainty. In particular, we search for articles containing the term 'uncertainty' or 'uncertain', the terms 'economic' or 'economy' and one or more of the following terms: 'congress', 'legislation', 'white house', 'regulation', 'federal reserve', or 'deficit'.

To deal with changes over time in the volume of articles for a given paper, we divide the raw count of policy uncertainty articles by the total number of articles in the same paper and month. We then normalize the resulting series for each paper to have a unit standard deviation from January 1985 through December 2009. Next, we sum the normalized values over papers in each month to obtain a multi-paper index. Finally, we re-normalize the multi-paper index to an average value of 100 from January 1985 through December 2009.

With each monthly update, data from the preceding two months may be revised slightly, as well. This is driven by the fact that some online newspapers do not immediately update their online archives with all articles, leading to slightly changing totals for the previous 1-2 months.

<b>Tax Code Expiration Data</b>

The second component of our index draws on reports by the Congressional Budget Office (CBO) that compile lists of temporary federal tax code provisions. Temporary tax measures are a source of uncertainty for businesses and households because Congress often extends them at the last minute, undermining stability in and certainty about the tax code.

<b>Economic Forecaster Disagreement</b>

The third component of our policy-related uncertainty index draws on the Federal Reserve Bank of Philadelphia's Survey of Professional Forecasters. We measure dispersion in the individual-level data for three of the forecast variables directly influenced by government policy: CP, purchases of goods and services by state and local governments, and purchases of goods and services by the federal government. For each series, we look at the quarterly forecasts for one year in the future. We chose these variables because they are directly influenced by monetary policy and fiscal policy actions.

<b>Constructing our overall policy-related economic uncertainty index</b>

To construct our overall index of policy-related economy uncertainty, we first normalize each component by its own standard deviation prior to January 2012. We then compute the average value of the components, using weights of 1/2 on our broad news-based policy uncertainty index and 1/6 on each of our other three measures (the tax expirations index, the CPI forecast disagreement measure, and the federal/state/local purchases disagreement measure).
