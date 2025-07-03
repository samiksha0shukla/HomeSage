# 🏠 HomeSage

### *Your Smart Companion for Real Estate Price Prediction, Analytics, and Recommendations*

---

## 📌 Overview

**HomeSage** is a unified, intelligent platform designed to assist real estate buyers, sellers, and analysts in making informed decisions. By integrating machine learning, interactive data visualizations, and a recommendation system, HomeSage empowers users with accurate price predictions, market trend insights, and personalized property suggestions.

---

## 🚀 Features

* 🔍 **Price Prediction**
  Predict property prices based on input features like type, location, built-up area, and amenities using a trained ML pipeline.

* 📊 **Data Analytics Dashboard**
  Dynamic sector-wise visualizations, area vs. price comparisons, BHK distribution pie charts, and word clouds for property features.

* 🧠 **Recommendation Engine**
  Personalized property suggestions based on cosine similarity and spatial proximity.

* 🌐 **Interactive Streamlit Interface**
  User-friendly web app for entering property details, exploring analytics, and viewing recommendations.

---

## 🧠 Tech Stack

| Layer              | Tools/Frameworks                       |
| ------------------ | -------------------------------------- |
| **Frontend**       | Streamlit                              |
| **Backend**        | Python                                 |
| **ML Libraries**   | Scikit-learn, Numpy, Pandas, Pickle    |
| **Visualization**  | Plotly, Matplotlib, Seaborn, WordCloud |
| **Data Handling**  | CSV / SQLite                           |
| **Recommendation** | Cosine Similarity                      |

---

## 📂 Folder Structure

```
HomeSage/
│
├── streamlit_app/
│   ├── price_predictor.py
│   ├── analytics_dashboard.py
│   └── recommend_properties.py
│
├── datasets/
│   ├── data_viz1.csv
│   ├── location_distance.pkl
│   └── feature_text.pkl
│
├── models/
│   ├── pipeline.pkl
│   └── cosine_sim_matrices.pkl
│
└── README.md
```

---

## ⚙️ Installation & Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/samiksha0shukla/HomeSage.git
   cd HomeSage
   ```

2. **Install Required Libraries**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit App**

   ```bash
   streamlit run streamlit_app/price_predictor.py
   ```

---

## 🧪 Testing

* Unit Testing: Pytest
* Manual Testing for UI and prediction accuracy
* Dataset validation through exploratory data analysis

---

## 📈 Sample Use Case

1. Enter property details (e.g., flat, 3BHK, Sector 21, 1800 sqft).
2. Click "Predict" to view the estimated price range.
3. Explore the **Analytics Dashboard** for trends.
4. Use the **Recommendation Tool** to discover similar properties nearby.

---

## 🌱 Future Enhancements

* Live market data integration via APIs.
* Deep learning-based recommendations.
* Mobile app version.
* Voice-based inputs and multi-language support.

---
