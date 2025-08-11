# 🛒 Flipkart Review Sentiment Analysis using DistilBERT

## 📌 Overview
This project performs **sentiment analysis** on Flipkart product reviews to classify them as:
- 😊 **Positive** → Customer satisfaction and praise
- 😡 **Negative** → Complaints or dissatisfaction
- 😐 **Neutral** → Factual or emotionless statements

We leverage **DistilBERT**, a lightweight and efficient transformer model, to understand natural language and detect the emotional tone of customer feedback.


## 🎯 Objective
The goal is to help **e-commerce platforms**, **sellers**, and **analysts** gain insights into:
- Product quality perception
- Customer satisfaction trends
- Improvement areas for better user experience

---

## 📊 Dataset
- **Source:** Provided Flipkart product reviews dataset (`flipkart_reviews.csv`)
- **Features:**
  - `Review Text` — The actual customer review
  - `Sentiment` — Labeled sentiment (Positive, Negative, Neutral)


## 🧠 Model
We use the **DistilBERT** model from Hugging Face Transformers, fine-tuned for text classification.

**Why DistilBERT?**
- Lightweight yet powerful
- Faster inference with minimal performance loss
- Great for real-world applications


## ⚙️ Workflow
1. **Data Preprocessing** 🧹  
   - Text cleaning  
   - Tokenization  
   - Removing stopwords & special characters  

2. **Model Training** 🤖  
   - Fine-tune DistilBERT on labeled Flipkart reviews  
   - Optimize hyperparameters for accuracy  

3. **Prediction** 📈  
   - Classify new reviews into Positive, Negative, or Neutral  


## 🚀 Installation & Usage
```bash
# Clone repository
git clone https://github.com/yourusername/flipkart-review-sentiment-analysis-distilbert.git
cd flipkart-review-sentiment-analysis-distilbert

# Install dependencies
pip install -r requirements.txt

# Run the script
python sentiment_analysis.py

