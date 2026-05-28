# python-ds-module-2-Data-Collection
DATA COLLECTION:
Data collection is the systematic process of gathering and measuring information from various sources to answer research questions, evaluate outcomes, and inform decision-making.

#Data Collection Techniques::

1. Web Scraping:
   Web Scraping is the automated process of extracting large amounts of data from websites.

 ## Web Scraping Project::
This project demonstrates basic web scraping using Python.
I collected book-related data from the website `books.toscrape.com` using the BeautifulSoup (bs4) library in Google Colab.

### Tools & Libraries Used
- Python
- Google Colab
- Requests Library
- BeautifulSoup (bs4)

### Project Workflow::
- Imported BeautifulSoup from bs4
- Used the Requests library to send HTTP requests
- Applied the `get()` method to access webpage content
- Parsed HTML data using BeautifulSoup
- Extracted book information from the websites
- Extracting Book Information
   The `find_all()` method was used to extract:
       Book titles
       Book prices

  2. API HANDLING:
      API (Application Programming Interface) handling in data collection refers to the process of programmatically                requesting and retrieving data from a web service.

     ##  API Handling Project Using Python ::
This project demonstrates API handling using Python by fetching live weather data from the OpenWeatherMap API for multiple cities.
The project was implemented in Google Colab using Python libraries such as Requests and Pandas.

##  Libraries & Tools/Technologies Used
- requests
- pandas
- Python
- Google Colab
- OpenWeatherMap API

## Project Workflow

### 1. API Integration
Used the OpenWeatherMap API with a unique API key to access real-time weather information.
### 2. Sending HTTP Requests
The `requests.get()` method was used to send API requests for different cities.
### 3. Fetching JSON Data
The response data was collected in JSON format using the `response.json()` method.
### 4. Extracting Weather Information
Extracted:
- Temperature  - Humidity   - Pressure   - Weather Description   - Wind Speed
### 5. Creating DataFrame
The collected weather data was stored in a list and converted into a Pandas DataFrame for structured analysis.

3.SQLite 3
SQLite 3 is a lightweight, serverless database engine that is ideal for data collection. It stores an entire database in a single file, making it a popular choice for logging IoT sensor streams, web scraping, and local application data without requiring a dedicated database server. 

##  SQLite Database Handling using Python::

This project demonstrates database handling using SQLite3 and Pandas in Python.

The project creates a database, stores student records, performs data analysis, and displays the results using Pandas DataFrames.

##  Libraries & Tools/Technologies Used
- sqlite3
- pandas
- Python
- SQLite Database
- Google Colab

##  Project Workflow:
### 1. Database Connection
Used the `sqlite3.connect()` method to create and connect to the SQLite database.
### 2. Table Creation
Created a `users` table containing:
- ID
- Name
- Age
- Marks
### 3. Inserting Records
Inserted multiple student records into the database using the `executemany()` method.
### 4. Fetching Data
Retrieved data from the database using SQL queries and stored it in a Pandas DataFrame.
### 5. Data Analysis
Performed different operations such as:
- Calculating mean marks
- Finding students with marks greater than mean
- Creating a list of student names
- Finding the lowest 5 marks
- Sorting data by age

  4.CSV/EXCEL :
  CSV and Excel are two foundational tools for data collection. CSV (Comma-Separated Values) acts as a universal,              lightweight text file that securely stores raw data. Excel is a full-featured spreadsheet application used to build data     collection forms, format entries, and perform advanced analysis.

  ## 📄 CSV File Handling using Python::
This project demonstrates CSV file handling and data analysis using Pandas in Python.
The dataset was uploaded and analyzed in Google Colab to explore dataset structure, missing values, statistics, and categorical information.

## Libraries & Tools/Technologies Used
- pandas
- google.colab.files
- Python
- Google Colab
- CSV Dataset
- Pandas DataFrame

##  Project Workflow:
### 1. Uploading CSV File
Used `files.upload()` from Google Colab to upload the CSV dataset.
### 2. Reading Dataset
Loaded the dataset using the `pd.read_csv()` function.
### 3. Exploring Dataset
Performed different dataset inspection operations such as:
- Displaying first 5 rows using `head()`
- Displaying last 5 rows using `tail()`
- Checking dataset information using `info()`
- Finding dataset shape using `shape`
- Viewing column names
### 4. Handling Missing Values
Checked missing/null values using the `isnull().sum()` method.
### 5. Statistical Analysis
Generated statistical summary using `describe()`.
### 6. Data Analysis
Performed analysis such as:
- Gender count
- Survival count
- Average age calculation
- Passenger class count
- Displaying selected column

  

