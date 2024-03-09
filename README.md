Debiasing Gender Stereotypes in Bollywood Movie Plots
Overview
This repository contains code to analyze, detect, and remove gender stereotypes from Bollywood movie plots. The techniques employed are inspired by the following research papers:

"Analyze, Detect and Remove Gender Stereotyping from Bollywood Movies"
"Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings"
Workflow
The project workflow can be summarized as follows:

Data Collection:

Acquire Bollywood movie plot data.
Preprocessing:

Tokenize the movie plots.
Convert text to lowercase.
Remove stopwords and special characters.
Set the minimum count for unique words to 1.
Gender-Specific Word Extraction:

Identify and extract gender-specific adjectives and verbs.
Create lists of female and male words.
Cosine Similarity Analysis:

Calculate cosine similarity to assess gender bias in word embeddings.
Identify gender-specific biases.
Debiasing:

Utilize equalizing techniques for neutralizing gender-specific word vectors.
Compute cosine similarity after debiasing.
Results and Evaluation:

Analyze and compare the effectiveness of debiasing techniques.
Measure changes in cosine similarity.
