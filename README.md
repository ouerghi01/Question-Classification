# Question Classification Using NLP

## Overview
This project focuses on **Question Classification** using Natural Language Processing (NLP) techniques. It leverages the experimental dataset provided by Xin Li and Dan Roth ([1]), widely recognized for advancing the understanding and classification of natural language questions. The dataset includes multiple training sets, a TREC-10 test set, and associated feature extraction tools, making it an ideal foundation for building robust question classification models.
- **lien dataset** : https://cogcomp.seas.upenn.edu/Data/QA/QC/
## Dataset Description
The dataset contains:
- **Question Classification Taxonomy**: Defines the classes used for question categorization.
- **Training Sets**:
  - Set 1: 1000 labeled questions
  - Set 2: 2000 labeled questions
  - Set 3: 3000 labeled questions
  - Set 4: 4000 labeled questions
  - Set 5: 5500 labeled questions
- **Test Set**: TREC-10 questions
- **Preprocessing Examples**: Scripts and methods used to prepare the questions for analysis.
- **Feature Extraction**:
  - Scripts for defining features.
  - Examples of semantically related word lists for categories like professions, mountains, and food.
- **All Data for Fex**: Comprehensive feature extraction data for the `Fex` tool.

## Project Goals
This project aims to:
1. Develop models capable of accurately classifying questions into predefined categories.
2. Explore and utilize advanced NLP techniques for preprocessing, feature extraction, and model training.
3. Benchmark performance using the TREC-10 test set.

## Methodology
1. **Preprocessing**:
   - Tokenization
   - Stopword removal
   - Semantic feature mapping using word lists
2. **Feature Extraction**:
   - Use scripts provided in the dataset to define lexical, syntactic, and semantic features.
3. **Model Training**:
   - Train multiple models (e.g., Naive Bayes, SVM, BERT-based classifiers) using the training sets.
4. **Evaluation**:
   - Use accuracy, precision, recall, and F1-score to evaluate model performance on the TREC-10 test set.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/ouerghi01/Question-Classification.git
   cd Question-Classification
