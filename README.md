🎬 Movie Recommendation System (Clustering-Based)

This intelligent unsupervised movie recommendation system uses genre clustering and synthetic features like vote average and popularity to suggest similar movies. Built using Python’s data science stack, it analyzes patterns using K-Means clustering and visualizes results using Matplotlib and Seaborn.

🧪 No explicit user ratings are needed — it uses clustering of genre preferences combined with voting and popularity simulations.

🚀 Run Demo (Locally)
Clone the repo and run the script to see recommendations and cluster visualizations.

🧑‍💻 Access Source Code
👉 GitHub Repository: https://github.com/Piyush-0021/Piyush-0021.github.io

📸 Features

🎞️ Reads and cleans IMDB movie dataset (1951–2023)
🧠 Parses and encodes genre metadata using ast and MultiLabelBinarizer
📊 Clusters movies using KMeans into genre-based groups
📈 Computes Silhouette Scores to choose optimal k
🎨 Visualizes genre clusters and distributions
🎯 Recommends similar movies based on cluster proximity
🧪 Simulates vote_average and popularity for ranking results
📁 Fully modular and easy to customize with real ratings

### 🛠️ Tech Stack

| Data Handling         | Clustering & Encoding     | Visualization | Other Tools         |
|-----------------------|---------------------------|---------------|---------------------|
| pandas                | scikit-learn (KMeans)     | matplotlib    | ast (genre parsing) |
| numpy                 | MultiLabelBinarizer       | seaborn       |                     |
| CSV dataset (IMDB)    | MinMaxScaler              |               |                     |
	
📌 How It Works

Cleans and normalizes movie titles and genres.
Converts genres from strings to structured lists.
Encodes genre combinations into binary vectors.
Adds simulated numerical features (vote_average, popularity).
Applies MinMax Scaling to normalize inputs.
Uses KMeans to group similar movies.
Recommends N movies from the same cluster, sorted by quality signals.
