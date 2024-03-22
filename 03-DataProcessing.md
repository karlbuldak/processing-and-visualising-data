# DATA PROCESSING




## Adding Columns

1. Open the notebook extra-columns.ipynb. Learn how to add some extra columns to the existed DataFrame. Then, complete all tasks in the notebook.

1. The continents.csv file contains data on the area and number of inhabitants of some continents. Create a notebook in which create a DataFrame with the data contained in the CSV file. Display the contents of the DataFrame. Then, add a column in which calculate the population density, i.e. the number of inhabitants per 1 km2. View the modified DataFrame.




## Data Sorting

1. Data sorting allows you to arrange data in a specific order. This makes it easier to understand, organize, and find relevant information. As a result, information processing becomes more effective. In addition, presenting data in an orderly manner is more readable for humans. Sorting allows data to be presented in a way that facilitates understanding. And finally, with sorted data, you can make more effective decisions. For example, when analyzing financial data, sorting transactions by date helps you better understand trends.

1. Open the notebook data-sorting.ipynb. Learn how to sort data according to the specified columns. Then, complete all tasks in the notebook.

1. Create a new notebook. Based on the file european-countries.csv, create a DataFrame. Then, do the following tasks:

    * display currency names alphabetically (only one column)
    * display data organised by the population, descending
    * display data organised by the region and then by the country
    * display data organised by the population density (first, add an extra column)
    * display the name of the capital and currency (only two columns), arrange the data by currency and then by the name of the capital city




## Creating Queries

1. Data selection refers to the process of choosing specific data from a larger collection that are relevant to a particular purpose or analysis. It is a crucial step in various fields, including research, business intelligence, data science, and machine learning.

1. The DataFrame contains a query() method that you can use to select data.

1. Open the notebook creating-queries.ipynb. Learn how to select data according to the specified criteria. Then, complete all tasks in the notebook.

1. The cities-in-poland.csv file contains a list of cities in Poland. Open the CSV file in a character editor and familiarize yourself with the data structure of the file. Notice that the data is separated by a semicolon. Find in the Pandas manual how to get data from a CSV file, separated by a semicolon.

    Create a new notebook and read the contents of the CSV file. Then, display file contents. As you can see, due to the volume of the data, only the first and last few rows are displayed. Find out how to display all rows of data. 

    Finally, complete each task in a **separate Code cell**.\
    Copy the command content into a text cell and then add a Code cell below with the solution to the problem.

    * display the first 10 rows of data
    * display all rows of data
    * display last 8 rows of data with columns: City, Province, Population
    * calculate and add population density to the data frame (add a new column)
    * display first 5 rows with columns: City, Density
    * sort cities alphabetically and display the first 10 cities
    * display cities with at least half a million inhabitants (How many such cities are there in Poland?)   
    * display 10 cities with the highest population
    * display 10 cities with the least population
    * display cities from the 'małopolskie' province
    * display cities from the 'małopolskie' province and 'tarnowski' region
    * display cities from the 'małopolskie' province and 'tarnowski' region, sorted by area, starting with the largest one





## Data Grouping

1. Data grouping enables you to apply aggregate functions like COUNT, SUM, AVG, MIN, MAX, etc., to groups of rows based on their values in specified columns. This allows you to summarize data and generate new values representing entire groups. For example, you can count the number of customers in each country, find the average order value for each product category, or identify the highest-grossing month for your online store.

1. Open the notebook data-grouping.ipynb. Learn how to calculate aggregated values based on the specified criteria. Then, complete all tasks in the notebook.

1. Calculate and display the total number of students studying in Warsaw and Krakow. The data is available in the universitites.csv file. Do your calculations in a separate notebook.

1. The list of Polish cities is available in the cities-in-poland.csv file. In a separate notepad, calculate and display:

    * the number of cities in each province
    * the total number of inhabitants in each province
    * the total number of inhabitants in each of the regions in the 'opolskie' province 
    * the total number of inhabitants in each of the regions in the 'opolskie' province; sort the values in descending order




## Data Joining

1. To combine separate datasets, you can some powerful techniques available in pandas. One of them is the merge() function you can use anytime you want functionality similar to a database’s join operations.

1. The pandas merge() function allows you to combine two DataFrames, based on common columns or indexes.

    <https://realpython.com/pandas-merge-join-and-concat/>

1. Open the notebook data-joining.ipynb. Learn how to join some DataFrames using the merge() function. Then, complete all tasks in the notebook.

1. The files krk-airlines.csv, krk-flights.csv and krk-passengers.csv contain data about flights from Krakow Airport. In a separate notebook, calculate and display:

    * list including flight number and destination (two columns)
    * flight list with the full name of the airline and the name of the aircraft
    * a list of passengers on a flight to London sorted by surname
    * a list of women flying to Paris ordered by surname
    * number of passengers on the flight to Berlin
    * number of men flying from Krakow
    * number of passengers for each flight

