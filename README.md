# Suggesteria



### Anime Recommendation System – Content-Based Filtering

Developed a content-based recommendation system to suggest anime titles similar to a user-selected input using textual metadata. The model relies on features such as name, genre, and type to compute similarity scores and deliver relevant recommendations.

**Core Features:**

* **Content-Based Filtering:** Identifies similar anime using metadata fields (name, genre, type).
* **TF-IDF Vectorization:** Transforms textual metadata into numerical vectors for comparison.
* **Cosine Similarity:** Computes pairwise similarity between anime based on their vector representations.
* **Pickled Components:** Stores the trained TF-IDF vectorizer and similarity matrix for fast loading and reuse.
* **Interactive Web App:** Built with Streamlit for a user-friendly and responsive interface.

**How the System Works:**

1. **Data Cleaning:** Preprocesses the dataset and handles missing values.
2. **Feature Engineering:** Merges key metadata into a unified text format.
3. **Vectorization:** Converts combined text into TF-IDF vectors.
4. **Similarity Computation:** Applies cosine similarity to measure closeness between anime entries.
5. **Recommendation Engine:** Returns the top *k* most similar titles based on user input.
6. **User Interface:** Streamlit enables real-time input and interactive display of recommendations.

**Technologies Used:**
Python, Pandas, NumPy, Scikit-learn, Streamlit, Pickle
TF-IDF (TfidfVectorizer), Cosine Similarity


