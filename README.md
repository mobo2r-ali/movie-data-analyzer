# IMDB-movie-data-analyzer

An exploratory data analysis project on the IMDb Top 1000 Movies dataset using Python, Pandas, and Matplotlib.

Project Overview

This project explores the IMDb Top 1000 Movies dataset to identify patterns in movie ratings, genres, directors, votes, and box office revenue.

Dataset

- Source: "IMDb Top 1000 Movies Dataset" (https://huggingface.co/datasets/drossi/EDA_on_IMDB_Movies_Dataset)
- Total records: 1,000 movies
- Total columns: 16

Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

Project Structure

movie-data-analyzer/
├── data/
│   └── movies.csv
├── notebooks/
│   └── movie_analysis.ipynb
├── .gitignore
├── requirements.txt
├── README.md
└── LICENSE

Analysis Performed

1. Data Inspection and Cleaning

- Inspected dataset structure and data types.
- Checked missing values and duplicate records.
- Corrected an invalid release year.
- Converted runtime and gross revenue columns to numeric types.

2. IMDb Rating Analysis

- Calculated average, maximum, and minimum ratings.
- Identified top-rated movies.
- Compared average ratings across decades.

3. Genre Analysis

- Counted movies in each genre.
- Compared average IMDb ratings by genre.
- Identified the most frequent genres.

4. Director Analysis

- Identified directors with the most movies.
- Compared average ratings for directors with at least five movies.

5. Movie Analysis

- Identified movies with the highest number of votes.
- Identified movies with the highest gross revenue.

Key Findings

- The average IMDb rating in the dataset is approximately 7.95.
- Drama is the most frequent genre, appearing in 724 movies.
- War has the highest average genre rating, approximately 8.01.
- Alfred Hitchcock has the most movies in the dataset, with 14.
- Christopher Nolan has the highest average rating among directors with at least five movies, approximately 8.46.
- The Shawshank Redemption has the highest number of votes.
- Star Wars: Episode VII - The Force Awakens has the highest gross revenue in the dataset.

Visualizations

The project includes visualizations for:

- Average IMDb rating by decade
- Top 10 movie genres
- Top 10 directors by number of movies
- Top 10 movies by number of votes
- Top 10 highest-grossing movies
- Distribution of IMDb ratings

Installation and Usage

Clone the repository:

git clone https://github.com/mobo2r-ali/movie-data-analyzer.git

Navigate to the project directory:

cd movie-data-analyzer

Install the required libraries:

pip install -r requirements.txt

Open Jupyter Notebook:

jupyter notebook

Then open "notebooks/movie_analysis.ipynb" and run the cells.

Author

GitHub: "mobo2r-ali" (https://github.com/mobo2r-ali)