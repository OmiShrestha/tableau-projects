# British Airways Reviews Analysis

This project analyzes British Airways reviews from different countries across the world. The analysis is based on two CSV files: `countries.csv` and `ba_reviews.csv`.

## Table of Contents
- [Project Overview](#project-overview)
- [Datasets](#datasets)
  - [countries.csv](#countriescsv)
  - [ba_reviews.csv](#bareviewscsv)
- [Usage](#usage)
- [Analysis](#analysis)
- [Contributing](#contributing)
- [License](#license)

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
This file contains reviews of British Airways from different countries.

| Column        | Description                                           |
|---------------|-------------------------------------------------------|
| `review_id`   | Unique identifier for the review                      |
| `country_code`| ISO country code (matches `code` in `countries.csv`)  |
| `review`      | Text of the review                                    |
| `rating`      | Rating given by the reviewer                          |
| `date`        | Date of the review                                    |

## Usage
1. **Clone the repository:**
   ```bash
   git clone https://github.com/OmiShrestha/ba-reviews-analysis.git
   cd ba-reviews-analysis
