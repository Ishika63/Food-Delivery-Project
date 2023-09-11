# Problem Statement
Food Delivery services like Zomato and Swiggy need to show the accurate time it will take to deliver your order to keep transparency with their customers. These companies use Machine Learning algorithms to predict the food delivery time based on how much time the delivery partners took for the same distance in the past.

To predict the food delivery time in real-time, we need to calculate the distance between the food preparation point and the point of food consumption. After finding the distance between the restaurant and the delivery locations, we need to find relationships between the time taken by delivery partners to deliver the food in the past for the same distance.


## Usage
To use the food delivery prediction system, follow these steps:

1. Provide input data, including order details, weather conditions, and traffic information.
2. The system will predict the estimated delivery time based on historical data and machine learning models.
3. Display the estimated delivery time to the customer for transparency.



## Data Description

The dataset used in this project includes the following columns:

| Column Name                | Description                                      |
| -------------------------- | ------------------------------------------------ |
| ID                         | Unique identifier for each record                |
| Delivery_person_ID         | Unique identifier for the delivery person        |
| Delivery_person_Age        | Age of the delivery person                       |
| Delivery_person_Ratings    | Ratings or feedback received by the delivery person |
| Restaurant_latitude        | Latitude of the restaurant                        |
| Restaurant_longitude       | Longitude of the restaurant                       |
| Delivery_location_latitude | Latitude of the delivery location                 |
| Delivery_location_longitude| Longitude of the delivery location                |
| Order_Date                 | Date when the food order was placed              |
| Time_Ordered              | Time of day when the food order was placed       |
| Time_Order_picked          | Time when the order was picked up from the restaurant |
| Weather_conditions         | Prevailing weather conditions during delivery     |
| Road_traffic_density       | Traffic conditions affecting delivery times      |
| Vehicle_condition          | Condition of the delivery vehicle                 |
| Type_of_order              | Type of food order (e.g., takeout, delivery)      |
| Type_of_vehicle            | Type of vehicle used for delivery                |
| multiple_deliveries        | Indicator for multiple deliveries on the same trip |
| Festival                   | Indicator for festivals or special events         |
| City                       | City or location of the delivery                  |
| Time_taken (min)          | Actual time taken for delivery (in minutes)       |

