# ETL Operations on Country-GDP Data

## What's This Project About?
Dive into the world of ETL (Extract, Transform, Load) operations where we will be pulling data about the largest banks from a website, transforming that data into something more useful, and then saving it to both a CSV file and a database. Plus, we throw in some cool SQL queries to see the data in action!

## What You Need
- Python 3.x
- BeautifulSoup4
- Requests
- Pandas
- Numpy
- SQLite3

Install everything you need with this command:
```sh
pip install beautifulsoup4 requests pandas numpy
```

## What’s Inside
1. **Logging Function:** Logs our journey through the code execution to a log file.
2. **Extract Function:** Grabs data from a URL and load it into a DataFrame.
3. **Transform Function:** Converts the market cap from USD to GBP, EUR, and INR using exchange rates from a CSV file.
4. **Load Functions:** 
    - Save the transformed data to a CSV file.
    - Save the transformed data to a SQLite database.
5. **Query Function:** Runs some SQL queries and prints out the cool stuff we find.

## How It All Works
1. **Define Your Playground:**
    - The URL of the Wikipedia page with our bank list.
    - The columns we want in our DataFrame.
    - Paths for the CSV file and the database.

2. **Log Your Journey:**
    - Start logging the ETL process.

3. **Extract the Good Stuff:**
    - Fetch the webpage, parse the HTML, and pull out the table data into a DataFrame.
    - Log that you’ve extracted the data.

4. **Transform Like a Boss:**
    - Read the exchange rates from a CSV file.
    - Add new columns for market caps in GBP, EUR, and INR.
    - Log that the transformation is done.

5. **Load and Save:**
    - Save the transformed DataFrame to a CSV file.
    - Log that you’ve saved to CSV.
    - Connect to a SQLite database and save the DataFrame as a table.
    - Log that the data is now in the database.

6. **Query the Cool Stuff:**
    - Display the entire table.
    - Calculate and display the average market cap in GBP.
    - Show the names of the top 5 banks.
    - Log that you’ve completed the process.

7. **Wrap It Up:**
    - Close the database connection.

Happy coding and enjoy the ride! 🚀
