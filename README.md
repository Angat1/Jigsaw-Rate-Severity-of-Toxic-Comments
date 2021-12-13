# Jigsaw-Rate-Severity-of-Toxic-Comments
This repository Jigsaw Rate Severity of Toxic Comments
In Jigsaw's fourth Kaggle competition, we return to the Wikipedia Talk page comments featured in our first Kaggle competition. When we ask human judges to look at individual comments, without any context, to decide which ones are toxic and which ones are innocuous, it is rarely an easy task. In addition, each individual may have their own bar for toxicity. We've tried to work around this by aggregating the decisions with a majority vote. But many researchers have rightly pointed out that this discards meaningful information.

😄 🙂 😐 😕 😞
A much easier task is to ask individuals which of two comments they find more toxic. But if both comments are non-toxic, people will often select randomly. When one comment is obviously the correct choice, the inter-annotator agreement results are much higher.

In this competition, we will be asking you to score a set of about fourteen thousand comments. Pairs of comments were presented to expert raters, who marked one of two comments more harmful — each according to their own notion of toxicity. In this contest, when you provide scores for comments, they will be compared with several hundred thousand rankings. Your average agreement with the raters will determine your individual score. In this way, we hope to focus on ranking the severity of comment toxicity from innocuous to outrageous, where the middle matters as much as the extremes.

Can you build a model that produces scores that rank each pair of comments the same way as our professional raters?

Disclaimer: The dataset for this competition contains text that may be considered profane, vulgar, or offensive.

Related Work
The paper "Ruddit: Norms of Offensiveness for English Reddit Comments" by Hada et al. introduced a similar dataset that involved tuples of four sentences that were marked with best-worst scoring, and this data may be directly useful for building models.

We also note "Constructing Interval Variables via Faceted Rasch Measurement and Multitask Deep Learning: a Hate Speech Application" by Kennedy et al. which compares a variety of different rating schemes and argues that binary classification as typically done in NLP tasks discards valuable information. Combining data from multiple sources, even with different annotation guidelines, may be essential for success in this competition.

Resources
The English language resources from our first Kaggle competition, and our second Kaggle competition, which are both available in the TensorFlow datasets Wikipedia Toxicity Subtypes and Civil Comments can be used to build models.

One example of a starting point is the open source UnitaryAI model.

Google Jigsaw
Google's Jigsaw team explores threats to open societies and builds technology that inspires scalable solutions. One Jigsaw product is PerspectiveAPI which is used by publishers and platforms worldwide as part of their overall moderation strategy.
