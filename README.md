# Spotify_Song_Recommedation-VectorDB-
A content-based music recommendation system using Spotify audio features and FAISS vector database to recommend top n similar songs.
 
#  Spotify Song Recommendation System using FAISS

This project implements a **content-based music recommendation system** using the Spotify dataset.  
Given a selected song, the system recommends the **top n most similar songs** based on audio features using a **vector database (FAISS)**.

---

##  Project Overview

Music recommendation systems play a crucial role in enhancing user experience.  
In this project, we leverage **vector similarity search** to efficiently find songs that are similar to a user's selected track.

The workflow includes:
- Feature extraction from Spotify audio data
- Vector embedding creation
- Indexing using **FAISS**
- Similarity-based song recommendations

---

##  Recommendation Approach

- **Type**: Content-Based Filtering  
- **Similarity Metric**: Vector similarity (e.g., L2 / cosine similarity via FAISS)  
- **Recommendation Output**: Top 5 similar songs  

Each song is represented as a numerical vector derived from Spotify audio features such as:
- Danceability  
- Energy  
- Loudness  
- Tempo  
- Valence  
- Acousticness  
- Instrumentalness  

---

##  Tech Stack

- **Python**
- **Pandas & NumPy** – Data processing
- **Scikit-learn** – Feature scaling
- **FAISS (Facebook AI Similarity Search)** – Vector database
- **Jupyter Notebook**





