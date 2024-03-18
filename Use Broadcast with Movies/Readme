This Spark project aims to analyze movie ratings data to identify the most popular movies. The dataset used in this project is the MovieLens 100K dataset.
Overview:

The goal of this project is to determine the top 10 most popular movies based on the number of ratings they have received.
Setup:

To run this project, ensure you have the following dependencies installed:

bash

pip install pyspark

Instructions:

    Mount Google Drive: This project assumes the dataset is located in Google Drive. Ensure you mount your Google Drive by running the provided code.

    Load Dataset: The movie ratings dataset is loaded from Google Drive using PySpark's DataFrame API.

    Define Functions: Two functions are defined:
        loadMovieNames(): Loads movie names from a file and returns them as a dictionary.
        lookupName(): A user-defined function (UDF) that maps movie IDs to their respective names.

    Analyze Data:
        Group the movies by ID and count the number of ratings each movie has received.
        Add a new column to the DataFrame containing the movie titles by applying the lookupName() UDF.
        Sort the results by the count of ratings in descending order.

    Display Results:
        Show the top 10 most popular movies along with their titles.

Project Structure:

    PopularMovies.ipynb: Jupyter Notebook containing the project code.
    ml-100k: Directory containing the MovieLens 100K dataset.
        u.data: Movie ratings data file.
