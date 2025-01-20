---
title: "Cross-Lingual Clustering Using Large Language Models"
collection: publications
category: conferences
permalink: /publication/2024-10-29-Cross-lingual-clustering
excerpt: 'Evaluates the ability of LLMs to conduct cross-lingual clustering of news articles based on geospatial and topical information contained in the text.' 
date: 2024-10-29
venue: '7th ACM SIGSPATIAL International Workshop on AI for Geographic Knowledge Discovery'
slidesurl: # ''
paperurl: 'https://dl.acm.org/doi/pdf/10.1145/3687123.3698280'
---

Text clustering methods traditionally rely on a shared vocabulary and script, which poses a challenge for cross-lingual text clustering problems that arise in a variety of domains including social media, news, finance, and more. 
Recent approaches to cross-lingual clustering have found success by leveraging latent embedding space representations of neural models and more recently by directly using Large Language Models (LLMs) to do text clustering in zero-shot or few-shot settings. 
However, much of the recent work focuses on short text, like social media posts.
In this paper, we use cross-lingual clustering in the news domain as a case study to test whether LLMs can effectively cluster long documents by extracting and maintaining keyphrases associated with each cluster of documents. 
We compare the clustering several LLMs produce in a zero-shot setting to a more traditional online clustering method that uses TF-IDF to cluster documents based on their content and time of publication. 
We find that LLMs tend to cluster the articles based on the text, in particular based on the language of the text more than the content, and ignore the time and location of publication, indicating further work is needed before LLMs can reliably be used in clustering news articles across multiple languages.

    @inproceedings{schneider2024a,
    title={Cross-Lingual Clustering Using Large Language Models},
    author={Schneider, Nicole R and Das, Avik and O'Sullivan, Kent and Samet, Hanan},
    booktitle={Proceedings of the 7th ACM SIGSPATIAL International Workshop on AI for Geographic Knowledge Discovery},
    pages={1--10},
    year={2024}
    }