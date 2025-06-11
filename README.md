# Birds_Migration_Analyysis-Power-Bi#

This repository contains the **BIRD_MIGRATION_DATASET**, a comprehensive dataset for analyzing migratory patterns of birds across different regions and environmental conditions using **Power BI**.

---

## 📊 Project Objective

The main goal is to uncover actionable insights on bird migration by leveraging DAX, visualizations, slicers, KPIs, maps, and interactive dashboards in **Power BI**. These insights support wildlife researchers, ecologists, and conservationists in understanding:

- average flight distance by species and region 
- how does weather condition impact average speed of flight 
- which month have the longest average migration duration 
- average tag battery level of birds
- highest recorded flight distance
- average recovery time of birds

---

## 🗃️ Dataset Structure

Each row in the dataset represents one bird's migration instance with detailed attributes including geography, environmental metrics, and behavioral traits.

| Column Name                | Description |
|---------------------------|-------------|
| Bird_ID                   | Unique identifier for each bird |
| Species                   | Bird species name |
| Region                    | Region where migration occurred |
| Habitat                   | Type of habitat involved |
| Weather_Condition         | General weather during migration |
| Migration_Reason          | Reason for migration (e.g. breeding, seasonal) |
| Start_Latitude, Start_Longitude | GPS start point |
| End_Latitude, End_Longitude     | GPS end point |
| Flight_Distance_km        | Total distance migrated |
| Flight_Duration_hours     | Total flight time |
| Average_Speed_kmph        | Speed averaged across the flight |
| Max_Altitude_m, Min_Altitude_m | Altitude range during migration |
| Temperature_C             | Average temperature during migration |
| Wind_Speed_kmph           | Wind speed during migration |
| Humidity_%                | Humidity percentage |
| Pressure_hPa              | Atmospheric pressure |
| Visibility_km             | Visibility in kilometers |
| Nesting_Success           | Success of nesting attempt (1 = success, 0 = failure) |
| Tag_Battery_Level_%       | Remaining battery level of GPS tag |
| Signal_Strength_dB        | Signal strength of tag |
| Migration_Start_Month     | Month migration began |
| Migration_End_Month       | Month migration ended |
| Rest_Stops                | Number of rest stops taken |
| Predator_Sightings        | Number of predator sightings |
| Tag_Type                  | Type of GPS tracking tag used |
| Migrated_in_Flock         | Boolean flag for flock migration |
| Flock_Size                | Number of birds in the flock |
| Food_Supply_Level         | Food supply level during migration |
| Tracking_Quality          | Quality rating of the tracking data |
| Migration_Interrupted     | Boolean flag for interruptions |
| Interrupted_Reason        | Reason for interruption (if any) |
| Tagged_By                 | Researcher/organization that tagged the bird |
| Tag_Weight_g              | Weight of the tag in grams |
| Migration_Success         | Boolean flag indicating successful migration |
| Recovery_Location_Known   | Boolean flag for known recovery location |
| Recovery_Time_days        | Time taken to recover the bird data |
| Observation_Counts        | Number of times the bird was observed |
| Observation_Quality       | Quality rating of observations |
| Origin                    | Origin location name |
| Destination               | Destination location name |

---

Screenshot-: ![image alt](https://github.com/Vikas-Sajwan/Birds_Migration_Analysis-Power-Bi/blob/426c388d19ff75ce6caed630cec2ae4588207d47/Dashboard%20Screenshot.png)
