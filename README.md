# Hyrox Web Scraper
This project is a web scraper designed to collect detailed information about participants from the Hyrox race event website. It is implemented using Python and utilizes libraries such as requests, BeautifulSoup, and csv for web scraping and data handling.

# Features
Scrapes participant details, scoring information, workout results, and overall times from the Hyrox website.
Dynamically constructs URLs to access race event pages based on specified seasons and divisions.
Handles pagination to ensure comprehensive data collection across multiple pages.
Extracts additional information such as gender and event ID from the URL query parameters.
Flattens nested data structures and organizes the scraped data into a structured format.
Saves the scraped data to a CSV file for further analysis or use in other applications.
Provides progress tracking and time estimation during the scraping process.

# Usage
Copy Collab Notebook: https://colab.research.google.com/drive/1HGHGh4XYU-Vx9T4NOTK4PkbCehHPGkEB?usp=drive_link

# Data Structure
The scraped data is structured as follows:

Participant details are stored in a dictionary with keys such as "Name", "Age Group", "Number", and "Nat".
Scoring information is stored in a dictionary with keys such as "Division" and "Race".
Workout results are stored as a list of dictionaries, each containing the split name, time, and place.
Overall time is stored in a dictionary with keys such as "Overall Time", "Rank (AG)", and "Rank (M/W)".
Gender and event ID are extracted from the URL query parameters and added as separate fields.
The data is flattened and organized into a CSV file with the following columns:

Event ID
Participant_Name
Gender
Participant_Age Group
Participant_Number
Participant_Nat
Scoring_Race
Scoring_Division
Overall Time_Rank (M/W)
Overall Time_Rank (AG)
Overall Time_Overall Time
Specific split columns (e.g., Running_1, 1000m_SkiErg, etc.)
Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.
