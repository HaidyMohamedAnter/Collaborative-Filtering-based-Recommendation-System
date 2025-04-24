# 🎬 MovieMate: Collaborative Filtering Recommender System

This project builds a **Collaborative Filtering-based Movie Recommendation System** using the **MovieLens 100K** dataset.  
The system provides personalized movie suggestions based on user preferences and the behavior of similar users.

---

📚 Dataset
- **MovieLens 100K**
- 100,000 ratings from 943 users on 1,682 movies
- Download: https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset

---

## ⚙️ Functional Features

✅ Load and preprocess MovieLens dataset  
✅ Implement **User-Based Collaborative Filtering**  
✅ Implement **Item-Based Collaborative Filtering**  
✅ Evaluate model using **RMSE**, **Precision@K**, and **Recall@K**  
✅ Provide top-N recommendations for a given user  
✅ (Optional) Visualize similarity matrices and performance

---

## 🧠 Project Structure
collaborative-filtering-recommender/ 
│ 
├── README.md 
├── requirements.txt 
│ 
├── data/ 
│   
└── u.data 
│   
│   
└── u.item 
└── u.user 
│ 
├── notebooks/ 
│   
├── 01_data_preprocessing.ipynb 
│   
│   
│   
├── 02_user_based_cf.ipynb 
├── 03_item_based_cf.ipynb 
└── 04_evaluation_and_visualization.ipynb 
│ 
├── src/ 
│    
├── data_loader.py 
├── recommender.py 
└── evaluation.py 
│ 
└── results/ 
├── top_n_recommendations.csv 
└── evaluation_metrics.json
