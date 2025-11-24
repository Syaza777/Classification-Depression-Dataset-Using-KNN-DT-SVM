# 🧠 Depression Detection Using Emotion Patterns

A Machine Learning Classification Project

## 📌 Project Overview

Depression is a common but serious mental health condition affecting an estimated 121 million people worldwide.
Since human emotions can reflect underlying psychological states, emotional patterns may serve as potential indicators of depression.

The goal of this project is to recommend the best classification model that can determine whether an individual is showing signs of depression based on their emotion patterns recorded over two weeks.

## 📊 Dataset Description

This project uses two datasets — Freq-PHO-Binary.csv and Norm-PHO-Binary.csv — which contain emotion-based features collected over a two-week period to determine whether an individual shows signs of depression. We collected a dataset through self-reported emotional logs.

Each record represents one individual and includes:

| Column Name          | Description                                                                             |
| -------------------- | --------------------------------------------------------------------------------------- |
| **Gender**           | The gender of the individual (e.g., Male/Female).                                       |
| **Emotion_Joy**      | Frequency or normalized score of joy expressed.                                         |
| **Emotion_Sadness**  | Frequency or normalized score of sadness.                                               |
| **Emotion_Anger**    | Frequency or normalized score of anger.                                                 |
| **Emotion_Disgust**  | Frequency or normalized score of disgust.                                               |
| **Emotion_Fear**     | Frequency or normalized score of fear.                                                  |
| **Emotion_Surprise** | Frequency or normalized score of surprise.                                              |
| **Emotion_Contempt** | Frequency or normalized score of contempt.                                              |
| **Emotion_Neutral**  | Frequency or normalized score of neutral emotion.                                       |
| **Depression**       | Binary target variable indicating depression status (1 = depressed, 0 = not depressed). |


## 🎯 Objective

To evaluate and compare multiple classification models and identify the model that best predicts whether an individual shows early signs of depression based on their emotional patterns.