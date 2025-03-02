# Recommendation System Project 🔎

## Overview
This project implements a content-based filtering recommendation system for streaming data, following a DataCamp tutorial. The knowledge gained here will be applied to develop a recommendation system for a personal shopper AI agent.

📆 **Project completed 03-02-2025**

## Features
- Content-based filtering approach
- Streaming platform data cleaning and analysis
- Cosine similarity calculations
- TF-IDF Vectors

## Technologies Used
- Python
- Pandas/NumPy (for data manipulation)
- Scikit-learn (for vector operations)
- Seaborn/Matplotlib (for data visualization)

## Implementation Details
- Feature extraction from content metadata
  -> numercial-only and numerical/textual approach
- Vector representations of user preferences
- Cosine similarity for matching

## Results
- The initial content-based filtering system only used similarities in streaming platform to provide recommendations. While this can be a good system for Disney+ since the movies are generally targeting the same audience, this approach does not extend as well to platforms like Netflix that have a wide range of material.
- The improved system also used Rotten Tomatoes scores, the audience age, and the year the movie was released to help round out the recommendations. This approach greatly improved the overall utility of the recommendation system across all movies on the different streaming platforms.

## Future Work
- With additional data, the recommendation system could be improved even more based on details like the genre of the movie and the IMDb rating.
- Given data about the people who watch these movies, a collaborative filtering approach could be implemented based on movies that are typically watched by a common demographic. 
- If all of this additional data were present, the next thing would be to explore hybrid approaches to leverage both the movie similarities, and those of their watchers. 
- Develop a recommendation system model for the Personal Shopper AI project. 

## Getting Started
```bash
# Clone repository
git clone https://github.com/JessicaChildress/RecommendationSystemProject.git

# Install dependencies
pip install -r requirements.txt

# Run the recommendation engine by launching jupyter
jupyter notebook
```

## Data & Acknowledgements
- The data used in this project is from Kaggle: https://www.kaggle.com/datasets/ruchi798/movies-on-netflix-prime-video-hulu-and-disney/data
- This project was developed by following along with this tutorial from DataCamp: https://www.datacamp.com/tutorial/streaming-platform-analysis
- Additional details on recommendation systems were gathered from NVIDIA's glossary: https://www.nvidia.com/en-us/glossary/recommendation-system/ 
