---
layout: page
title: Research
permalink: /Research
---
## <u>Current Projects</u>
#### Pasadena Unified School District School Lottery Data Analysis
In Pasadena de facto socioeconomic and racial segregation has continued to this day through the public-private school divide. In fact, 30% of the children in Pasadena attend private school, about three times the national average - this leaves the public schools with low student enrollment and thus inadequate state funding. Our project seeks to identify how to change the PUSD school lottery system so that more families get their top choice school, and the distribution of children from different racial and socioeconomic classes is more evenly spread across the district. Here are some preliminary **[results](https://SujaiHiremath.github.io/assets/img/pasadenaresearch.pdf)**.
## <u>Current Papers I'm Reading/Think are Important</u>
Overview of Causal Inference - **[link](https://SujaiHiremath.github.io/assets/img/overview.pdf)**. 

Causal Structural Learning - **[link](https://SujaiHiremath.github.io/assets/img/causallearning.pdf)**.

Handling Confounders - **[link](https://SujaiHiremath.github.io/assets/img/controls.pdf)**.




## <u>Previous Work</u>
#### URL Classification ML Tool
I was hired as a research assistant at Caltech by Shunto Kobayashi to build an ML tool for classifying company website URLs into their corresponding industries. I used the tidymodels package in R to create a machine learning model that processed website URLs into 3-letter n-grams, and then used a XGBoost classifier algorithm to assign category labels: the final model had 95.25% accuracy. Here is a link to my **[results](https://SujaiHiremath.github.io/assets/img/url.pdf)**. 

#### Impact of Rebroadcasters on Yahoo! Ad Auctions
I worked with Matthew Shum to understand the role of specific bidders in Yahoo! Ad Auctions called ‘rebroadcasters’, who act as middlemen between auctioneers and traditional bidders. Rebroadcasters receive bid requests from the auctioneers, update the bid requests with additional information and pass the modified bid request to other bidders. Interestingly, I found that rebroadcasters could be characterized by both high financial impact, contributing 34% of overall auction revenue, and cheaper bids, with an average winning bid that was only 70% of the average winning bid from traditional bidders. Importantly, I established that in 93% of the auctions that rebroadcasters won, the bidder that they represented never submitted a direct bid. This heavily supports my group’s working theory that rebroadcasters contribute significant value by identifying money-ball auctions that traditional bidders miss out on because they lack targeted and specific information about many ad opportunities. Here is a link to the full **[paper](https://SujaiHiremath.github.io/assets/img/yahoo.pdf)**.

#### Bounded Confidence Models on Opinion Dynamics - Caltch and UCLA Joint Group
I worked with Franca Hoffmann to develop bounded confidence models of opinion dynamics on social networks that could account for heterogeneous sources of ‘media opinions’; this would potentially make them useful for studying, modeling, and predicting how misinformation from untrustworthy news sites spreads on platforms like Twitter. I started with a traditional agent-based model where ‘agents’ are accounts. I then derived a macroscopic equation that describes the evolution of the distribution of agent opinions over time by proposing a fixed time-step opinion update rule, taking the limit as the time-step approached 0, and finding the mean-field limit as the number of accounts on the network approached infinity. Lastly, I was able to use the mean-field approximation of the velocity of opinion change, and previous work on swarming models, to derive the final macroscopic density equation. One interesting result I proved is that piecewise constant distributions of opinion can not be steady states of the macroscopic equation. Here is a link to the full **[paper](https://SujaiHiremath.github.io/assets/img/opinion.pdf)**.