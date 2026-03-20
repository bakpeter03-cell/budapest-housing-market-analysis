# Budapest Rental Market Analysis

## Project Overview
This project analyzes the Budapest rental market using apartment listing data. The goal is to identify which districts are the most expensive, which offer better value for money, and which apartment characteristics are most strongly associated with rental prices.

## Business Questions
- Which Budapest districts have the highest and lowest rental prices?
- Which districts have the highest and lowest rent per square metre?
- How do apartment size and room count affect monthly rent?
- How do apartment types differ in pricing?
- Where is rental supply most concentrated across Budapest?

## Dataset
- Source: Kaggle – Flats for Rent at Budapest
- Observations after cleaning: 2,775 listings
- Main variables used: price, size, rooms, district, type, condition, heating_type, furniture, elevator, garden, animals

## Data Cleaning
The dataset was cleaned by:
- removing irrelevant technical columns
- dropping rows missing core analysis variables
- filtering unrealistic values for rent, size, and room count
- extracting district information from location text
- creating a new `price_per_sqm` variable

## Key Findings
- 
- 
- 
- 

## Tools Used
- Python
- pandas
- matplotlib
- Jupyter Notebook

## Project Structure
- `data/raw/` – original dataset
- `data/processed/` – cleaned dataset
- `notebooks/` – cleaning and analysis notebooks
- `visuals/` – exported figures

## Limitations
- Listing prices may differ from final agreed rental prices
- The dataset is a scraped sample and may not represent the full market
- Some outer districts have relatively few observations
