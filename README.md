# 🎬 Movie Recommendation System (Content-Based)

## 📌 Overview
This project is a content-based machine learning model that recommends movies based on user input. By analyzing movie metadata such as genres, keywords, cast, and crew, the model calculates the cosine similarity between movies to suggest the top 5 closest matches to the user's favorite film. 

## 🛠️ Tools & Technologies Used
* **Development Environment:** Visual Studio Code (VS Code)
* **Programming Language:** Python
* **Libraries:** Pandas, Scikit-learn (CountVectorizer, Cosine Similarity), NLTK (PorterStemmer), AST
* **Data Source:** [TMDB 5000 Movies Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) via Kaggle
* **AI Assistance:** Google Gemini (for debugging, code optimization, and troubleshooting)

## 🚀 Features
* **Text Preprocessing:** Extracts relevant data from JSON-like strings, removes spaces to create unique entity tags (e.g., "James Cameron" -> "JamesCameron"), and applies stemming.
* **Vectorization:** Converts textual metadata into a matrix of token counts using `CountVectorizer`.
* **Smart Search:** Normalizes user input (handling spacing and capitalization) so inputs like `iron man`, `IronMan`, and `ironman` successfully return accurate recommendations.

## 💻 How to Run Locally
1. Clone this repository:
   ```bash
   git clone [https://github.com/AbdullahShakeelOfficial/Movie-Predictor-ML.git](https://github.com/AbdullahShakeelOfficial/Movie-Predictor-ML.git)