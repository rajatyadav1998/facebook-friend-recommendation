# facebook-friend-recommendation
Friend recommendation system using graph mining and ML
# Facebook Friend Recommendation System

This project is a simplified version of Facebook's friend recommendation system using graph-based features and machine learning.

## 🔍 Problem Statement
Recommend potential friends to users based on graph-based features like:
- Number of common friends (common neighbors)
- Preferential attachment (based on node degree)

## 📁 Dataset
- `train.csv`: Contains pairs of users and whether they are friends (1) or not (0).

## 🧠 Model
- Trained a supervised classification model using features extracted from a user-user graph.
- Algorithms used: Random Forest / Logistic Regression

## 🧮 Features Used
- Common Neighbors
- Preferential Attachment
- (Optional: Jaccard Coefficient, Adamic-Adar, etc.)

## 📦 Files
- `facebook_data_mining.ipynb`: Colab notebook with full code.
- `friend_graph.pkl`: Pre-built NetworkX graph object.
- `friend_recommendation_model.pkl`: Saved ML model for inference.
- `train.csv`: Input training data.

## 🚀 How to Run
You can open and run the notebook in Google Colab:
[Open in Colab](https://colab.research.google.com/github/rajatyadav1998/facebook-friend-recommendation/blob/main/facebook_data_mining.ipynb)

## 👨‍💻 Author
Rajat Yadav  
- Pursuing M.tech Data Science from Delhi Technological University  
- 2 years experience at Wipro  
- GATE 2024 Qualified (Data Science & AI)  

## 📌 Contact
📞 9538746317  
🔗 [LinkedIn](https://www.linkedin.com/in/rajat-yadav-575b46177)


