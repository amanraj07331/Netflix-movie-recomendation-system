# Netflix Movie and Series Recommendation Syste
## Introduction
This project presents a Netflix Movie and Series Recommendation System built using data available up to 2024. It employs content-based filtering techniques to offer personalized recommendations to users, enhancing their experience by helping them discover movies and TV shows that align with their preferences.

## Objective
The primary goal is to develop a recommendation system that suggests relevant and engaging content (movies and series) based on user interests. By leveraging textual and metadata features such as titles, genres, cast, and descriptions, the system generates intelligent recommendations using natural language processing and similarity metrics.

## Datasets
1. **Netflix Dataset**: Contains comprehensive information about movies and series available on Netflix until 2024. Key features include titles, descriptions, cast, director, and genre.
2. **IMDb Dataset**:
   - `IMDb ratings.csv`: Includes IMDb ratings data.
   - `IMDb movies.csv`: Contains information about movie titles, years, and genres.

## Methodology
1. Data Preprocessing
Cleaning and standardizing textual data

Handling missing values

Creating a unified text format for analysis

2. Feature Engineering
TF-IDF Vectorization for analyzing movie/series descriptions

Creation of a "feature soup" combining title, cast, genre, director, and description

Count Vectorization for handling multiple combined textual features

3. Recommendation Techniques
TF-IDF Based Content Filtering

Calculates cosine similarity between descriptions

Returns recommendations based on semantic content similarity

Multi-Feature Content Filtering

Builds a weighted feature soup

Uses Count Vectorizer + Cosine Similarity to provide nuanced suggestions

4. Deployment
Deployed using Streamlit, enabling an interactive web-based interface

Users can input a movie/series name and receive real-time recommendations

The deployment code is included in the repository

🚀 How to Run
# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py



## Conclusion
This project demonstrates the effectiveness of content-based filtering techniques for building a recommendation system tailored to both movies and series. By analyzing various features from the Netflix dataset and incorporating additional IMDb data, the system provides users with relevant suggestions. For practical use, the system has been deployed using Streamlit, and a file with the Streamlit deployment code is attached in the repository.

## Additional Information
There is also a file attached in the repository where the recommendation system is deployed using Streamlit, allowing users to interact with the system through a web interface.

---
In case Of any query feel free to mail me at amanraj07331@gmail.com
