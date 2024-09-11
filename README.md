# YouTube Sentiment Analysis and Visualization Project

## Overview
This project uses Python for performing sentiment analysis, emoji analysis, and various visualizations on YouTube comments.

### Key Features
- **Sentiment Analysis**: Classify user comments into positive, neutral, and negative sentiments.
- **Word Cloud Analysis**: Generate word clouds for both positive and negative comments.
- **Emoji Analysis**: Visualize the most frequently used emojis in the comments.
- **Visualization**: Leverage Python libraries like Plotly, Matplotlib, and Seaborn for graphical representations.

## Tools & Setup

### 1. Anaconda Navigator
Anaconda Navigator enables package management and environment control without using the command line. You can find, install, and manage packages and environments easily.

### 2. Jupyter Notebook
Jupyter Notebook allows users to write live code, visualize outputs, and add rich text for documentation. It's a web-based tool that makes data analysis workflows interactive.


## Lifecycle of Data Analysis

### 1. Understanding Use Case
In a typical data project, the process starts with understanding business requirements. The **Business Analyst** and **Data Analyst** collaborate to:
- Identify data sources.
- Determine if third-party APIs are necessary.
- Clarify how to extract data from databases.

### 2. Run ETL Pipeline
An ETL pipeline involves:
- **Extract**: Raw data collection from various sources (CSV, databases, APIs).
- **Transform**: Clean the data by handling missing values, removing duplicates, fixing errors, and preparing it for analysis.
- **Load**: Feature-engineered or processed data is loaded into a data store for analysis.

```python
import pandas as pd
comment = pd.read_csv(r'P:\Data_Analysis\Youtube/UScomments.csv', on_bad_lines='skip')




