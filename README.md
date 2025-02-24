# Medical Hypothesis Generation using the Reddit AskDocs Dataset

With more people turning to online forums like Reddit’s r/AskDocs for medical advice, it is crucial to understand whether AI can provide useful preliminary health assessments. This project explores the effectiveness of Natural Language Processing in identifying potential medical conditions from user-generated posts. We scraped and processed AskDocs data and are using a fine-tuned language model to generate two types of responses: a list of possible diagnoses with test recommendations and a Reddit-style physician reply. To evaluate accuracy, we compare these AI-generated responses to actual top-voted physician comments using a similarity metric. Our goal is to determine how well AI aligns with expert medical opinions and whether it can be a reliable tool for preliminary guidance. The results will help assess the feasibility of AI-assisted symptom analysis, particularly for those with limited access to healthcare.

# Project Dependencies Installation Guide

This guide provides detailed steps to install the necessary dependencies for the project.

## Dependencies

The project relies on several Python libraries for data manipulation, machine learning operations, text processing, and data visualization. Below is a list of the main libraries used:

- pandas: For data manipulation and analysis.
- scikit-learn: For machine learning and data processing.
- nltk: For natural language processing tasks.
- matplotlib: For creating static, animated, and interactive visualizations in Python.

## Installation

Ensure you have Python installed on your system. It's recommended to use Python 3.8 or newer. You can download Python from [python.org](https://www.python.org/downloads/).
