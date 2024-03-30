# POS-Tagging-NN
# Part-of-Speech Tagging with Neural Networks

## Overview
This project explores the development and evaluation of neural network models for part-of-speech (POS) tagging, leveraging a dependency treebank dataset. It highlights the process from data preparation to model evaluation, with a focus on addressing common NLP challenges such as out-of-vocabulary (OOV) tokens.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Results](#results)
- [Future Directions](#future-directions)
- [Contributors](#contributors)
- [References](#references)

## Features
- Implementation of neural network models for POS tagging
- Management of OOV tokens with innovative approaches
- Utilization of pre-trained GloVe embeddings for enhanced model performance
- Detailed performance analysis using precision, recall, and F1-score

## Models
- Baseline Model: A bidirectional LSTM network, enhanced with an additional dense layer for context understanding.
- Model 1: Extends the baseline by incorporating an extra LSTM layer, aiming at improved sequential data learning.
- Model 2: Introduces an additional dense layer to capture complex patterns, showing superior performance.

## Results
Model evaluation reveals that Model 2 consistently achieves high F1-scores, outperforming other configurations. Detailed results and analysis are available in the results directory.

## Future Directions
Further refinement of the existing models to improve accuracy
Exploration of more sophisticated neural network architectures
Expansion of the dataset to include more diverse linguistic structures
## Contributors
Mirco Lescart
Freddy Fernandes
Parsa Mastouri Kashani
Arina Sadeghi Khiabanian
## References
- Journal of Big Data Article on POS Tagging
- GloVe: Global Vectors for Word Representation
- Handling OOV Words in NLP
- StatQuest for Statistical Understanding
