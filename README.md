# movie_recommendation
🎬 <b>Movie Recommendation System :</b>
<br>A machine learning-based system that suggests movies to users based on their preferences using content-based filtering and/or collaborative filtering techniques. This project demonstrates the application of recommendation algorithms to provide personalized movie recommendations.

📌 <b>Features : </b>
🔍<br> Recommends similar movies based on a selected movie (Content-Based Filtering)<br>
🧠 Uses NLP techniques on movie metadata (like genres, cast, overview, etc.)<br>
📈 Visualizes similarities using cosine similarity and vectorization<br>
📦 Easily deployable using Streamlit (or Flask if used)<br>
🎯 Accurate and efficient with minimal latency in recommendations

🛠️ <b>Tech Stack :</b>
<br>Python<br>
Pandas, NumPy – Data manipulation<br>
Scikit-learn – Vectorization and similarity calculation<br>
NLTK / spaCy – Text preprocessing (if applicable)<br>
Jupyter Notebook – Development and visualization

📁 <b>Dataset :</b>
<br>The dataset used is from TMDb 5000 Movie Dataset containing metadata like title, genres, cast, crew, keywords, overview, etc.

🧠 <b>Recommendation Approach :</b>
<br>Content-Based Filtering: Recommends movies based on movie metadata such as genre, cast, and overview using TF-IDF/CountVectorizer and cosine similarity.
