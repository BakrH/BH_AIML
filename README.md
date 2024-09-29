# Capstone Project: Housing Price Analysis

## Dataset Overview
This repository contains a dataset named **NewAIMLcsv**, which consists of **126,766 entries** related to real estate listings and transactions. The dataset includes various attributes that provide insights into housing status, pricing, and property characteristics.

## Dataset Attributes
The dataset includes the following attributes:

- **brokered by**: Categorially encoded agency/broker responsible for the listing.
- **status**: Indicates the housing status, which can be:
  - a. Ready for sale
  - b. Ready to build
- **price**: The housing price, which can either be the current listing price or the recently sold price if the house has been sold recently.
- **bed**: The number of bedrooms in the property.
- **bath**: The number of bathrooms in the property.
- **acre_lot**: The size of the property/land in acres.
- **street**: Categorially encoded street address of the property.
- **city**: The name of the city where the property is located.
- **state**: The name of the state where the property is located.
- **zip_code**: The postal code of the area.
- **house_size**: The area/size/living space of the house in square feet.
- **prev_sold_date**: The date when the property was previously sold.

## Objective
### Problem Statement
Analyze housing prices across three states (Minnesota, Virginia, and Ohio) present in the dataset to determine which state offers reasonable prices based on various features such as house size, number of bedrooms, number of bathrooms, and land size (acre lot).

### Key Objectives
1. **Predict Housing Prices**: Develop predictive models to forecast housing prices based on property features and location attributes.
2. **Analyze Correlations**: Explore and identify significant correlations between housing prices and various attributes such as location, property size, and house features.
3. **Market Overview**: Provide an overall picture of housing prices across different regions in the USA.

## Methodology
- **Data Preprocessing**: Clean and preprocess the dataset to handle missing values and encode categorical variables.
- **Exploratory Data Analysis (EDA)**: Conduct EDA to visualize data distributions and relationships between variables.
- **Model Development**: Implement various predictive models (e.g., Linear Regression, Decision Trees) to forecast housing prices.
- **Evaluation**: Assess model performance using appropriate metrics (e.g., RMSE, R²).

## Results
- Summarize key findings from the analysis, including insights on housing price trends and significant predictors of price.

## Next Steps
- Suggest further explorations, such as incorporating additional datasets or refining predictive models.

## Repository Structure
- `data/`: Contains the dataset used for analysis.
- `notebooks/`: Jupyter Notebooks with EDA and model development.
- `results/`: Folder for storing results and visualizations.
- `README.md`: This file.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
