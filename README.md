"# ToxiWave" 
# Comment Toxicity Classification Model

This project builds a machine learning model to classify comments based on their toxicity levels. Using TensorFlow, the model learns to identify harmful language in online comments, making it useful for content moderation systems.

## Purpose

The goal of this project is to create an automated tool that detects toxic comments to improve online user experience. By classifying potentially harmful content, this model can assist in moderating large volumes of comments in social media, forums, and other online platforms.

## Project Structure

1. **Data Loading and Exploration**: The dataset is loaded from `train.csv`, and basic exploratory data analysis is performed to understand the data distribution.
2. **Data Preprocessing**: The comments are vectorized using TensorFlow’s `TextVectorization` layer to prepare for model training.
3. **Model Training**: A neural network model is built and trained on the vectorized comments to classify them as toxic or non-toxic.
4. **Model Evaluation and Prediction**:
   - **Evaluation**: The model’s performance is assessed using metrics such as accuracy and F1-score.
   - **Prediction**: After training, the model is used to make predictions on new comment data.
5. **Gradio Interface**: A Gradio web interface is created for users to test the model by entering their own comments to check toxicity levels.

## Installation

To run this project, install the required dependencies:

```bash
pip install tensorflow tensorflow-gpu pandas matplotlib scikit-learn gradio
