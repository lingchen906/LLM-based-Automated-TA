Automated Thematic Analysis with K-Means-Enhanced LLM Coding
Overview
This repository contains the implementation of an automated thematic coding framework that leverages small, locally deployed LLMs and K-means clustering to extract, refine, and evaluate themes from user-generated text. The approach enables scalable, privacy-preserving qualitative analysis while maintaining high interpretability and consistency with human-coded themes.

Key Features
LLM-Based Thematic Coding: Uses Gemma 2 (27B, 9B) and LLaMA 3 (8B) to generate and evaluate themes.
K-Means Clustering for Code Refinement: Groups semantically similar codes to enhance coherence.
Inter-LLM Agreement as a Quality Metric: Uses multiple smaller models to validate generated themes.
Efficient & Privacy-Preserving: Runs on consumer-grade GPUs without reliance on cloud APIs.
Validated on E-Learning Reviews: Tested on Duolingo user reviews for educational data mining applications.
