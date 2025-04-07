# # SpaceX Falcon 9 First Stage Landing Prediction

This project focuses on predicting the landing success of the **SpaceX Falcon 9 First Stage** booster using real-world launch data. It includes web scraping, data wrangling, and data analysis to build a clean and insightful dataset for further machine learning modeling.
## Project Overview

This project involves:

- Collecting launch data from the **SpaceX API** and official web pages using **web scraping**.
- Cleaning and wrangling the data with **pandas**.
- Handling missing values by **imputation (mean replacement)**.
- Labeling outcomes to classify the **success or failure** of booster landings.
- Analyzing orbital outcomes, launch sites, and mission results.

The cleaned and labeled dataset can be used in a machine learning pipeline to predict landing outcomes.

## Technologies Used

- Python 
- `requests` – for HTTP GET requests
- `BeautifulSoup` – for parsing HTML
- `pandas` – for data manipulation
- `piplite` – for accessing lightweight pip packages (JupyterLite)
  

