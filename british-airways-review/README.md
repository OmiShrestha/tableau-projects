# British Airways Reviews Analysis

This project analyzes British Airways reviews from different countries across the world. The analysis is based on two CSV files: `countries.csv` and `ba_reviews.csv`.

## Table of Contents
- [Project Overview](#project-overview)
- [Datasets](#datasets)
  - [countries.csv](#countriescsv)
  - [ba_reviews.csv](#bareviewscsv)
- [Usage](#usage)

## Project Overview
This repository contains data and scripts for analyzing British Airways (BA) reviews from various countries. The analysis aims to understand the sentiment and quality of service provided by BA in different regions, continents, and countries.

## Datasets

### countries.csv
This file contains information about different countries, including their code, continent, and region.

| Column     | Description                      |
|------------|----------------------------------|
| `country`  | Name of the country              |
| `code`     | ISO country code                 |
| `continent`| Continent the country belongs to |
| `region`   | Specific region within the continent |

### ba_reviews.csv
This file contains detailed reviews of British Airways from different countries. The dataset includes various attributes related to the travel experience.

| Column                  | Description                                    |
|-------------------------|------------------------------------------------|
| `review_id`             | Unique identifier for the review               |
| `country_code`          | ISO country code (matches `code` in `countries.csv`) |
| `aircraft`              | Model/type of the aircraft                     |
| `traveller_type`        | Type of traveller (e.g., Business, Leisure)    |
| `seat_type`             | Type of seat (e.g., Economy, Business)         |
| `rating`                | Overall rating given by the reviewer           |
| `seat_comfort`          | Rating for seat comfort                        |
| `cabin_staff_service`   | Rating for cabin staff service                 |
| `food_beverages`        | Rating for food and beverages                  |
| `ground_service`        | Rating for ground service                      |
| `value_for_money`       | Rating for value for money                     |
| `entertainment`         | Rating for in-flight entertainment             |


## Usage
1. **Clone the repository:**
   ```bash
   git clone https://github.com/OmiShrestha/tableau-projects.git
   cd tableau-projects
   
