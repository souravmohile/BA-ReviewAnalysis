# Airline Customer Analysis Projects

This repository contains two projects aimed at analyzing airline customer data:

1. **Sentiment Analysis of Customer Reviews**:
   - Uses multiple sentiment analysis techniques to analyze and visualize customer feedback.
   - Highlights areas of customer satisfaction and dissatisfaction through advanced NLP techniques.

2. **Customer Modeling**:
   - Explores the factors influencing customer flight bookings.
   - Includes predictive modelling and segmentation for a better understanding of customer behaviour.

---

## **1. Sentiment Analysis of Customer Reviews**

This project analyzes customer reviews using three sentiment analysis methods: **VADER**, **TextBlob**, and **BERT**. It involves preprocessing textual data, performing sentiment analysis, and visualizing results through various techniques.

### **Features**
- **Data Preprocessing**:
  - Combined titles and reviews into a single text.
  - Cleaned text by removing punctuation, special characters, and stopwords.
  - Tokenized and processed text for more structured analysis.

- **Sentiment Analysis**:
  - **VADER**: Lexicon-based tool designed for social media and short-text sentiment analysis.
  - **TextBlob**: General-purpose sentiment analysis tool using polarity scoring.
  - **BERT**: State-of-the-art transformer model for fine-grained sentiment classification.

- **Visualizations**:
  - WordClouds for positive and negative reviews.
  - Histograms displaying sentiment score distributions for each method.
  - Scatter plots comparing sentiment scores across methods.
  - Correlation heatmap to evaluate agreement between sentiment analysis methods.

### **Key Insights**
- Refined WordClouds created from the top 1000 positive and negative reviews, as determined by BERT scores.
- Identified key sentiment trends and areas of improvement for airline services.

### **Dataset**
- **Source**: Contains 3,612 customer reviews.
- **Structure**:
  - `Title`: Review title.
  - `Review`: Full review text.
  - Additional fields created during preprocessing for analysis.

---

## **2. Customer Modeling**

This project focuses on understanding what influences a customer's flight booking.

