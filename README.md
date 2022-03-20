# Airline Price Predictor

### EDA & ML Practice

**Checklist**

> Cleaning and Processing of Data

-   [x] Import libraries
-   [x] Load dataset
-   [x] Check for missing values
-   [x] Drop unnecessary features
-   [x] Rename features
-   [x] Reorder featuress
-   [x] Change data types
    -   [x] Change `flight_date` to "datetime" in yyyy-mm-dd format
    -   [x] Change `flight_dep` and `flight_arr` to "datetime" in HH:MM format
    -   [x] Change `total_stops` to "int" from categorical values
    -   [x] Change `flight_time` to "datetime" in HH:MM format
    -   [x] Change `flight_fare` to "int"
-   [x] Fix reapeated values in some features

    -   [x] Fix feature `airline_name`, i.e,: "Air Asia" to "AirAsia"
    -   [x] Fix features `flight_dep` and `flight_arr`, i.e,: "BOM" to "Mumbai"

-   [ ] Encode features from categorical to numerical
    -   [ ] `airline_name`
    -   [ ] `flight_dep`
    -   [ ] `flight_arr`

> Exploratory Data Analysis

> Price Prediction using Machine Learning
