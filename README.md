# ✈️ Travel Destination Sentiment Analysis – Hyderabad

## 📚 Project Overview
This project involves analyzing traveler reviews for Hyderabad destinations to determine the **sentiment** expressed in the reviews.  
The analysis is based on both **overall sentiments** and **aspect-based sentiments** (like food, service, cleanliness, etc.).

The final insights are presented through a **Power BI dashboard** for easy visualization and interpretation.

---

## 📂 Dataset Description
The project consists of the following main files:

| File | Description |
|:-----|:------------|
| `Travels Reviews.ipynb` | Jupyter Notebook for sentiment analysis and aspect extraction |
| `reviews_with_sentiment_clean (1).xls` | Cleaned dataset with sentiment results |
| `Travel Analysis.pbix` | Power BI dashboard showcasing the sentiment analysis insights |

---

## ✨ Features
- 📝 **Review Text**: User-generated detailed reviews of places.
- 📈 **Sentiment Score**: Sentiment polarity score calculated using VADER.
- 💬 **Sentiment Label**: Categorized as Positive, Negative, or Neutral.
- 🏷️ **Aspect-Based Sentiments**: Focused on Food, Service, Cleanliness, Attractions, Amenities.
- 🌍 **Location**: All reviews pertain to places in Hyderabad.

---

## ⚙️ Implementation Details

### Steps Involved:

📀 **Load the dataset**:  
- Data is loaded using **Pandas** from `reviews.csv`.

🔄 **Preprocessing**:  
- Dropped unnecessary columns.  
- Added a **Location** column (Hyderabad).  
- Cleaned the date format (month-year conversion).

🎯 **Sentiment Analysis**:  
- Used **VADER Sentiment Analyzer** to generate compound scores.
- Classified reviews into **Positive**, **Negative**, and **Neutral** categories based on the compound score.

🔍 **Aspect-Based Sentiment Analysis**:  
- Defined aspect keywords like `food`, `service`, `cleanliness`, etc.
- Used **TextBlob** to compute polarity scores for each aspect separately.

📤 **Save Cleaned Data**:  
- The final dataset, including aspect sentiment scores and overall sentiment, is saved for Power BI visualization.

---

## 📁 Project Files

| File | Purpose |
|:-----|:--------|
| `Travels Reviews.ipynb` | Data processing, sentiment analysis, aspect sentiment extraction |
| `reviews_with_sentiment_clean (1).xls` | Final cleaned dataset ready for dashboard visualization |
| `Travel Analysis.pbix` | Interactive dashboard showing sentiment breakdown and insights |

---

## 📊 Dashboard Overview (Power BI)
The Power BI dashboard provides the following insights:
- Overall distribution of **Positive**, **Negative**, and **Neutral** reviews.
- Destination-wise sentiment comparison.
- Aspect-based sentiment ratings (e.g., how good was the **food** across places?).
- Monthly trend of traveler sentiments.

✅ The dashboard is **focused on Hyderabad** tourist places only.

---

## 📦 Dependencies

- 💻 Python
- 📈 Pandas
- 📈 NumPy
- 🔎 VADER Sentiment
- 🔎 TextBlob
- 📈 Power BI Desktop

You can install the Python libraries with:

```bash
pip install pandas numpy vaderSentiment textblob
```

---

## 🚀 How to Run

1. Open and run all cells in `Travels Reviews.ipynb` to process the data.
2. Open `Travel Analysis.pbix` with Power BI Desktop to view and explore the dashboard.

---

## 🎥 Video Presentation
🎥 Video Link - *https://drive.google.com/file/d/1nU4WVxGqYC6gmnBwN5gI4fwenZU5sC_3/view?usp=sharing*

---

## 💬 Feedback & Contribution
We welcome any feedback, improvements, or suggestions! Feel free to contribute by:

- 🔍 Reporting issues or bugs
- 🌟 Suggesting enhancements
- 📝 Improving documentation
- 💬 Sharing your thoughts

📧 For feedback, please contact:

- **Siva Maruthi**: sivamaruthi590@gmail.com

---

## 👨‍🎓 Author
Developed and Presented by **Siva Maruthi**.

---

