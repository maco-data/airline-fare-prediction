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

-   [ ] Encode features for data Analysis
    -   [x] Extract months and days from `flight_date`
    -   [x] Extract hours and mins from `dep_time` and `arr_time`
    -   [x] Extract hours and mins from `flight_time`
    -   [x] Convert `airline_name`to numerical data
    -   [x] Connvert `flight_dep` to numerical data
    -   [x] Convert `flight_arr`to numerical data

> Exploratory Data Analysis

-   [ ] Considering simplifying features name i.e.: `flight_fare` to `price`, etc.

    -   [ ] Change flight_fare to price
    -   [ ] Change flight_time to duration
    -   [ ] Change airline_name to airline
    -   [ ] Change flight_dep to dep
    -   [ ] Change flight_arr to arr

-   [ ] Create test data
    -   [x] Split data
    -   [ ] Feauture selection for prediction

> Price Prediction using Machine Learning
