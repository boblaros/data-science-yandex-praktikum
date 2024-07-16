# Age Estimation Model

## Client
"Khleb-Sol" Supermarket

## Context
Khleb-Sol is implementing a computer vision system to process customer photos at checkout areas. This system will estimate customers' ages to analyze purchases and suggest relevant products for their age group. Additionally, it will monitor cashiers' compliance when selling alcohol.

## Project Goal
Develop a model that estimates a person's age from a photo with a Mean Absolute Error (MAE) of no more than 8.

## Data Insights
- Peaks around "milestone" ages likely due to rounding by annotators.
- Age distribution is relatively normal with major peaks around 30 years and 1-5 years.
- Ages range from 1 to 100 years.
- Photos are in color and black-and-white, various sizes, correctly oriented.

## Model
- A model was trained to estimate age from photos.
- The final MAE on the test set is 7.13. Although MAE increased initially during training and then decreased, indicating overfitting, the model meets the goal with MAE <= 8.