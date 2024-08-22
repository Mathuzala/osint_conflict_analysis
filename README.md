# Conflict Zone Analytics and OSINT Tools

![conflict_map](https://github.com/user-attachments/assets/ad2c1446-66de-4eb1-91c2-b9fae018de9e)


## Overview

This repository contains a collection of Google Colab notebooks showcasing various analytics and methodologies used in the analysis of conflict zones and the identification of violent actors using open-source data and OSINT (Open Source Intelligence) tools. The analysis spans regions including Asia, Europe, and the Middle East, and leverages data from ACLED, SIPRI, GDELT, and other public sources.

## Project Structure
	• Data Collection: Notebooks related to data extraction from sources such as ACLED, SIPRI, and GDELT. These notebooks include API interactions, data processing, and the initial data cleaning steps.
	• Data Analysis: Contains notebooks focused on the analysis of conflict events, military expenditures, and socio-political dynamics. Techniques such as time series analysis, sentiment analysis, and predictive modeling are used.
	• Actor Identification: Notebooks in this section are dedicated to identifying key actors in various conflict zones, including the calculation of growth rates, analysis of conflict events by actor, and the use of machine learning models for prediction.
	• Visualization: Contains all notebooks related to data visualization. These include charts, graphs, and interactive visualizations that help illustrate the findings from the analysis.
	• OSINT Tools: Demonstrates how tools like Maltego and other OSINT platforms were used to gather and analyze open-source intelligence, identify potential threats, and map out connections between entities.

![zoom_in_greece_v2](https://github.com/user-attachments/assets/07b5f7ba-d74c-42dd-ab65-8909d27c07a2)

## Key Notebooks
	• ACLED Data.ipynb - Extracts conflict event data for all three regions using the ACLED API.
 	• GDELT - Web Scraping.ipynb - Extracts relevant URLs from GDELT for the three different regions for NLP analysis. 
  	• Conflict Analysis - Asia.ipynb - Analyzes and identifies key violent actors in Asia and determining which country and actor to focus on.
	• CA - Middle East NLP.ipynb - NLP analysis consisting of two parts - Sentiment Analysis to determine reflected emotion and Named Entity Recognition (NER) to extract key entities.
	• Conflict Analysis - Combined.ipynb - Contains analytics and visualizations that showcase all three regions and the chosen three countries. 
	• Conflict Analysis - Europe Word Cloud.ipynb - Applies word cloud visualization analysis showcasing the relevant words from the GDELT article pull and analysis. 

## Getting Started

To explore the notebooks, simply clone this repository and open the notebooks in Google Colab or Jupyter Notebook.

```
git clone https://github.com/your-username/conflict-zone-analytics.git
```

Make sure to install any required libraries before running the notebooks. The necessary libraries and their versions are listed in each notebook’s introductory cells.
