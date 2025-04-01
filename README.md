# Airbnb NYC Data Analysis

## Overview
This repository contains an exploratory data analysis (EDA) of Airbnb listings in New York City. The analysis examines pricing patterns, geographical distribution, room types, and other factors that influence Airbnb listings across NYC's neighborhoods.

## Dataset
The analysis uses a dataset (`datasets.csv`) containing information about Airbnb listings including:
- Basic listing information (ID, name, host ID)
- Location data (neighborhood group, neighborhood)
- Listing characteristics (room type, bedrooms, beds)
- Pricing information
- Booking metrics (minimum nights, availability, number of reviews)
- Rating information

## Analysis Highlights
The notebook performs a thorough exploratory analysis including:

1. **Data Cleaning & Preparation**
   - Handling missing values
   - Removing duplicates
   - Data type conversion
   - Outlier identification and handling

2. **Price Analysis**
   - Distribution of prices across NYC
   - Price comparison by neighborhood group
   - Effect of room type on pricing
   - Created PricePerBed metric for value comparison

3. **Geographic Analysis**
   - Listing distribution across neighborhood groups
   - Price variations by location

4. **Listing Characteristics**
   - Relationship between reviews and price
   - Analysis of availability patterns
   - Impact of room type on various metrics

## Key Findings
- Manhattan appears to have the highest average prices for Airbnb listings
- Significant price outliers exist in the dataset (addressed by filtering to listings under $1,500)
- Clear relationships between neighborhood, room type, and pricing
- Visualized patterns in review numbers relative to price and location

## Technologies Used
- **Python**: Primary programming language
- **Pandas & NumPy**: Data manipulation and numerical operations
- **Matplotlib & Seaborn**: Data visualization

## Getting Started
To run this analysis:

1. Clone this repository
```
git clone https://github.com/VarunPahuja/AirbnbNYCDataAnalysisProject.git
```

2. Install required dependencies
```
pip install pandas numpy matplotlib seaborn
```

3. Open the Jupyter notebook
```
jupyter notebook Untitled-1.ipynb
```

## Future Work
Potential extensions to this analysis:
- Predictive modeling for Airbnb pricing
- Sentiment analysis of reviews
- Time series analysis of availability and pricing patterns
- Geographic visualization using mapping libraries


## Contact
Varun Pahuja 
vpahuja1508@gmail.com
7999389919
