---
title: "A Framework for Benchmarking Graph-Based Artificial Intelligence"
collection: publications
category: theses
permalink: /publication/2024-05-21-Graph-based-ai-benchmark
excerpt: 'Advised by [Bill Regli](https://www.cs.umd.edu/people/regli) at the [University of Maryland](https://www.cs.umd.edu/).'
date: 2024-05-21
venue: 'University of Maryland Masters Thesis'
slidesurl: 'https://github.com/osullik/umd_thesis'
paperurl: 'https://doi.org/10.13016/gwgs-7jgd'

---

Graph-based Artificial Intelligence (GraphAI) encompasses AI problems formulated using graphs, operating on graphs, or relying on graph structures for learning.
Contemporary Artificial Intelligence (AI) research explores how structured knowledge from graphs can enhance existing approaches to meet the real world’s demands for transparency, explainability, and performance.
Characterizing GraphAI performance is challenging because different combinations of graph abstractions, representations, algorithms, and hardware acceleration techniques can trigger unpredictable changes in efficiency. 
Although benchmarks enable testing different GraphAI implementations, most cannot currently capture the complex interaction between effectiveness and efficiency, especially across dynamic and structured knowledge graphs.
This work proposes an empirical ‘grey-box’ approach to GraphAI benchmarking, providing a method that enables experimentally trading between effectiveness and efficiency across different combinations of graph abstractions, representations, algorithms, and hardware accelerators. 
A systematic literature review yields a taxonomy of GraphAI tasks and a collection of intelligence and security problems that interact with GraphAI. 
The taxonomy and problem survey guide the development of a framework that fuses empirical computer science with constraint theory in an approach to benchmarking that does not require invasive workload analyses or code instrumentation.
We formalize a methodology for developing problem-centric GraphAI benchmarks and develop a tool to create graphs from OpenStreetMaps data to fill a gap in real-world mesh graph datasets required for benchmark inputs. 
Finally, this work provides a completed benchmark for the Population Segmentation Intelligence and Security problem developed using the GraphAI benchmark problem development methodology. 
It provides experimental results that validate the utility of the GraphAI benchmark framework for evaluating if, how, and when GraphAI acceleration should be applied to the population segmentation problem.

    @mastersthesis{osullivan2024,
    title={A Framework for Benchmarking Graph-Based Artificial Intelligence},
    author={O'Sullivan, Kent Daniel},
    year={2024},
    school={University of Maryland, College Park}
    }