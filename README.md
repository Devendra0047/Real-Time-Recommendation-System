# Real-Time-Recommendation-System

Explanation:

Data Collection and Processing:
Load the interaction data and encode user and item IDs.
Split the data into training and testing sets.

Model Training:
Use the Surprise library to train an SVD-based collaborative filtering model.
Evaluate the model using RMSE.

Serving Recommendations:
Create a Flask web server with an endpoint /recommendation to get user recommendations.
Generate recommendations by predicting interactions for all items and sorting them.
