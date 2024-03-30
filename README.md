# Part-of-Speech Tagging with Neural Networks

## Project Overview

This project uses a dependency treebank dataset to implement and evaluate neural network models designed for part-of-speech (POS) tagging. 
The project explores the process from data preparation to the development of different neural network models, and ultimately their evaluation. The models leverage pre-trained GloVe embeddings to enhance their performance.

## Team Members

- Mirco Lescart
- Freddy Fernandes
- Parsa Mastouri Kashani
- Arina Sadeghi Khiabanian

## Requirements

To run this project, you need Python 3. x along with the following libraries:
- pandas
- NumPy
- Keras
- matplotlib
- sklearn
- gensim

## Dataset

The dataset consists of words and their corresponding part-of-speech tags, extracted from the dependency treebank. It has been preprocessed to fit the requirements of neural network training, including length normalization and tokenization.

## Models

Three distinct models have been implemented and tested:

- **Baseline Model**: A bidirectional LSTM network enhanced with an extra dense layer for better contextual understanding.
- **Model 1**: Adds another LSTM layer to improve sequential data learning.
- **Model 2**: Incorporates an additional dense layer to capture complex patterns more effectively.

## Setup and Execution

1. Clone the repository.
2. Ensure you have all the required libraries installed in your Python environment.
3. Run the Jupyter Notebook `Assignment 1.ipynb` to train the models and evaluate their performance.

## Results

The models were evaluated based on their validation accuracy, precision, recall, and F1 scores. Model 2 showed the highest F1 scores across the majority of POS tags, indicating its superior performance in POS tagging tasks.

## Conclusion

The project demonstrates the effectiveness of using neural networks for POS tagging, highlighting the impact of architectural choices on model performance. Model 2, with its additional dense layer, was identified as the best-performing model, suggesting that deeper architectures can capture the complexities of natural language more efficiently.

For further details, please refer to the project report included in this repository.

## References

Links to references and further reading are included in the project report.
