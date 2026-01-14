# A24 IN THE FILM INDUSTRY
### Understanding How a Prestige Indie Studio Compares to The Broader Film Industry Through Data

## Project Overview
This project analyzes how A24 films compare to the broader film industry in terms of box office performance once key factors like budget, genre, ratings, and release year are controlled for. Using a dataset of nearly 10,000 films from IMDb combined with a curated A24 dataset, we examine what actually drives revenue in theatrical releases and where A24 differentiates itself.

The project was completed as part of BANA 212: Data & Programming for Analytics at UC Irvine’s Paul Merage School of Business.

## Research Questions
- What factors most strongly predict box office revenue across the film industry?
- How do A24 films perform relative to industry expectations after controlling for budget, ratings, genre, and release year?
- Does A24’s prestige positioning translate into financial outperformance?

## Data & Methods
- Data sources: IMDb film dataset (~10,000 films) + curated A24 release data
- Data preparation: Title standardization, financial data cleaning, feature engineering, log transformations
- Exploratory analysis: Budget distributions, genre concentration, rating differences
- Models used:
  - Linear Regression (OLS) for interpretability
  - Random Forest Regression for predictive performance
  - Train–test split and cross-validation for model stability

## Key Insights
- Budget is the strongest driver of box office revenue across all models.
- A24 films operate at significantly lower budgets but receive higher average audience ratings.
- Once budget, genre, and ratings are controlled for, A24 films perform in line with industry expectations, rather than systematically over- or under-performing.
- A24’s competitive advantage lies in creative positioning and genre focus (drama, horror, thriller), not financial scale.

## My Role (Individual Contributions)
Although this was a group project, my individual contributions included:

- Designing the research question and analytical framing
- Cleaning and merging datasets across sources
- Feature engineering (log-transformed financials, genre indicators)
- Implementing regression and Random Forest models in Python
- Interpreting model results and translating them into strategic insights
- Writing sections of the final report and supporting the presentation narrative

## Tools & Skills
Python, Pandas, NumPy, Scikit-learn, Regression Analysis, Random Forests, Exploratory Data Analysis, Feature Engineering, Data Visualization

## Files
- Notebook: 
- Slides: 
