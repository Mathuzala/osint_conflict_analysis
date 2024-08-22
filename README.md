# Conflict Zone Analytics and OSINT Tools

## Overview

This repository contains a collection of Google Colab notebooks showcasing various analytics and methodologies used in the analysis of conflict zones and the identification of violent actors using open-source data and OSINT (Open Source Intelligence) tools. The analysis spans regions including Asia, Europe, and the Middle East, and leverages data from ACLED, SIPRI, GDELT, and other public sources.

## Project Structure

	•	Data Collection: Notebooks related to data extraction from sources such as ACLED, SIPRI, and GDELT. These notebooks include API interactions, data processing, and the initial data cleaning steps.
	•	Data Analysis: Contains notebooks focused on the analysis of conflict events, military expenditures, and socio-political dynamics. Techniques such as time series analysis, sentiment analysis, and predictive modeling are used.
	•	Actor Identification: Notebooks in this section are dedicated to identifying key actors in various conflict zones, including the calculation of growth rates, analysis of conflict events by actor, and the use of machine learning models for prediction.
	•	Visualization: Contains all notebooks related to data visualization. These include charts, graphs, and interactive visualizations that help illustrate the findings from the analysis.
	•	OSINT Tools: Demonstrates how tools like Maltego and other OSINT platforms were used to gather and analyze open-source intelligence, identify potential threats, and map out connections between entities.

## Key Notebooks

	•	01_Data_Collection_ACLED.ipynb - Extracts conflict event data using the ACLED API.
	•	02_SIPRI_Military_Expenditure_Analysis.ipynb - Analyzes military expenditure as a percentage of GDP for selected countries.
	•	03_Actor_Identification_Yemen.ipynb - Identifies and analyzes key violent actors in Yemen.
	•	04_Sentiment_Analysis_GDELT.ipynb - Applies sentiment analysis to news articles from GDELT to identify emerging threats.
	•	05_Visualization_Greece_Conflict.ipynb - Visualizes conflict data for Greece, focusing on event types and sub-event types.

## Getting Started

To explore the notebooks, simply clone this repository and open the notebooks in Google Colab or Jupyter Notebook.

git clone https://github.com/your-username/conflict-zone-analytics.git

Make sure to install any required libraries before running the notebooks. The necessary libraries and their versions are listed in each notebook’s introductory cells.
