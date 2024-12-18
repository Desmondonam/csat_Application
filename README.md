# Customer Satisfaction (CSat) Survey Dashboard
## Overview
- This Streamlit application provides a comprehensive Customer Satisfaction survey and analysis tool. It allows businesses to:

    - Collect detailed customer feedback
    - Calculate Customer Satisfaction Score
    - Visualize customer satisfaction segments
    - Get actionable insights across different service areas

- Here is the Dashboard:
![alt text](image.png)



## Features

    - Interactive CSat Survey
    - Real-time Satisfaction Score Calculation
    - Segment Distribution Visualization
    - Service Area Performance Analysis
    - Actionable Business Insights
    - Data Export Functionality

## Setup Instructions
### Prerequisites

    - Python 3.8+
    - pip (Python Package Manager)

### Installation Steps

- Clone the repository
- Create a virtual environment

`python -m venv venv`
`source venv/bin/activate`  # On Windows, use `venv\Scripts\activate`

### Install dependencies

`pip install -r requirements.txt`

-  Run the Streamlit App

`streamlit run app.py`

## How to Use

    - Navigate through different sections using the sidebar
    - Complete the survey in the "Survey" section
    - View analysis in "CSat Analysis"
    - Get insights in the "Insights" section
    - Download data in "Download Data"

## Data Storage

- Survey responses are stored in data/csat_responses.csv
- Automatically creates the file on first survey submission

## Customization

   - Modify utils.py to adjust CSat calculation or insights
   - Update visualizations in the utility functions

- You can also access the application of the web here: https://desmondonam-csat-application-app-vuzw5c.streamlit.app/
