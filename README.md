# SpaceX Launch Success Analytics

This repository contains the final project for the **IBM Data Science Capstone**, focusing on analyzing and predicting SpaceX launch success rates. The project implements a complete data science workflow, from data collection to interactive visualization and predictive modeling.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0701EN-SkillsNetwork/lab_v2/images/crash.gif)

## Project Structure

```
.
├── Data Collection
│   ├── Data-Collection-API.ipynb        # SpaceX API data collection
│   └── Data-Collection-webscraping.ipynb # Web scraping for additional data
├── Data Wrangling
│   └── Data wrangling.ipynb             # Data cleaning and preprocessing
├── Exploratory Data Analysis
│   ├── Data_Visualization.ipynb         # Data visualization and analysis
│   └── Explorator Data Analysis - SQL.ipynb # SQL-based analysis
├── Interactive Visualization
│   ├── spacex_dash_app.py              # Interactive Dash application
│   └── Visual Analytics with Folium.ipynb # Geographical visualizations
├── Predictive Analysis
│   └── Machine_Learning_Prediction.ipynb # ML models for launch prediction
└── Documentation
    ├── IBM Data Science Capstone Project.pdf
    └── IBM Data Science Capstone Project.pptx
```

## Project Overview

This project analyzes SpaceX launch data to understand factors that contribute to successful rocket launches and predict future launch outcomes. The analysis includes:

1. **Data Collection**
   - Gathering launch data from SpaceX API
   - Web scraping additional relevant information
   - Compiling historical launch records

2. **Data Processing**
   - Cleaning and preprocessing launch data
   - Handling missing values and outliers
   - Feature engineering for analysis

3. **Exploratory Analysis**
   - Statistical analysis of launch success rates
   - Visualization of launch patterns and trends
   - SQL-based data exploration

4. **Interactive Visualizations**
   - Interactive dashboard using Dash
   - Geographical launch site analysis with Folium
   - Real-time data visualization

5. **Predictive Modeling**
   - Machine learning models for launch success prediction
   - Model evaluation and comparison
   - Feature importance analysis

## Technical Stack

- **Programming Languages**: Python, SQL
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Interactive Dashboard**: Dash
- **Geospatial Analysis**: Folium
- **Machine Learning**: Scikit-learn
- **Development Environment**: Jupyter Notebooks

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Astro-Success-Analytics.git
   cd Astro-Success-Analytics
   ```

2. Install required packages

3. Launch Jupyter Notebook:
    ```bash
   jupyter notebook
   ```

## Project Workflow

1. Start with the Data Collection notebooks to gather the necessary data
2. Use the Data Wrangling notebook to clean and prepare the data
3. Explore the data using the Exploratory Data Analysis notebooks
4. Run the interactive visualizations in the Interactive Visualization section
5. Build and evaluate predictive models using the Machine Learning notebook

## Key Findings

[To be added based on your analysis results]

## Future Improvements

- [ ] Add real-time data updates
- [ ] Implement additional machine learning models
- [ ] Add automated testing

## Contributing

Feel free to submit issues and enhancement requests!

## Acknowledgments

- IBM Data Science Professional Certificate Program
- SpaceX for providing the API
- Open source community for various tools and libraries used in this project
