# Time Series Analysis

This repository contains data, scripts, and documentation for analyzing the relationship between climate data and mental health outcomes. It includes pre-processing scripts, data cleaning workflows, and methodologies for integrating multiple datasets to explore the effects of extreme weather events on mental health.

## Repository Structure

- **`climate-data/`**  
  Contains raw and processed climate data, such as temperature records, extreme weather event frequencies, and other environmental metrics.

- **`mental-health-data/`**  
  Includes datasets related to mental health metrics, such as prevalence of serious psychological distress (SPD), depression, and anxiety. Note: Pre-processed datasets are excluded for privacy and compliance reasons.

- **`README.md`**  
  This file. It provides an overview of the repository, its purpose, and how to use the resources.

- **`SPD_PreProcessing.py`**  
  Python script for pre-processing SPD-related data. Handles tasks such as cleaning, validation, and feature extraction.

- **`clean_and_validate_climate_data.Rmd`**  
  R Markdown script for cleaning and validating raw climate data. Ensures consistency and accuracy in dataset preparation.

- **`merging_public_datasets.Rmd`**  
  R Markdown script for integrating climate and mental health datasets, resolving mismatches, and preparing data for analysis.

## Features

- **Data Cleaning:** Scripts to clean and validate datasets for analysis.  
- **Data Integration:** Methods for merging public datasets to study correlations between climate and mental health.  
- **Pre-Processing:** Python and R scripts to prepare data for statistical and sentiment analysis.  
- **Exploration of Trends:** Includes code to explore and visualize trends in climate and mental health data over time.  

## Usage

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/climate-mental-health-analysis.git
   cd climate-mental-health-analysis
   ```

2. Install required dependencies for Python and R as specified in the respective scripts.

3. Run the scripts as needed:
   - To pre-process SPD data:  
     ```bash
     python SPD_PreProcessing.py
     ```
   - To clean and validate climate data:  
     Open and execute `clean_and_validate_climate_data.Rmd` in RStudio.  

4. Merge datasets by executing `merging_public_datasets.Rmd`.

## Acknowledgments

This project leverages publicly available datasets and tools to contribute to understanding the interplay between climate and mental health. Special thanks to organizations like SAMHSA and IHME for providing valuable data.
