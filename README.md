# Airline Customer Care Transcript Analysis

## Overview

This repository contains scripts and analysis for topic modeling of airline customer care transcripts. The main goal of this project is to extract recurring customer issues by applying various unsupervised learning techniques, including topic modeling and clustering.

## Contents

1. **Jupyter Notebooks**:
   - The provided Jupyter notebook contains our complete analysis of the customer care transcripts. It walks through the steps of topic extraction, clustering, and visualization.

2. **Topic Modeling Scripts**:
   - The `topic_modelling` folder contains three pipelines for topic modeling using different techniques.
   - We have not included all topic-number choices for each pipeline but have summarized the best choices based on graph analysis.
   - You can analyze the best topic choices by reviewing the provided results.

3. **Summarizer Script**:
   - The `summarizer.py` script is designed to summarize the findings of the topic modeling and provide insight into the recurring customer issues from the transcripts.
   - Running this script will output a summary based on the processed topics and the corresponding customer issues.

## Instructions for Use

1. **Jupyter Notebook**: 
   - Open the notebook and run the cells sequentially to reproduce the analysis. This notebook includes visualizations of the clusters and interpretations of the customer care issues based on the topic modeling results.
   
2. **Running Topic Modeling Pipelines**:
   - Navigate to the `topic_modelling` folder.
   - Choose the script corresponding to the pipeline you wish to run.
   - Modify the number of topics or any other parameters if needed, though the current settings reflect the best configuration based on the visual analysis.

3. **Running the Summarizer**:
   - To view a summary of the key issues extracted from the transcripts, run `summarizer.py`:
     ```bash
     python summarizer.py
     ```
   - The script will output key insights regarding the most frequent customer complaints, service issues, and trends.

## Requirements

- Python 3.8+
- Required libraries are listed in the `requirements.txt` file. You can install them with:
  ```bash
  pip install -r requirements.txt