# 📚 Book Recommender System using Machine Learning

This project is a **Book Recommendation System** built with Python and Machine Learning.  
It suggests books to users based on ratings data using **Collaborative Filtering** and **Cosine Similarity**.


![Logo](https://cdn.slidesharecdn.com/ss_thumbnails/bookrecommendations-230615063942-3b1016c9-thumbnail.jpg?width=640&height=640&fit=bounds)



## Features

- Popularity-based recommendations (Top rated + most read books)
- User-based Collaborative Filtering
- Item-based Collaborative Filtering (similar books)
- Search and recommend books by title
- Dataset preprocessing and cleaning


## Dataset

The project uses 3 CSV files from the **Book-Crossing dataset**:
- `Books.csv` → Book details (Title, Author, ISBN, Image URL)
- `Users.csv` → User details (User ID, Location, Age)
- `Ratings.csv` → Ratings data (User ID, ISBN, Rating)

Note: `Books.csv` is large (~70 MB). GitHub may not preview it in-browser, but it can be downloaded.


## How to run?

1. Clone the Repository:
   ```bash
   git clone https://github.com/IdiotEditor/Book-Recommender-System-Using-Machine-Learning.git
   cd Book-Recommender-System-Using-Machine-Learning
2. Install dependencies:
   pip install -r requirements.txt
3. Open the Jupyter/Colab notebook:
   jupyter notebook Book_Recomenrder_System.ipynb

## Usage

Example of generating recommendations: 

recommend("Harry Potter and the Sorcerer's Stone")

Output: 

Harry Potter and the Chamber of Secrets  
Harry Potter and the Prisoner of Azkaban  
Harry Potter and the Goblet of Fire  
...
