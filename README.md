# IMDb Top 50 Movies with the most number of votes

This is a simple web scraper built to extract data from the IMDb website's top movies page. The webpage lists the top 50 movies with the most number of votes along with details such as release date, runtime duration, cast, genre, ratings, and more.

## How It Works

1. Reading: The scraper reads the HTML content of the IMDB webpage using Python's requests library.

2. Parsing: The BeautifulSoup library is used to parse and beautify the HTML code, making it more understandable and easier to work with.

3. Extraction: The required movie-related information, such as title, year, director, genre, duration, gross, votes, rating is extracted from the webpage using BeautifulSoup's parsing methods.

4. Transformation: The extracted data is transformed into a structured format, such as a CSV file, making it easy to store, analyse or share the data.

5. Data Analysis: We will use pandas to clean and analyse the data.

6. Data Visualisation: We will create visualisations using seaborn to answer some of the questions.


## Dependencies

- Python 3.x
- requests library
- BeautifulSoup library
- Pandas
- Seaborn
- Matplotlib

## Getting Started

Open the file "Web_scrapping_IMDb.ipynb" and follow the steps.

## Output

The script will generate a CSV file named "Top_votes_movies.csv" containing the extracted data. It will include columns such as title, year, director, genre, duration, gross, votes and rating for each of the top 50 movies with the most votes (you can add more variables).

## Analysing and visualising data

Now we have collected information on movies, we'll answer some questions: open the file named "IMDb_analysis.ipynb" and follow the steps.

## Contribution

This project was realised during a course at TechTalent Academy.
Contributions are welcome and encouraged! If you find any bugs, have feature requests, or want to improve the project, feel free to open an issue or submit a pull request. 

## Source 

http://www.imdb.com/search/title?sort=num_votes,desc&start=1&title_type=feature&year=1950,2012
