# travel_planner_code-implementation
Explanation
Data Preparation: The dataset is loaded, and any missing values are handled. Descriptive statistics and visualizations help understand the data distribution.

Feature Engineering: Categorical features are encoded, and numerical features are normalized using StandardScaler.

Model Building: A K-Nearest Neighbors (KNN) model is trained on the normalized features.

User Preferences: User preferences are encoded and normalized using the same encoders and scalers used for the dataset.

Recommendation: The KNN model is used to find similar destinations based on user preferences. The recommendations are printed and visualized.
