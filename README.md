# 🎬 Movie Recommendation System
A content-based movie recommendation system built using Python and Pandas using movie information from the TMDB 5000 dataset.
The system recommends movies based on similarities between movie features such as genres, keywords, cast, director, and overview.

## 🎯 Project Objective
The main objective of this project is to understand how a basic content-based movie recommendation system works, from preparing movie data to generating movie recommendations based on similarity.

## 📊 Dataset
This project uses two datasets from TMDB:
- TMDB 5000 Movies Dataset
- TMDB 5000 Credits Dataset

The two datasets are merged and processed to create useful features for the recommendation system.

## 🔄 Project Workflow
      text
TMDB Movies Dataset
        +
TMDB Credits Dataset
        ↓
      Merge
        ↓
   Data Cleaning
        ↓
  Feature Selection
        ↓
Genres Processing
        ↓
Keywords Processing
        ↓
 Cast Processing
        ↓
Director Extraction
        ↓
Overview Processing
        ↓
  Create Movie Tags
        ↓
Feature Vectorization
        ↓
Similarity Calculation
        ↓
Movie Recommendation

## 🧹 Data Preprocessing
The movie datasets are cleaned and prepared before building the recommendation system.
The preprocessing includes:
- Merging the movies and credits datasets
- Selecting the required columns
- Handling missing values
- Removing unnecessary columns
- Processing genres
- Processing keywords
- Extracting the top 3 cast members
- Extracting the director
- Processing the movie overview
- Combining important features into a tags column
- Converting text to lowercase

## 🏷️ Movie Tags
Important movie information is combined into a single tags column.
The tags contain information such as:
- Movie overview
- Genres
- Keywords
- Top cast members
- Director
These tags are used as the main features for finding similar movies.

## 🤖 Recommendation Approach
This project uses a content-based filtering approach.
The system compares movies based on their content and features rather than relying on user ratings or other users' preferences
The recommendation process follows these steps:
- Select a movie from the dataset.
- Find the index of the selected movie.
- Get the similarity scores for that movie.
- Sort movies based on their similarity scores.
- Select the most similar movies.
- Display the recommended movie titles.

 ## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## 📚 What I Learned
Through this project, I practiced:
- Working with multiple datasets
- Merging DataFrames
- Data cleaning and preprocessing
- Text and list processing
- Feature engineering
- Creating meaningful features from movie metadata
- Working with movie tags
- Measuring similarity between movies
- Building a basic content-based recommendation system
- Writing a recommendation function in Python
  
## 🚀 Future Improvements
Some possible improvements for this project include:
- Building a user-friendly frontend
- Connecting the recommendation system with a web interface
- Adding movie posters and additional movie information
- Improving the recommendation interface
- Deploying the application
