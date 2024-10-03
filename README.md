# Data Portfolio: Excel to Power BI

## Table of Contents
- [Objectives](#objectives)
- [Data Source](#data-source)
- [Stages](#stages)
- [Design](#design)
  - [Dashboard components requirement](#Dashboard components requirement)
  - [Tools](#tools)
- [Development](#development)
  - [Pseudocode](#Pseudocode)
  - [Data Exploration](#DataExploration)
  - [Data Cleaning](#DataCleaning)
  - [Transform the Data](#TransformtheData)
  - [Create the SQL View](#CreatetheSQLView)

## Objectives
The Head of Marketing wants to find out who the top YouTubers are in 2024 to determine which YouTubers are most suitable for marketing campaigns for the remainder of the year.

### Ideal Solution
To create a dashboard that provides insights into the top UK YouTubers in 2024 that includes the following:
- Subscriber count
- Total views
- Total videos
- Engagement metrics

This will help the marketing team make informed decisions regarding which YouTubers to collaborate with for their marketing campaigns.

## Data Source
### What data is needed to achieve our objective?
We need data on the top UK YouTubers in 2024 that includes:
- Channel names
- Total subscribers
- Total views
- Total videos uploaded

### Where is the data coming from?
The data is sourced from Kaggle (an Excel extract), which can be found [here](https://www.kaggle.com/datasets/bhavyadhingra00020/top-100-social-media-influencers-2024-countrywise?resource=download).

## Stages
- Design
- Development
- Testing
- Analysis

## Design
### Dashboard components requirement
To understand what it should contain, we need to figure out what questions we need the dashboard to answer:
1. Who are the top 10 YouTubers with the most subscribers?
2. Which 3 channels have uploaded the most videos?
3. Which 3 channels have the most views?
4. Which 3 channels have the highest average views per video?
5. Which 3 channels have the highest views per subscriber ratio?
6. Which 3 channels have the highest subscriber engagement rate per video uploaded?

### Tools

| Tool | Purpose
 --- | ---
| Excel | Exploring Data |
|  SQL Server | Cleaning, testing, and analyzing the data |
| Power BI | Visualizing the data via interactive dashboards |
| GitHub | Hosting the project documentation and version control |

## Development

### Pseudocode
- What is the general approach in creating this solution from start to finish?
1. Get the data
2. Explore the data in Excel
3. Load the data into SQL Server
4. Clean the data with SQL
5. Visualize the data in Power BI
6. Generate the findings based on the insights
7. Write the documentation + commentary
8. Publish the data to GitHub Pages


