# 🌴 Honolulu Climate Analysis & API

For this project, I conducted a climate data analysis from Honolulu, Hawaii. The purpose of the project was to better understand the weather patterns that travlers can use and take in cosideration before making plans. This project involved two main parts:

1. Climate Data Exploration using Python, SQLAlchemy, Pandas, and Matplotlib

2. Designing a Flask API to serve key climate metrics

# 📊 Part 1: Data Analysis & Exploration
Using the provided SQLite database (hawaii.sqlite) and a starter notebook (climate_starter.ipynb), I analyzed climate trends in Honolulu. Here's how I approached it:

# 🔗 Database Setup

- Connected to the SQLite database using SQLAlchemy’s create_engine()

- Reflected existing tables using automap_base() and mapped them to Station and Measurement classes

- Created a session to enable querying and closed it when finished

# 🌧️ Precipitation Analysis

- Queried the most recent date in the dataset

- Pulled precipitation data for the last 12 months prior to that date

- Loaded the data into a Pandas DataFrame and sorted by date

- Plotted the daily precipitation levels

- Displayed summary statistics using describe()

# 🛰️ Station Analysis

- Counted the total number of weather stations in the dataset

- Identified the most active stations based on observation count

- Focused on the most active station to:

  1. Retrieve its min, max, and avg temperature
  2. Pull temperature observations (TOBS) for the previous year
  3. Visualize the TOBS data as a histogram with 12 bins

# 🌐 Part 2: Climate API with Flask
After completing the analysis, I created a Flask API to expose key endpoints for dynamic climate data retrieval.

# 🔧 Notes & Tools Used

-Database: SQLite

- Libraries: SQLAlchemy, Pandas, Matplotlib, Flask

- Visualization: Line plots & histograms

- Techniques: ORM mapping, dynamic routing, JSON response formatting

This project sharpened my skills in data wrangling, API design, and delivering analysis in a user-friendly format.
