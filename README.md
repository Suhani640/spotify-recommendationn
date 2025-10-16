# 🎧 Spotify Music Recommendation System

The **Spotify Music Recommendation System** is a project designed to analyze musical features and suggest tracks similar to a listener’s preferences, inspired by Spotify’s own recommendation algorithms. Using the **Spotify Tracks Dataset** from Kaggle, the system evaluates multiple audio attributes such as **danceability, energy, loudness, speechiness, acousticness, instrumentalness, liveness, valence, and tempo** to understand the sonic characteristics of each track. By analyzing these features, the system groups similar songs together and provides personalized recommendations for users.

## 🧠 Project Workflow

1. **Data Preprocessing**  
   - Handled missing values and duplicates  
   - Selected relevant numeric features for analysis  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions, trends, and patterns using **Matplotlib** and **Seaborn**  
   - Created a **correlation matrix** to understand relationships between audio features  

3. **Clustering**  
   - Applied **K-Means clustering** on scaled feature data  
   - Grouped songs into clusters based on audio similarity  

4. **Recommendation System**  
   - Built a **content-based recommendation engine** using **cosine similarity**  
   - Suggests songs similar to a chosen track, prioritizing cluster similarity  

## 📊 Key Features

- Automatic song clustering based on audio features  
- Correlation analysis to understand feature relationships  
- Personalized music recommendations for any track in the dataset  

## 🛠️ Tools & Libraries

- **Python**  
- **Pandas** & **NumPy** for data manipulation  
- **Matplotlib** & **Seaborn** for visualization  
- **Scikit-learn** for clustering and recommendation modeling  

## 🚀 Outcome

The project demonstrates a practical approach to building a recommendation system for music streaming platforms. By combining clustering with content-based similarity, it provides meaningful song recommendations that enhance user experience, illustrating how **machine learning and data analysis** can be applied in real-world applications.
