  
# 🚫 ToxiWave

This project builds a machine learning model to classify comments based on their toxicity levels. Using TensorFlow, the model learns to identify harmful language in online comments, making it useful for content moderation systems.

## 🎯 Purpose

The goal of this project is to create an automated tool that detects toxic comments to improve online user experience. By classifying potentially harmful content, this model can assist in moderating large volumes of comments on social media, forums, and other platforms.

## 📁 Project Structure

1. **📊 Data Loading and Exploration**: Loads the dataset from `train.csv` and performs exploratory data analysis to understand data distribution.
2. **🔄 Data Preprocessing**: Prepares comments for model training by vectorizing them with TensorFlow's `TextVectorization` layer.
3. **🧠 Model Training**: Builds and trains a neural network to classify comments as toxic or non-toxic.
4. **📈 Model Evaluation and Prediction**:
   - **Evaluation**: Assesses the model's performance using metrics like accuracy and F1-score.
   - **Prediction**: Uses the trained model to predict toxicity on new comment data.
5. **🌐 Gradio Interface**: Creates an interactive Gradio web interface for users to test the model by entering their own comments to check toxicity levels.

## 🛠️ Installation

Install the required dependencies:

```bash
pip install tensorflow tensorflow-gpu pandas matplotlib scikit-learn gradio
