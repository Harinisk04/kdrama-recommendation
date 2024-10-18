**Overview**
This project clusters K-Dramas using KMeans Clustering based on features like rating and number of episodes, and provides personalized drama recommendations using Q-learning and Policy Gradient algorithms. The system offers visualizations of the clustering results, such as scatter plots and dendrograms, and allows users to choose a cluster to receive drama recommendations.

Features:

**KMeans Clustering:**
Groups K-Dramas into 3 clusters, e.g., Highly Rated, Moderately Rated, Lower Rated.
Visualizes the clustering results using scatter plots and dendrograms.
Evaluates clustering quality using the silhouette score.

**Q-learning Recommendation:**
Provides drama recommendations from a selected cluster based on simulated user feedback.
Updates the Q-values for each drama based on the feedback (reward).
Allows users to generate top N recommendations.

**Policy Gradient Recommendation:**
Recommends dramas by selecting from a probabilistic policy.
Updates the recommendation policy based on user feedback.
