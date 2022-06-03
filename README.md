<h1 align="center">NYC Airbnb - Machine Learning Based Predictive Analysis</h1>

<h2>Data Description</h2>

The given dataset has 12 features as explained below:

- `id` | The unique ID assigned to every hotel.
- `region` | The region in which the hotel is located..
- `latitude` | The latitude of the hotel.
- `longitude` | The longitude of the hotel.
- `accommodation_type` | The type of accommodation offered by the hotel. For example: Private room, Entire house/apt, etc.
- `cost` | The cost of booking the hotel for one night. (in \$\$)
- `minimum_nights` | The minimum number of nights stay required.
- `number_of_reviews` | The number of reviews accumulated by the hotel.
- `reviews_per_month` | The average number of reviews received by the hotel per month.
- `owner_id` | The unique ID assigned to every owner. An owner can own multiple hotels.
- `owned_hotels` | The number of hotels owned by the owner.
- `yearly_availability` | It indicates if the hotel accepts bookings around the year. Values are 0 (not available for 365 days in a year) and 1 (available for 365 days in a year).


<h2>Objective</h2>

The main objective is to train a ML model to predictct `yearly_availability`.
  
Objective could be sub-divided as follows:

- Data Wrangling & Visualization
  - Dealing with Null and duplicate values
  - Outlier detection
  - Outlier removal
  - Label Encoding of Catagorical Variables
  - Scaling of Data
- Modeling
  - Fit a decision tree classifier (`yearly_availability` as target)
  - Cross Validation
  - Generate predictions on Test Set
