# Top 10000 Popular Movies Analysis

This project is focused on analyzing a dataset of the top 10,000 popular movies. The dataset includes various attributes such as budget, revenue, popularity, vote average, and more. The goal of this project is to explore and gain insights from the dataset using data manipulation, visualization, and statistical analysis techniques.

## Project Structure 🔗

|**Sr.No. 🔢**|**References 👨‍💻**| **Links :link:**|
|------|--------------------|---------------------|
|1| ** Excel Dataset ** | [Dataset](https://github.com/Mahesh-Chincholkar/Top-Popular-Movies-Analysis/blob/main/movies.csv)|
|2| ** Excel Dataset ** | [Dataset](https://github.com/Mahesh-Chincholkar/Top-Popular-Movies-Analysis/blob/main/popular_10000_movies_tmdb.csv)|
|3| **Jupytr Notebook File** | [Jupytr Python File](https://github.com/Mahesh-Chincholkar/Top-Popular-Movies-Analysis/blob/main/Top%20Popular%20Movies%20Analysis.ipynb) |

## Libraries Used ⚙️

The project utilizes the following Python libraries:

* <a href="https://numpy.org/" target="_blank" rel="noreferrer">Numpy <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="numpy" width="40" height="40"/></a>

* <a href="https://jupyter.org/" target="_blank" rel="noreferrer">Jupytr <img src="https://github.com/Pavan-Jadhav/Pavan-Jadhav/blob/main/icons8-jupyter.svg" alt="jupyter" width="40" height="40"/> </a>

* <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer">Pandas <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a>

* <a href="https://www.python.org" target="_blank" rel="noreferrer">Python <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>


## Data Preprocessing

The dataset undergoes several preprocessing steps to clean and prepare the data for analysis. The preprocessing steps include:

- Dropping irrelevant columns such as `id`, `overview`, and `tagline`.
- Handling missing values by dropping rows with null values.
- Removing rows with non-standard or invalid language codes.
- Removing duplicate entries and empty genre/production company columns.
- Dropping rows with zero values in important columns.
- Adding a new column for the profit calculation.

## Data Analysis

The project performs various data analysis tasks to gain insights from the dataset. The analysis includes:

- Identifying the top 10 movies based on budget, revenue, profit, popularity, vote count, and vote average.
- Visualizing the top 10 movies for each category using bar plots.
- Counting the movies based on their original language.
- Determining the most popular and profitable movies for each genre.
- Identifying the top 5 production companies with the highest movie count.
- Finding the most popular movie for every 5-year period.
- Analyzing the average popularity, vote count, vote average, budget, revenue, and profit over time.
- Visualizing the trends in movie count over time.

## Conclusion

This project provides valuable insights into the top 10,000 popular movies dataset. The analysis highlights the movies with the highest budget, revenue, profit, popularity, vote count, and vote average. It also explores the distribution of movies based on original language, genre, and production companies. Additionally, it examines the trends and patterns in popularity, vote count, vote average, budget, revenue, and profit over time. The findings contribute to a better understanding of the movie industry and its evolving dynamics.

Feel free to explore the Jupyter Notebook file (`Top Popular Movies Analysis.ipynb`) to dive into the code and interact with the dataset. The cleaned dataset is also available in the `movies.csv` file for further analysis.
