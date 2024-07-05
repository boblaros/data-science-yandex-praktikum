# Real Estate Data Analysis Project

This project focuses on analyzing data from the **Yandex.Real Estate** service, specifically an archive of apartment sale listings in St. Petersburg and nearby localities over several years.

**Objective**: Identify parameters to develop an automated system for detecting anomalies and fraudulent activities.

Each apartment listing includes two types of data: user-provided and automatically generated based on cartographic data. For instance, distances to the city center, airport, nearest park, and water body are provided.

## Table of Contents

1. Project Description
2. Data Overview
3. Data Preprocessing
4. Data Design
5. Data Exploration
6. Conclusion

## Column Descriptions

- `airports_nearest`: Distance to the nearest airport in meters (m)
- `balcony`: Number of balconies
- `ceiling_height`: Ceiling height in meters (m)
- `cityCenters_nearest`: Distance to the city center in meters (m)
- `days_exposition`: Number of days the listing was posted (from publication to removal)
- `first_day_exposition`: Publication date
- `floor`: Floor number
- `floors_total`: Total number of floors in the building
- `is_apartment`: Boolean indicating if it's an apartment
- `kitchen_area`: Kitchen area in square meters (m²)
- `last_price`: Price at the time of removal from publication
- `living_area`: Living area in square meters (m²)
- `locality_name`: Name of the locality
- `open_plan`: Boolean indicating if it has an open floor plan
- `parks_around3000`: Number of parks within a 3 km radius
- `parks_nearest`: Distance to the nearest park in meters (m)
- `ponds_around3000`: Number of ponds within a 3 km radius
- `ponds_nearest`: Distance to the nearest pond in meters (m)
- `rooms`: Number of rooms
- `studio`: Boolean indicating if it's a studio apartment
- `total_area`: Total area of the apartment in square meters (m²)
- `total_images`: Number of images in the listing

## Research Plan

1. **[Project Description](#1)**
   - Introduction to the project and objectives.

2. **[Data Overview](#2)**
   - Detailed examination of the dataset structure and contents.

3. **[Data Preprocessing](#3)**
   - Cleaning and preparing the data for analysis.

4. **[Data Design](#4)**
   - Designing data models and frameworks for the study.

5. **[Data Exploration](#5)**
   - Analyzing the data to uncover patterns and insights.

6. **[Conclusion](#6)**
   - Summarizing findings and proposing next steps.

By following this structured plan, we aim to gain meaningful insights from the real estate data and develop an effective system to detect anomalies and potential fraudulent activities.