# Real Estate Data Analysis in France (2017–2021)

This project, developed by me during my M1 Economics & Financial Engineering program at Université Paris Dauphine, analyzes property transaction data in France between 2017 and 2021. The goal was to clean, structure, and model the data to identify pricing patterns and regional trends in real estate markets.

## Project Objective

The main objective of the project was to extract relevant insights from the French notarial transaction data ("Demandes de Valeurs Foncières"), focusing on property prices at different geographic levels (national, regional, departmental, and city). It also includes model building to understand the impact of various factors on real estate prices, including COVID-19.

## Dataset

The dataset was sourced from [data.gouv.fr](https://www.data.gouv.fr/), covering over 17 million transactions. It includes property value, location, type, surface area, and more.

## Tools and Technologies

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Data cleaning and transformation
- Exploratory data analysis (EDA)
- Linear regression modeling
- Outlier detection and removal

## Key Steps

1. **Data Cleaning**  
   - Removed irrelevant or incomplete fields  
   - Handled missing values  
   - Filtered only house and apartment sales  
   - Excluded overseas territories and commercial properties  
   - Standardized column names and formatting  
   - Created a price per square meter (`valeur_foncière / surface_bâtie`)  
   - Removed extreme values and outliers using statistical thresholds  

2. **Exploratory Data Analysis (EDA)**  
   - Evolution of property prices from 2017 to 2021  
   - Analysis at national, regional, and city level  
   - Identification of most expensive cities (e.g., Neuilly-sur-Seine, Paris)  
   - Comparison between houses and apartments  

3. **Focus on Nouvelle-Aquitaine**  
   - In-depth study of price evolution in this region, Gironde (dept. 33), and Bordeaux  
   - Tracked medians and distributions over time  

4. **Modeling**  
   - Linear regression to measure the impact of COVID-19  
   - Included features such as surface area, number of rooms, location, property type, and population  
   - Developed a prediction function to estimate property prices based on user input  

## Results

- National median price per m² increased from €2,248 in 2017 to €2,575 in 2021 (+14.56%)
- The pandemic had a surprising positive effect on prices at the national level
- Regional disparities were clearly observed, with Ile-de-France remaining the most expensive region
- Predictive model achieved an R² of ~35%, providing useful but improvable estimations

## Limitations & Suggestions

- External factors such as public transport, quality of life, and amenities were not included
- Population density and proximity to infrastructure could improve predictions
- Future versions could integrate data from INSEE and enrich the feature set for modeling

## Author

**Abdoulaye Gaye**  
Université Paris Dauphine Economics & Financial Engineering  (272)
Quantitative Research & Data Enthusiast  
