# UCSD Data Visualization 209

Two projects for UC San Diego's DSE 209 (Data Visualization): visualizing food processing scores and prices at grocery stores, and an analysis of NYPD civilian complaints before and after the Neighborhood Policing model.

## Repository Contents

| File | Description |
|---|---|
| `Visulaizations for Project 1.ipynb` | Project 1: food processing and price visualizations (26,250 grocery products) |
| `Police Data.ipynb` | Project 2: NYPD civilian complaint allegations before and after Neighborhood Policing |

## Commit History

### `dad79b9`: Upload of Project 1 and Project 2 (2026-01-04)

**Project 1: food processing and prices**
- **Cleaning:**
  - renamed columns and checked for nulls
  - rounded the numeric columns (food processing score, price per calorie, package weight and nutrients) to 2 decimals
- **Visualizations of organic foods:**
  - a swarm plot of food processing score vs. price, colored by store, used to look for trends and outliers
  - the distribution of organic foods sold at Whole Foods, with a histogram and KDE curve

**Project 2: NYPD complaints and Neighborhood Policing**
- **Data preparation:**
  - loaded the civilian complaint allegations dataset
  - renamed columns and converted month numbers to names
- **Before vs. after flag:** filtered to 2016 onward and added a column marking complaints during the Neighborhood Policing period (June 2015–December 2019).
- **Question:** did Neighborhood Policing improve community relations and reduce complaints against officers?
- **Charts comparing before and after:**
  - complaint counts by year and month
  - complaint outcomes
  - complainant gender and ethnicity
  - arrests
  - a focused look at Precinct 75

## Tools
Python, pandas, NumPy, matplotlib, seaborn, Jupyter Notebook
