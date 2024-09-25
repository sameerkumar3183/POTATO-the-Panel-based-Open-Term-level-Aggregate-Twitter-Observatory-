# POTATO-the-Panel-based-Open-Term-level-Aggregate-Twitter-Observatory-
A Flask-based project for analyzing Twitter data. It ingests tweet data from TSV files and allows users to search for terms, 
retrieving insights like tweet counts, unique users, average likes, and more. Simple to 
set up, with optional Docker support and well-documented for easy use and extension.
=======================================================================================================
Twitter Data Analysis with Flask
This project provides a simple solution for analyzing tweet data, allowing users to search for terms and retrieve various insights. It ingests data from a TSV file containing tweets, organizes it, and provides a searchable interface built with Flask.
====================================================================================================
Features:
Data Ingestion: Loads and structures tweet data from TSV files to facilitate efficient querying.
Search Functionality: Allows users to search tweets based on specific terms and retrieve statistics such as:
Number of tweets posted per day.
Number of unique users who tweeted.
Average likes per tweet.
Locations from where the tweets were posted.
Times of day when tweets were posted.
User with the most tweets containing the search term.
Flask Web Interface: A simple, intuitive web app built with Flask to perform searches and display results.
How to Run:
Clone the repository: git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
Install dependencies: pip install -r requirements.txt
Run the Flask app: python app.py
Access the app at http://127.0.0.1:5000 in your browser.
Optional Features:
Docker containerization for easy setup.
NoSQL support (e.g., MongoDB).
Unit testing using pytest.
API endpoint construction using Flask.
Feel free to explore and contribute!
