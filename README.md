# Anime Recommendation System 🎥📺

This project is an **Anime Recommendation System** that leverages **User-Based Collaborative Filtering (UBCF)** and a **Neural Network (NN)** to provide personalized anime recommendations.

## 🚀 Features
- **User-Based Collaborative Filtering (UBCF):** Recommends anime based on similar users' preferences.
- **Neural Network Model:** Predicts anime ratings using deep learning.
- **Hybrid Approach:** Combines both NN and UBCF for improved accuracy.
- **Efficient Data Cleaning:** Handles missing values, outliers, and inconsistencies.

## 🏗 Model Architecture
- **Neural Network Model (NN):**
  - 2 Dense Layers
  - 2 Dropout Layers (to prevent overfitting)
  - Optimized using **MSE & MAE Loss**
- **Collaborative Filtering (UBCF):**
  - Uses **Pearson correlation** to find similar users.
- **Hybrid Approach:**
  - Combines predictions from NN and UBCF with a weighted parameter `alpha`.

## 💻 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Noorm4590/anime-recommendation.git
   cd anime-recommendation
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook Anime_Recommendation_System.ipynb
   ```
4. Get recommendations by running the script!

## 📊 Evaluation Metrics
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**

## 🔥 Contributors
- Noor Muhammad
- Daniyal Khan

---

*Developed as part of a university project at the National University of Computer & Emerging Sciences, Karachi Campus.*
