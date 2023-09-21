# Stores_Sales_Prediction_ML
In the world of machine learning regression projects, I embark on an exciting journey to develop a model that can predict the dependent variable's values based on independent variables. This model is trained using historical data, allowing it to uncover hidden patterns.

Once trained, the model becomes a valuable tool for forecasting various future outcomes, such as sales, demand, or risk assessment. This plays a crucial role in this adventure, uncovering insights and shaping the future with data-driven decisions. It's a captivating journey of exploration and prediction!

## Project Overview
This project embraces the CRISP-DM framework, guiding my exploration of sales data for Corporation Favorita, a major Ecuadorian grocery retailer. My mission centers on constructing a robust model for predicting unit sales of diverse items in various Favorita stores. I follow a systematic approach, from data understanding to model development, aiming to provide more accurate sales forecasts. This journey promises to equip Favorita with invaluable insights and strategic advantages through data-driven decision-making.

### Aim of Project
The aim of this project is to explore the influence of external factors like oil prices, holiday events, and natural occurrences on product sales, and develop machine learning models to predict sales at Corporation Favorita Retail Stores.

## 📑 Table of Contents

- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Aim of Project](#aim-of-project)
- [Data Dictionary](#data-dictionary)
- [Project Highlights](#project-highlights)
- [Project Links](#project-links)
- [Hypothesis](#hypothesis)
- [Project Kickoff](#project-kickoff)
- [License](#license)
- [Author](#author)

## Project Structure📂
- `data/`: Contains the dataset used for analysis and 
- `project notebook/`: Contains the Jupyter notebook detailing the data exploration, preprocessing, and model building steps.
- `article/`: Holds project-related Article.
-  `powerbi/`: Holds project-related Dashboard.
- `LICENSE`: Project license.
- `README.md`: Project overview, links, highlights, and information.

## Data Dictionary
| **Dataset** | **Description** |
|------------|-----------------|
| train.csv  | Training data containing time series of features store_nbr, family, and onpromotion, as well as the target sales. |
|            | - `store_nbr`: Identifies the store where the products are sold. |
|            | - `family`: Identifies the type of product sold. |
|            | - `sales`: Total sales for a product family at a specific store on a given date (can be fractional , that is, 1.5 kg of cheese, for instance, as opposed to 1 bag of chips). |
|            | - `onpromotion`: Total number of items in a product family that were being promoted at a store on a given date. |
| test.csv   | Test data with the same features as the training data. Predict target sales for these dates. |
| transaction.csv | Contains date, store_nbr, and transactions made on specific dates. |
| sample_submission.csv | Sample submission file in the correct format. |
| stores.csv | Store metadata, including city, state, type, and cluster. |
|            | - `cluster`: Grouping of similar stores. |
| oil.csv    | Daily oil price data, including values during both the train and test data timeframes. |
| holidays_events.csv | Holidays and events data, with metadata. |
| Additional Notes| Wages in the public sector are paid every two weeks on the 15th and on the last day of the month. Supermarket sales could be affected by this.|
|                 | A magnitude 7.8 earthquake struck Ecuador on April 16, 2016. People rallied in relief efforts donating water and other first need products which greatly affected supermarket sales for several weeks after the earthquake.|

## Project Highlights
- Leveraged the CRISP-DM framework for a comprehensive understanding of retail dynamics.
- Unearthed hidden trends and patterns through extensive exploratory data analysis.
- Employed advanced predictive models, including the potent XGBoost algorithm, for highly accurate sales forecasting.
- Achieved exceptional predictive performance through meticulous hyperparameter tuning.
- Produced a compelling and informative article chronicling the project's journey, groundbreaking results, and its transformative potential in retail forecasting.

## Project Links
| Code | Name                                     |                                             Published Article                                              |
| ---- | ---------------------------------------- | :--------------------------------------------------------------------------------------------------------: |
| LP 3 | Exploring Favorito Superstore's Time Series Dataset in Ecuador | [Read Article](https://www.linkedin.com/pulse/exploring-favorito-superstores-time-series-dataset-ecuador-kofi-bamfo) |

| Code | Name                                     |                                             Published Dashboard                                              |
| ---- | ---------------------------------------- | :--------------------------------------------------------------------------------------------------------: |
| LP 3 | Sales Time Series Prediction | [PowerBI Dashboard]() |


## Hypothesis 
The project aims to test whether fluctuations in external factors, such as changes in oil prices, the occurrence of holiday events, and natural disasters, have a statistically significant impact on product sales in Corporation Favorita Retail Stores. Specifically, I hypothesize that variations in these external factors will correlate with changes in sales, and that machine learning models can effectively capture and predict these relationships, providing valuable insights for sales forecasting and decision-making.

**Null Hypothesis (H0):** There is no statistically significant relationship between external factors (such as oil prices, holiday events, and natural occurrences) and product sales at Corporation Favorita Retail Stores.

**Alternative Hypothesis (H1):** There is a statistically significant relationship between external factors (such as oil prices, holiday events, and natural occurrences) and product sales at Corporation Favorita Retail Stores

## Project Kickoff 🏁

1. Clone this repository: `git clone https://github.com/akbamfo/Stores_Sales_Prediction_ML.git`
2. Navigate to the project directory: `LP3-Super-Store-Time-Series-Forecasting`
3. Explore the Jupyter notebooks for detailed steps and code execution.
4. Read the published article for a comprehensive understanding of the project.








