# Data Sourcing Challenge

## Project Overview

In this project, I prepared some data for a recommendation system to help people find movie reviews and related movies. The data is extracted from two different sources: The New York Times API and The Movie Database API, then merged together. The text extracted from these APIs can later be used with natural language processing methods.

There are three parts to this project:
1. **Access the New York Times API**: Retrieve movie reviews.
2. **Access The Movie Database API**: Retrieve detailed movie information.
3. **Merge and Clean the Data for Export**: Combine the data from both sources and clean it for further analysis.

### Summary Analysis of Project's Findings:
1. The data includes movie reviews with associated metadata such as genres, spoken languages, and production countries.
2. The merging of the data sources allows for a comprehensive dataset that can be used for: 
- Recommendation Systems: The dataset can be used to build recommendation systems, suggesting movies based on genres, popularity, and reviews.
- Sentiment Analysis: The text data from reviews can be analyzed for sentiment, providing insights into the critical reception of movies.
- Trend Analysis: The dataset allows for the analysis of trends over time, such as changes in popular genres or shifts in movie review sentiments.


## Directory Structure
```
data-sourcing-challenge/
│
├── retrieve_movie_data.ipynb # Contains the implementation of the project
├── clean_data.csv # Output file of the project
├── README.md # Project README file
├── LICENSE # License information for the project
└── api_keys.env # API keys used in this project
```

## Project Files

### `retrieve_movie_data.ipynb`
This Jupyter notebook contains the complete implementation of the project. It includes code for accessing the APIs, processing the data, merging the data frames, and cleaning the data for export.

### `clean_data.csv`
This file is the cleaned and merged data resulting from the project. It includes movie reviews from The New York Times and detailed movie information from The Movie Database. 

### `LICENSE`
This project is licensed under the Unlicense, a public domain dedication. Feel free to use, modify, and distribute this project without any restrictions.

### `api_keys.env`
This file contains the API keys used in this project. This file is kept secure and not shared publicly.


## How to Use

1. Clone the repository:
    ```
    git clone https://github.com/your-username/data-sourcing-challenge.git
    cd data-sourcing-challenge
    ```
2. Set up the environment variables by creating a `.env` file with your API keys. Use `api_keys.env` as a template.
3. Open `retrieve_movie_data.ipynb` in Jupyter Notebook and run the cells to execute the project.

### Note
The implementation code for this project can be found in the `retrieve_movie_data.ipynb` file within the repository.

## License
This project is licensed under the Unlicense. For more details, see the `LICENSE` file.
