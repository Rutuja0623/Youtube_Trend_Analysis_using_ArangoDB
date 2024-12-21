# YouTube Trend Analysis with ArangoDB Graph Database

## Problem Statement
YouTube is one of the most popular streaming platforms globally, offering a trending page to highlight videos gaining significant traction. While some viral videos can predictably appear on this page, other videos may gain popularity over time, making it challenging to track their trajectory. To address this, a multi-model database is proposed to analyze YouTube trending video data effectively.

---

## Data Architecture

![Data Architecture](https://user-images.githubusercontent.com/114179722/236095375-90d3f4bc-7743-48a3-9f2f-d9ec677d7a75.jpg)

### Data Source
The primary data sources include Kaggle datasets and JSON files scraped from the YouTube API.  
Potential Kaggle dataset: [YouTube Trending Video Dataset](https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset?select=CA_youtube_trending_data.csv)

### Data Ingestion
A Python script will preprocess and combine data from Kaggle and YouTube API. The processed data will be ingested into ArangoDB using an ETL tool like Talend, ensuring seamless integration of preprocessed JSON files into the database.

### Data Storage and Querying
ArangoDB will store the data in JSON format, enabling further analysis of YouTube trends. Queries and machine learning algorithms will assist in extracting insights from the stored data.

### Data Reporting
Data visualizations will be generated using Power BI to display trends in YouTube videos through various graphical representations. These visualizations will help users understand YouTube trends more intuitively.

### Users
- **Querying**: Users can query ArangoDB to retrieve specific information tailored to their needs.  
- **Visualizations**: Users can explore Power BI visualizations for a graphical representation of YouTube trends.

---
