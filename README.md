# Movie Recommender


## Project Overview
This project focuses on developing an AI-powered movie recommendation system that delivers personalized content suggestions for users. By analyzing factors such as user profiles, browsing and search history, demographic characteristics, and preferences of similar users, the system aims to generate tailored recommendations. The objective is to enhance user experience, satisfaction, and engagement through intelligent content curation.

---

## Features
- User-based collaborative filtering (KNN, PCA, SVD)
- Item-based collaborative filtering (KNN, PCA, SVD)
- Hybrid model (K-means clustering + Random Forest)
- Genre-specific recommendations
- Personalized suggestions based on user activity

---

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn


---

## Dataset
The dataset used in this project comes from MovieLens, containing:
- 100,836 ratings
- 3,683 tag applications
- 9,742 movies
- Data files: links.csv, movies.csv, ratings.csv, tags.csv
- Additionally, data was scraped from IMDb and TMDb to enhance the recommendation system.

---

## Approaches Implemented
- **Collaborative Filtering**
  -  **KNN (K-Nearest Neighbors)**: Finds similar users or movies based on rating behavior.
  -  **PCA (Principal Component Analysis)**: Reduces dimensionality and identifies key patterns in user-movie interactions.
  -  **SVD (Singular Value Decomposition)**: Factorizes the user-movie matrix to capture latent features.

- **Hybrid Model**
  - Uses K-means clustering to group users based on rating behavior. Employs a Random Forest Regressor to predict ratings and generate recommendations. Combines user activity and movie features for enhanced accuracy.

---

## Future Enhancements
Implement deep learning techniques such as Neural Networks for better recommendation accuracy.
Incorporate real-time user feedback for dynamic recommendations.
Optimize computational performance for large-scale datasets.

---

## License  
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
