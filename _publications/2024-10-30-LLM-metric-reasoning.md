---
title: "Metric Reasoning in Large Language Models"
collection: publications
category: conferences
permalink: /publication/2024-10-30-LLM-metric-reasoning
excerpt: 'Evaluates the ability of LLMs to conduct formal spatial reasoning using metric relations finding a general lack of geospatial reasoning ability.' 
date: 2024-10-30
venue: '32nd ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems'
slidesurl: # ''
paperurl: 'https://dl.acm.org/doi/pdf/10.1145/3678717.3691226'

---

Spatial reasoning is a particularly challenging task that requires inferring implicit information about objects based on their relative positions in space. 
In an effort to develop general purpose geo-foundation models that can perform a variety of spatial reasoning tasks, preliminary work has explored what kinds of world knowledge and spatial reasoning capabilities Large Language Models (LLMs) naturally inherit from their training data. 
Recent work suggests that LLMs contain geospatial knowledge in the form of understanding geo-coordinates and associating spatial meaning to the key terms “near” and “far.” 
In this paper, we show that LLMs lack the ability to adapt the meaning of the words “near” and “far” to the appropriate scale when provided contextual reference points. 
By uncovering biases in how LLMs answer distance-related spatial questions, we set the groundwork for developing new techniques that may enable LLMs to perform accurate spatial reasoning.

    @inproceedings{osullivan2024a,
    title={Metric Reasoning in Large Language Models},
    author={O'Sullivan, Kent and Schneider, Nicole R and Samet, Hanan},
    booktitle={Proceedings of the 32nd ACM International Conference on Advances in Geographic Information Systems},
    pages={501--504},
    year={2024}
    }