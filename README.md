# 🎬 Movie Recommendation System
A content-based movie recommendation system built using Python and Pandas with movie information from the TMDB 5000 dataset.
The project recommends movies based on information such as genres, keywords, cast, director and movie overview.

## 🎯 Project Objective
The main objective of this project is to understand how a simple content-based recommendation system can be created using movie
metadata.

## 📊 Dataset
The project uses:
- TMDB 5000 Movies Dataset
- TMDB 5000 Credits Dataset
The two datasets are combined and processed to create useful movie
features.

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
     Tags
        ↓
Recommendation System

## 🛠️ Technologies Used
Python
Pandas
NumPy
Jupyter Notebook

## Recommendation Approach
This project uses a content-based approach.
Movie information is processed into tags containing important movie
features such as genres, keywords, cast, director and overview.
The system then uses these features to find movies with similar
content.

## 📚 What I Learned
Through this project, I practiced:
- Working with multiple datasets
- Merging DataFrames
- Data cleaning
- Text and list processing
- Feature engineering
- Creating movie tags
- Building a basic recommendation system
