# PyTorch-Model-for-Sentence-level-Multimodal-Sentiment-Analysis

This repository contains code for developing a PyTorch-based hybrid model that performs sentiment analysis using both textual and visual information. The model is designed from scratch, leveraging deep learning techniques for effective sentiment classification.

**Dataset:** https://drive.google.com/file/d/1BW0DKYWtDdPMoVjuuCJ_E8TMDzSxjASb/view?usp=sharing

**Code Structure**

Here’s an overview of the code structure:

**Data Loading and Preprocessing:**
1.Load dataset from Google Drive.
2.Preprocess images and captions.
3.Extract features using pre-trained VGG model for images.

**Text Preprocessing:**

1.Tokenize and extract BERT embeddings for textual data.

**Model Definition:**

1.Define separate models for handling image and text data.
2.Implement a multimodal model that integrates both image and text models.

**Training and Evaluation:**

1.Train the multimodal model using Adam optimizer and BCE loss function.
2.Evaluate model performance on both training and testing datasets.

**Results:**

Compute metrics like accuracy, confusion matrix, and F1-score.
