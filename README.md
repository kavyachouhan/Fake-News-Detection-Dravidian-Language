# Fake News Detection in Dravidian Languages (Malayalam)

![Python](https://img.shields.io/badge/Python-3.x-blue) ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.24-orange) ![Pandas](https://img.shields.io/badge/Pandas-1.3.0-green) ![NumPy](https://img.shields.io/badge/NumPy-1.21.0-yellow)

## Overview

This project was developed as part of the IITM-PAN BS AI-ML Challenge. The primary objective was to build a machine learning model capable of detecting fake news in the Malayalam language, a Dravidian language spoken in the Indian state of Kerala. The project was challenging due to the highly imbalanced dataset and the team's unfamiliarity with the language.

**Key Achievements:**
- Developed a machine learning model with a macF1 score of 0.248.
- Tackled issues related to class imbalance and language unfamiliarity.
- Collaborated with a team to implement various machine learning techniques for model development and evaluation.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Approach](#approach)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Challenges Faced](#challenges-faced)
- [Contributors](#contributors)

## Introduction

The goal of this project was to detect fake news articles written in Malayalam. The project was part of a competitive challenge and provided valuable insights into working with text data in languages other than English. The model was trained on a dataset provided by the challenge organizers, which was highly imbalanced, adding complexity to the task.

## Dataset

The dataset consisted of news articles in Malayalam labeled as either "False", "Mostly False", "Partly False" or "Half True." One of the key challenges was the significant class imbalance, with far more "False" news articles than others.

## Approach

1. **Data Preprocessing:**
   - Text cleaning and normalization.
   - Tokenization and vectorization using TF-IDF and Bag of Words.

2. **Model Development:**
   - Experimented with various machine learning algorithms including Logistic Regression, XGboost, and Random Forest.
   - Addressed class imbalance using techniques like oversampling, undersampling, and class weights.

3. **Evaluation:**
   - Evaluated models using macF1 score and accuracy.
   - The best performing model achieved a macF1 score of 0.248 and an accuracy of 73.5%.

## Results

- **macF1 Score:** 0.248
- **Accuracy:** 73.5%
- While these results did not win the challenge, they provided important learning experiences in handling imbalanced datasets and working with unfamiliar languages.

## Technologies Used

- **Programming Languages:** Python
- **Libraries:** Scikit-learn, Pandas, NumPy
- **Tools:** Google Collab

## Challenges Faced

- **Class Imbalance:** The dataset was highly imbalanced, which made it difficult to train a model that could generalize well across the classes.
- **Language Barrier:** None of the team members were familiar with the Malayalam language, which posed challenges in text preprocessing and understanding the nuances of the data.

## Contributors

- [Kavya Chouhan](https://github.com/kavyachouhan)
- Yashvi Jain
- [Sharvil More](https://github.com/team-member2)
