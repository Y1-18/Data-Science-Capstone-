🧠 Data Science Capstone Projects Repository

This repository contains two major end-to-end data science projects developed using Python and Jupyter Notebooks. Each project demonstrates practical applications of data collection, analysis, and visualization techniques within real-world contexts.

🚀 Project 1: SpaceX Falcon 9 First Stage Landing Prediction

This project focuses on predicting whether the first stage of a SpaceX Falcon 9 rocket will successfully land — a critical factor in determining the cost efficiency of space missions.

It covers the complete data science workflow, from data acquisition to exploratory data analysis (EDA) and geospatial visualization.

🔍 Workflow Overview
Notebook File	Description	Focus Area
jupyter-labs-webscraping.ipynb	Acquires launch data and records from Wikipedia using web scraping techniques.	Data Collection (Web Scraping)
jupyter-labs-spacex-data-collection-api-v2.ipynb	Retrieves additional mission and payload data from the official SpaceX API.	Data Collection (API)
labs-jupyter-spacex-Data wrangling-v2.ipynb
labs-jupyter-spacex-Data wrangling-v2 (1).ipynb	Cleans, preprocesses, and standardizes raw datasets to prepare them for analysis.	Data Wrangling
jupyter-labs-eda-sql-coursera_sqllite.ipynb	Performs SQL-based exploratory data analysis using a local SQLite database.	EDA (SQL)
jupyter-labs-eda-dataviz-v2.ipynb	Creates data visualizations using Matplotlib and Seaborn to identify landing success patterns.	EDA (Visualization)
lab_jupyter_launch_site_location_v2.ipynb
lab-jupyter-launch-site-location-v2.ipynb	Uses Folium for geospatial visualization of launch sites and landing zones.	Geospatial Analysis
🧭 Key Objectives

Collect and consolidate SpaceX launch data from multiple sources.

Explore patterns and relationships between rocket features, mission parameters, and landing outcomes.

Build an analytical foundation for predictive modeling of Falcon 9 first-stage landings.

⚙️ Requirements and Installation
🐍 Environment

All notebooks are designed to run in a Python 3 environment (preferably 3.8+).

📦 Required Libraries

To execute the notebooks, install the following dependencies:

pip install pandas numpy requests beautifulsoup4 sqlalchemy matplotlib seaborn folium nltk scikit-learn

🔧 Additional Setup

For SQL notebooks, ensure that sqlite3 or a compatible SQL connector is available.

For the NLP project, you may need to download NLTK datasets:

import nltk
nltk.download('punkt')
nltk.download('stopwords')



📁 Repository Structure
├── SpaceX_Falcon9_Prediction/
│   ├── jupyter-labs-webscraping.ipynb
│   ├── jupyter-labs-spacex-data-collection-api-v2.ipynb
│   ├── labs-jupyter-spacex-Data wrangling-v2.ipynb
│   ├── jupyter-labs-eda-sql-coursera_sqllite.ipynb
│   ├── jupyter-labs-eda-dataviz-v2.ipynb
│   └── lab-jupyter-launch-site-location-v2.ipynb
│
├── Automated_Reviews_Analysis/
│   └── Project_Automated Customers Reviews (2).ipynb
│
└── README.md


📊 Skills Demonstrated

Web Scraping (BeautifulSoup)

API Data Collection (SpaceX API)

Data Wrangling & Cleaning (pandas, numpy)

SQL-based EDA (SQLite)

Data Visualization (Matplotlib, Seaborn, Folium)

Natural Language Processing (NLTK, scikit-learn)

Geospatial Analysis

🧾 License

This repository is open-source and available under the MIT License
.
