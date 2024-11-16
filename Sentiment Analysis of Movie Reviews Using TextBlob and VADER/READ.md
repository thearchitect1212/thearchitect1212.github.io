# Sentiment Analysis of Movie Reviews Using TextBlob and VADER

## Overview
This project analyzes movie reviews to classify their sentiment as positive or negative. Using prebuilt libraries like TextBlob and VADER, it compares their performance and identifies strengths and weaknesses in analyzing textual data.

---

## Key Features
- **Sentiment Analysis**: Used polarity scores to classify reviews.
- **Tool Comparison**: Evaluated TextBlob and VADER for sentiment detection.
- **Accuracy Metrics**: Measured model accuracy against ground-truth labels.

---

## Dataset
- **Source**: IMDB labeled movie reviews dataset.
- **Size**: 25,000 reviews (50% positive, 50% negative).
- **Features**:
  - Review Text
  - Sentiment Label (1 for positive, 0 for negative)
- **Preprocessing**:
  - Removed HTML tags and special characters.
  - Tokenized text for processing by sentiment analyzers.

---

## Methodology
1. **EDA**:
   - Explored review lengths, word frequencies, and sentiment distributions.
   - Visualized polarity scores for positive and negative reviews.
2. **Sentiment Analysis**:
   - Used TextBlob to compute polarity scores and classify reviews.
   - Applied VADER for sentiment analysis, focusing on compound scores.
3. **Evaluation**:
   - Calculated accuracy, precision, recall, and F1-score.
   - Compared predictions against ground-truth sentiment labels.

---

## Key Insights
- TextBlob achieved 68.5% accuracy, slightly outperforming random guessing.
- VADER excelled in detecting nuanced sentiments, especially in mixed reviews.
- Both tools demonstrated limitations in handling sarcasm and complex language.

---

## Technologies Used
- Python (Pandas, NumPy)
- TextBlob
- VADER (Valence Aware Dictionary and sEntiment Reasoner)
- Scikit-learn (Evaluation Metrics)

---

## Applications
- **Social Media Monitoring**: Analyzes sentiment in user comments and tweets.
- **Movie Recommendation Systems**: Enhances recommendations by incorporating sentiment analysis.
- **Customer Feedback**: Identifies trends in product or service reviews.

---

## Future Directions
1. Train custom sentiment models on domain-specific datasets for better accuracy.
2. Incorporate deep learning techniques such as LSTMs or transformers.
3. Build an API for real-time sentiment analysis of movie reviews.

---

## References
1. IMDB Dataset Documentation.
2. TextBlob and VADER Documentation.
3. Research on Sentiment Analysis Techniques.

---
