# Customer Review Sentiment Analysis

## Problem Overview

Commercial skiing in New Zealand is an industry that's worth $1 to $1.5 billion NZD each year, with many skiers travelling to the South Island of the country which is well known around the world for its beautiful slopes.

However, the effects of climate change are causing ski seasons to become shorter due to the lack of enough snow to ski upon. As such, more skiers are visiting fewer locations that provide the most snow, creating greater competition among operators of ski fields around NZ to draw visitors to their locations. Furthermore, those locations that are now facing a greater number of visitors have to accommodate them in all facets of their skiing experience without a decrease in quality (or else they may risk losing these extra visitors to their competitors).

The client in question is the operator of some the largest ski fields in the South Island. They have asked Qrious to provide insights (using natural language processing - NLP) on what customers are saying about their ski fields as well as those of their competitors,what makes skiers choose the fields operated by their competitors, and how to continue attracting skiers to their own fields.

## Problem Breakdown and Requirements

Firstly, the client would like to us to use what customers are saying online based on to provide insights into what customers are saying about their ski fields versus those of their competitors. 

The largest sources of online customer feedback are generally social media comments and customer reviews. A brief look at each ski field's social media profiles showed that customers rarely provide direct feedback on individual posts (which are often promotional in nature and), or some posts have more than usual engagement due to a competition or offer. 

On the contrary, sites like TripAdvisor contain hundreds of reviews for each ski field and would be a good source for collecting insights on what customers are saying. Review websites which would (more often than not) not be controlled by the operators of the ski fields themselves (unlike their social media profiles) and the most popular review websites often have an authentication process to ensure anything posted comes from real humans, so whatever is said about those ski fields may be more likely to be authentic.

To keep the scope of this project manageable, a decision was made to focus on 3-5 ski fields, with the majority being the client's and the rest being the competitor's. Furthermore, after an initial exploration of what NLP techniques could be used to extract insights from customer reviews, we decided to conduct aspect-based sentiment analysis which essentially broke down our insight gathering into two problems:

1. What overarching concepts were customers were mentioning in their reviews (topic modelling)?
2. How did customers feel about each of those overarching concepts (polarity i.e. the degree of positivity and negativity and also subjectivity i.e. how subjective or objective were the reviews)?