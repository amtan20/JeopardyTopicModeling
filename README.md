# JeopardyTopicModeling

# Introduction
The purpose of this project was to use unsupervised learning to explore trends in the Jeopardy gameshow over a 27 year period (from 1984-2011). 

# Data
The data included Jeopardy 216,930 questions and was retrieved from this site: https://www.reddit. com/r/datasets/comments/1uyd0t/200000_jeopardy_questions_in_a_json_file/

# Overview of Methods/Modeling Process
1. Cleaned, tokenized, and lemmatized text using spaCy. 
2. Determined the optimal number of topics using coherence score. 
3. Calculated topic probabilities for each question using Latent Dirichlet Allocation (LDA).  
4. Wrote a Python function to return the top n most important topics and the corresponding words that described that topic for a given decade and round of Jeopardy. 
5. Identified the most likely topic for each question using Non-Negative Matrix Factorization (NMF).
6. Visualized the results to show trends in Jeopardy questions over time.

# Results
- When comparing the 3 rounds of the gameshow (Jeopardy, Double Jeopardy, and Final Jeopardy), the topics of Final Jeopardy questions were the most similar throughout the decades. 
- The topics of questions from all 3 rounds combined showed an average overlap of 13% from year to year. 
