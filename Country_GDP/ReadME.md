# ETL Fun with Country-GDP Data

## What's This Project About?
Welcome to this fun ETL (Extract, Transform, Load) project where we work with GDP data from different countries. We are going to pull data from a website, prettify it, and then save it both as a CSV file and into a database. Plus, we’ll run some cool SQL queries to see what we’ve got!

## Requirements
- BeautifulSoup4
- Requests
- Pandas
- Numpy
- SQLite3

You can install these libraries using the following command:
```sh
pip install beautifulsoup4 requests pandas numpy
```

## Project Structure
1. **Logging Function:** Keeps a log of our ETL adventure.
2. **Extract Function:** Grabs GDP data from a URL and drops it into a DataFrame.
3. **Transform Function:** Converts GDP from millions to billions of USD.
4. **Load Functions:** 
    - Save the transformed DataFrame to a CSV file.
    - Save the transformed DataFrame to a SQLite database.
5. **Query Function:** Runs SQL queries to show off our data.

## How It Works
1. **Set Up Your Playground:**
    - The URL of the Wikipedia page with our GDP data.
    - The column names for our DataFrame.
    - Paths for our CSV file and the SQLite database.

2. **Log Your Journey:**
    - Start logging the ETL fun.

3. **Extract the Goods:**
    - Fetch the webpage, parse the HTML, and pull out the GDP data into a DataFrame.
    - Log the successful extraction.

4. **Transform Like a Pro:**
    - Convert GDP values from millions to billions of USD.
    - Rename the column to reflect the new units.
    - Log the successful transformation.

5. **Load and Save:**
    - Save the DataFrame to a CSV file.
    - Log the successful CSV save.
    - Connect to a SQLite database and save the DataFrame as a table.
    - Log the successful database save.

6. **Run Cool Queries:**
    - Run SQL queries to show off the data.
    - Log the successful querying.

7. **Wrap It Up:**
    - Close the database connection and call it a day.
      
Happy coding and have a blast with ETL! 🚀
