# Voice of Customer - Energy Market
Our client, a French energy supplier, is expecting an intensifying competition to retain customers in 2025 given the tense energy market, including but not limited to soaring energy prices. To differentiate itself from its competitors, it wants to listen to customer feedback.

## 📌 Project Overview
This project analyzes customer feedback for a **French energy supplier** facing increased competition in 2025 due to soaring energy prices. The goal is to **extract insights from customer reviews** using **Natural Language Processing (NLP)** techniques and provide recommendations to improve the customer experience.

## 🏆 Key Objectives
- Apply **NLP techniques** to analyze the **Voice of Customer (VoC)** and identify pain points.
- Use **sentiment analysis and topic extraction** to detect recurring concerns.
- Leverage **TF-IDF and Word2Vec embeddings** to structure and interpret customer reviews.
- Provide **data-driven recommendations** to help the company differentiate itself in a competitive energy market.

## 🔍 Data Pipeline
### 1️⃣ Data Collection
- Web scraping and API extraction of customer reviews.
- Removal of missing values and noise in the text.

### 2️⃣ Data Preprocessing
- **Text cleaning:** Lowercasing, punctuation removal, and stopword filtering.
- **Tokenization & Lemmatization:** Using **SpaCy** for efficient text segmentation.

### 3️⃣ Feature Engineering
- **TF-IDF weighting:** Identifies important terms in customer feedback.
- **Word2Vec embeddings:** Captures semantic relationships between words.
- **Sentence embeddings:** Weighted vector representation for document-level analysis.

### 4️⃣ Data Analysis & Visualization
- **Topic Modeling:** Extraction of key themes from reviews.
- **Sentiment Analysis:** Categorization of feedback as positive, neutral, or negative.
- **t-SNE clustering:** Visualizing customer sentiment patterns.

## 📊 Results & Insights
- Top recurring customer concerns: **service quality, pricing, contract management, and billing.**
- **Distinct sentiment clusters** observed in t-SNE visualization.
- Word embeddings reveal associations between negative and positive feedback themes.

## 🛠️ Tech Stack
- **Programming Language:** Python
- **Libraries:** Pandas, Numpy, Scikit-learn, SpaCy, NLTK, Gensim, Matplotlib, Seaborn
- **NLP Models:** TF-IDF, Word2Vec, t-SNE Clustering

## 🚀 Future Enhancements
- Implement **deep learning models** (BERT, transformers) for more accurate sentiment analysis.
- Build a **recommendation system** for personalized customer support.
- Integrate **real-time feedback monitoring** for continuous improvement.

## 🤝 Team Members
- **Roy Bensimon**
- Mamoun Jamai
- Samuel Rajzman
- Marco Salerno
- Solal Zana
- Maxim Leon Ochterbeck

##  References
- [Capgemini Data Camp 2024](https://www.capgemini.com/)
- Scientific papers on NLP and sentiment analysis

##  Contact
For any questions or collaborations, feel free to reach out!
roybensimonpro@gmail.com
