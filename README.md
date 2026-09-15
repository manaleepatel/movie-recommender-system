🎬 Movie Recommendation System

A **Content-Based Movie Recommendation System** built using Python and Machine Learning. The system recommends **5 movies similar to a movie selected by the user** based on the movie's content and features.

🚀 Project Overview

In this project, I developed a movie recommendation system that analyzes movie information and identifies movies with similar characteristics.

The project uses **Bag of Words (BoW)** for text vectorization to convert movie features into numerical vectors. **Cosine Similarity** is then used to measure the similarity between movies and generate the top 5 recommendations.

The application is built with **Streamlit** and includes **API integration for dynamically retrieving movie posters**, making the recommendation interface more interactive and visually appealing.

🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and preprocessing
* **NumPy** – Numerical operations
* **Scikit-learn** – Text vectorization and similarity calculation
* **Seaborn** – Data visualization and exploratory data analysis
* **Streamlit** – Web application development and deployment
* **Bag of Words** – Text feature vectorization
* **Cosine Similarity** – Finding similar movies
* **Fanart API** – Retrieving movie poster artwork
* **API Integration** – Fetching poster information dynamically

⚙️ How It Works

1. Movie data is loaded and cleaned using Pandas.
2. Relevant movie features are combined to create a text-based representation.
3. The text data is converted into numerical vectors using the **Bag of Words** technique.
4. **Cosine Similarity** is calculated between movie vectors.
5. When a user selects a movie, the system finds the **5 most similar movies**.
6. An API is used to retrieve posters for the recommended movies.
7. The recommendations and posters are displayed through a **Streamlit web application**.

🎯 Key Learning Outcomes

Through this project, I practiced:

* Data preprocessing and exploratory data analysis
* Text feature extraction using Bag of Words
* Cosine similarity
* Building a content-based recommender system
* API integration and dynamic data retrieval
* Building an interactive interface with Streamlit
* Deploying a Data Science project as a web application

🌐 Deployment

The project is deployed using **Streamlit Community Cloud**.

📌 Project Type

**Data Science | Machine Learning | Recommendation System | API Integration | Streamlit**
