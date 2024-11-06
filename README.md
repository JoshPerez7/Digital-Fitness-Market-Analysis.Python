# Digital Fitness Market Analysis

## Project Overview

As a product manager for a fitness studio, we are interested in understanding the current demand for digital fitness classes. This project aims to conduct a market analysis using Python to gauge demand and identify potential areas for growth of digital products and services.

## Data

We are provided with several CSV files in the "Files/data" folder, containing international and national-level data on Google Trends keyword searches related to fitness and related products. The datasets include:

### workout.csv
| Column             | Description                                              |
|--------------------|----------------------------------------------------------|
| month              | Month when the data was measured.                        |
| workout_worldwide  | Index representing the popularity of the keyword 'workout', on a scale of 0 to 100. |

### three_keywords.csv
| Column                    | Description                                                             |
|---------------------------|-------------------------------------------------------------------------|
| month                     | Month when the data was measured.                                       |
| home_workout_worldwide    | Index representing the popularity of the keyword 'home workout', on a scale of 0 to 100. |
| gym_workout_worldwide     | Index representing the popularity of the keyword 'gym workout', on a scale of 0 to 100.  |
| home_gym_worldwide        | Index representing the popularity of the keyword 'home gym', on a scale of 0 to 100.     |

### workout_geo.csv
| Column              | Description                                                             |
|---------------------|-------------------------------------------------------------------------|
| country             | Country where the data was measured.                                    |
| workout_2018_2023   | Index representing the popularity of the keyword 'workout' during the 5 year period. |

### three_keywords_geo.csv
| Column                    | Description                                                             |
|---------------------------|-------------------------------------------------------------------------|
| country                   | Country where the data was measured.                                    |
| home_workout_2018_2023    | Index representing the popularity of the keyword 'home workout' during the 5 year period. |
| gym_workout_2018_2023     | Index representing the popularity of the keyword 'gym workout' during the 5 year period.  |
| home_gym_2018_2023        | Index representing the popularity of the keyword 'home gym' during the 5 year period.     |

## Objective

1. Determine the Peak Global Interest in 'Workout': Identify the time period when the global search interest for the keyword 'workout' was at its highest.

2. Analyze Keyword Popularity During and Post-COVID: Assess which fitness-related keyword ('home workout', 'gym workout', 'home gym') was the most popular during the COVID-19 pandemic and which one is currently the most popular.

3. Compare Workout Interest by Country: Identify the country with the highest interest in workouts among the United States, Australia, and Japan.

4. Evaluate Home Workout Interest: Determine which country, between the Philippines and Malaysia, has the highest interest in home workouts.

By achieving these goals, the project will provide insights into global and regional trends in digital fitness, helping to identify potential areas for growth and opportunities for digital fitness products and services.
