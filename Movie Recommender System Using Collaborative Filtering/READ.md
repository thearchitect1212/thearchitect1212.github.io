# Movie Recommender System Using Collaborative Filtering

## Overview
This project builds a movie recommendation system using the MovieLens dataset. By employing collaborative filtering techniques, it suggests movies based on user preferences and rating behaviors.

---

## Key Features
- **Personalized Recommendations**: Tailored movie suggestions for users.
- **Efficient Computation**: Leveraged Singular Value Decomposition (SVD).
- **Scalability**: Handles large datasets like MovieLens efficiently.

---

## Dataset
- **Source**: MovieLens dataset
- **Size**: ~100,000 ratings, ~1,000 movies
- **Features**:
  - User ID
  - Movie ID
  - Rating
- **Preprocessing**:
  - Merged ratings and movies datasets.
  - Transformed data into a user-item interaction matrix.

---

## Methodology
1. **EDA**:
   - Analyzed user behaviors (e.g., average ratings per user).
   - Visualized popular movies and rating distributions.
2. **Collaborative Filtering**:
   - Trained an SVD model to decompose the user-item matrix.
   - Predicted ratings for unobserved user-movie pairs.
3. **Evaluation**:
   - Metrics: RMSE and MAE.
   - Validated using k-fold cross-validation.

---

## Key Insights
- Recommender systems are effective in capturing latent user preferences.
- The model achieved an RMSE of 0.87, demonstrating high predictive accuracy.

---

## Technologies Used
- Python (Pandas, NumPy)
- Surprise Library
- Matplotlib for visualization

---

## Applications
- **Streaming Platforms**: Netflix-like personalized recommendations.
- **E-commerce**: Product recommendation systems for online stores.

---

## Future Directions
1. Include content-based filtering to incorporate movie genres and descriptions.
2. Explore hybrid models combining collaborative and content-based techniques.
3. Develop a web app to allow user interaction with the recommender.

---

## References
1. MovieLens Dataset Documentation.
2. Research on collaborative filtering algorithms.

---
