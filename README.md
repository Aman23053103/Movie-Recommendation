# 🎬 Movie Recommendation System

A content-based movie recommender system built using **TF-IDF Vectorization** and **Cosine Similarity**, which suggests movies similar to a user's favorite based on genres, keywords, taglines, cast, and director metadata.

## 🚀 Features

- Real-time movie suggestions based on user input
- Text feature engineering from multiple metadata columns
- TF-IDF Vectorization to convert text into feature vectors
- Cosine Similarity to measure movie similarity
- Handles fuzzy inputs using string matching (`difflib`)
- Recommends Top 30 similar movies
- Clean and interactive terminal-based interface

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**:
  - `pandas` – data handling
  - `numpy` – numerical operations
  - `scikit-learn` – TF-IDF and cosine similarity
  - `difflib` – fuzzy string matching
  - `os` – file and directory handling

## 📁 Dataset

The project uses a `movies.csv` dataset with the following key columns:
- `genres`
- `keywords`
- `tagline`
- `cast`
- `director`
- `title`
- `index`

> Make sure the dataset is placed in the same directory or update the path accordingly.

## 📦 Setup Instructions

1. Clone this repository or download the source code.
2. Place `movies.csv` in the project directory.
3. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn
