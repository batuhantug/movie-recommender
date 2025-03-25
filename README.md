# Movie Recommender

Welcome to the **Movie Recommender** repository! 🎬📽️ This project explores movie recommendation techniques using data analysis, sentiment classification, and vector search to suggest movies based on user preferences.

## 📂 Repository Structure

```
├── data-exploration.ipynb          # Initial data analysis and visualization
├── sentiment-classification.ipynb  # Sentiment analysis on movie reviews
├── vector-search.ipynb             # Movie recommendation using vector similarity
├── README.md                       # Project documentation (this file)
```

## 🚀 Project Overview

This project aims to build an effective movie recommendation system using various machine learning and natural language processing techniques:

1. **Data Exploration (`data-exploration.ipynb`)**
   - Load and analyze the dataset
   - Perform data cleaning and preprocessing
   - Generate insights from visualizations

2. **Sentiment Classification (`sentiment-classification.ipynb`)**
   - Use a pre-trained model from Hugging Face to classify movie plots as emotions
   - Evaluate sentiment impact on recommendations

3. **Vector Search (`vector-search.ipynb`)**
   - Convert movie features into vector representations
   - Use similarity measures (e.g., cosine similarity) to find similar movies
   - Generate personalized movie recommendations

## 🔧 Installation & Setup

To run the notebooks, follow these steps:

1. **Clone the repository**
   ```sh
   git clone https://github.com/batuhantug/movie-recommender.git
   cd movie-recommender
   ```
2. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```
   (Ensure you have Python and Jupyter Notebook installed.)

3. **Launch Jupyter Notebook**
   ```sh
   jupyter notebook
   ```

## 📊 Dataset
The dataset used in this project : https://www.kaggle.com/datasets/jrobischon/wikipedia-movie-plots

## 📈 Future Improvements
- Implement deep learning models for recommendation.
- Integrate collaborative filtering techniques.
- Deploy as a web application for user interaction.

## 📜 License
This project is open-source and available under the **MIT License**.

