# Capstone Project: Housing Prices Analysis

## Dataset Overview
This repository contains a dataset named **NewAIMLcsv**, which consists of **126,766 entries** related to real estate listings and transactions. The dataset includes various attributes that provide insights into housing status, pricing, and property characteristics.

This data was initially retrieved from Kaggle link below: 
https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset/data

## Dataset Attributes
The dataset includes the following attributes:

- **brokered by**: Categorially encoded agency/broker responsible for the listing.
- **status**: Indicates the housing status, which can be: Ready for sale or Sold.
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


#### House Size
- The average house size is about **1,925 sqft**, with most homes ranging between **1,445 sqft** (25th percentile) to **2,291 sqft** (75th percentile).
- Homes in the top 25% are significantly larger, with a maximum size of around **3,663 sqft**.

#### Price
- The average home price ranges from **$1** (likely outliers or special cases) to **$985,900** for high-end properties.
- The median price is **$314,950**, meaning half the homes cost more than this and half cost less.

#### Lot Size (Acre Lot)
- The average lot size is about **0.36 acres**, with most properties ranging between **0.15** and **0.37 acres**.

#### Bedrooms and Bathrooms
- The typical home has around **3 bedrooms** and **2.5 bathrooms**, which is fairly standard for family-sized homes.

### Price Distribution by State
- **Minnesota**: Likely offers larger properties with more land at a reasonable price per square foot.
- **Virginia**: Home prices are higher, likely due to the state's economic factors and proximity to high-demand regions.
- **Ohio**: Offers more affordable housing options, with homes priced significantly lower than in Virginia.

### Recommendation
- Buyers in **Minnesota** may find a balance between price and land size.
- Those in **Virginia** should expect to pay more, especially for properties in suburban or urban areas.
- **Ohio** offers the most affordable options for buyers on a budget.

---

## Price Recommendations

### Objective
Offer actionable price recommendations based on key features such as house size, number of bedrooms, bathrooms, and land size (acre lot).

#### Price per Square Foot
- Based on an average house size of ~**1,925 sqft** and a median price of **$314,950**, we can estimate that the price per square foot is approximately:
  - **Price per sqft = $163.64/sqft**
- **Minnesota**: Price per square foot may range between **$180**, making it a reasonably affordable state.
- **Virginia**: Expect higher prices per square foot, ranging from **$250**, particularly in high-demand areas.
- **Ohio**: More affordable, with prices ranging from **$160** per square foot.

#### Price per Acre
- With a median lot size of **0.29 acres** and a median price of **$314,950**:
  - **Price per acre = $1,085,000/acre**
- Acre lot size impacts pricing significantly in rural areas, especially in Minnesota and Ohio, where land is more abundant. Virginia, being more urbanized, likely sees higher price appreciation for smaller lots.


## Recommendations for Buyers/Investors

### For Buyers:
- **Minnesota**: Buyers looking for spacious homes with more land at a reasonable price should focus on Minnesota. With a moderate price per square foot and acre, it provides a good balance between cost and size.
- **Virginia**: Expect to pay a premium, especially for properties with larger houses or premium locations. Buyers here may focus on maximizing home features (e.g., more bedrooms or higher-quality finishes) as a way to justify the higher price.
- **Ohio**: The most affordable option for buyers. If price is the main concern, Ohio offers good value for those seeking a lower cost per square foot or per acre.

### For Investors:
- **Minnesota**: Consider investing in larger lots or properties that can appreciate over time as land becomes scarcer.
- **Virginia**: High demand areas present opportunities for flipping or rental income, but initial investment costs will be higher.
- **Ohio**: Offers opportunities for long-term investment or rental properties. Its affordability makes it a low-risk market for those looking to buy multiple properties at a lower cost.

---

## Conclusion
- **Minnesota**: Offers reasonably priced larger homes and acreage. Great for buyers and investors seeking a balance between cost and property size.
- **Virginia**: A more premium market, especially for high-demand areas. Buyers should be prepared to pay more for properties with greater amenities or proximity to urban centers.
- **Ohio**: The most affordable state, providing good value for money, especially for those interested in investing in larger properties or multiple homes.

These insights and recommendations should help buyers and investors make informed decisions based on the analysis of housing prices across the three states.

## Repository Structure
- `data/`: Contains the dataset used for analysis.
- `notebooks/`: Jupyter Notebooks with EDA and model development.
- `results/`: Folder for storing results and visualizations.
- `README.md`: This file.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
