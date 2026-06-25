# Netflix_Recommendation_ML-model
From the Data-Analysis to ML-model...
Building a Content-Based Netflix Recommender System! 🎬
Here’s a quick snapshot of the machine learning pipeline I just built to recommend movies and TV shows:

Data Exploration (EDA): Analyzed over 8,800+ titles to uncover content trends, top genres (International Movies & Dramas), and distribution patterns over the years.

Feature Engineering: Combined key textual features—including director, cast, listed_in (genres), and description—into a unified metadata profile for every title.

Natural Language Processing (NLP): Cleaned text data and transformed it into numerical vectors using a TF-IDF Vectorizer to capture the essence of the content.

Similarity Engine: Computed a Cosine Similarity Matrix to calculate exactly how close any two titles are based on their metadata profiles.

Fuzzy Search Integration: Upgraded the system with RapidFuzz so it seamlessly handles typos and approximate names (like searching "interstelar" and still getting perfect recommendations!).

Production Ready: Modulized the engine into a clean, reusable Python class (recommender.py) and serialized the assets using joblib for quick deployment.
