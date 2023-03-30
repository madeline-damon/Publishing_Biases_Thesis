# Publishing_Biases_Thesis
This repository contains code that works with my full sample of 50,000 abstracts

The following list describes each file's contents:

1. Creating Full Dataset with Geographic Data: Combines WoS downloaded records, uses regex to organize authors by their address, create two different samples based on U.S. addresses and non-U.S. addresses
2. Exploring Text Data - US Sample: Explores abstracts published by first authors within the U.S.
3. Exploring Text Data - NonUS Sample: Explores abstracts published by first authors based outside the U.S.
4. Generating US and Non-US Samples: Generates Intellectual Diversity Survey sample by randomly selecting 1,300 US authors and 1,300 NonUS authors
5. LDA Topic Modeling and Mapping - All Abstracts: Uses LDA to explore appropriate topic models for all 50,000 abstracts and maps them globally
6. Nonnegative Matrix Factorization - All Abstracts: Uses NMF to explore appropriate topic models for all 50,000 abstracts, selects a model, tests for differences between groups, and maps topics globally
7. Singular Value Decomposition - All Abstracts: Uses SVD to explore appropriate topic models for all 50,000 abstracts
