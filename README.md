# 🎵 Music Genre Clustering with Machine Learning

## 📌 Project Overview
This project applies unsupervised machine learning techniques to cluster Spotify songs based on their audio characteristics. 
Instead of using predefined genre labels, songs are grouped according to similarity in acoustic features.

https://huggingface.co/spaces/sevvaliclal/ClusteringMusicGenresApp

## 📊 Dataset
- Source: Spotify music dataset
- Number of samples: ~2000 songs
- Data includes various audio features such as BPM, energy, danceability, loudness, and acousticness.

## 🧹 Data Preprocessing
- Removed non-numeric and irrelevant columns (Index, Title, Artist, Genre)
- Converted duration values to numeric format
- Selected only audio-related numerical features
- Applied MinMaxScaler for feature normalization

## 🤖 Modeling
- Used **K-Means clustering** algorithm
- Experimented with different cluster counts
- Evaluated clustering performance using **Silhouette Score**

## 📈 Visualization
- Visualized clusters using 2D and 3D scatter plots
- Analyzed relationships between BPM, Energy, and Danceability

## ✅ Results
The model successfully grouped songs into meaningful clusters based on audio similarity. 
These clusters can be used as a foundation for music recommendation systems.

## 🛠 Technologies Used
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Plotly
- Streamlit
