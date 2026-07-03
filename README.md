# AFL Match Data Integration

## Project Overview

This project focuses on integrating multiple Australian Football League (AFL) datasets to create a comprehensive dataset for analysis and machine learning. The primary objective is to enrich player round-by-round statistics with corresponding match information such as venue, attendance, match result, and home/away status.

The integrated dataset enables deeper analysis of player performance within different match contexts.

---

## Objectives

- Clean and preprocess multiple AFL datasets.
- Standardize column names and data formats.
- Merge player statistics with match-level information.
- Handle missing values and inconsistent records.
- Create a final integrated dataset suitable for analysis and predictive modeling.

---

## Datasets Used

### 1. Player Round-by-Round Statistics
Contains individual player performance for every AFL match.

Examples of attributes:
- Player ID
- Player Name
- Team
- Opponent
- Season
- Round
- Kicks
- Handballs
- Marks
- Tackles
- Goals
- Fantasy Points

---

### 2. Team Match Information
Contains match-level information including:

- Season
- Round
- Team
- Opponent
- Venue
- Home/Away
- Crowd Attendance
- Match Result

---

## Data Preprocessing

The following preprocessing steps were performed before integration:

- Loaded datasets using Pandas.
- Removed duplicate records.
- Standardized team names.
- Renamed inconsistent columns.
- Converted seasons and rounds to consistent data types.
- Checked for missing values.
- Verified merge keys.

---

## Data Integration

The datasets were merged using common identifiers such as:

- Season
- Round
- Team
- Opponent

Additional contextual match information was appended to every player record, including:

- Home/Away status
- Venue
- Crowd attendance

---

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## Project Structure

```
project/
│
├── afl_players_round_by_round_stats_raw.csv
├── team_matches_home_away_raw.csv
├── AFL_Match_Data_Integration.ipynb
├── integrated_afl_dataset.csv
└── README.md
```

---

## Output

The final integrated dataset contains:

- Complete player statistics
- Match venue
- Home/Away indicator
- Crowd attendance
- Match context

This dataset is ready for:

- Exploratory Data Analysis (EDA)
- Player performance analysis
- Feature engineering
- Predictive modeling
- Data visualization

---

## Skills Demonstrated

- Data Cleaning
- Data Integration
- Data Wrangling
- Data Validation
- Dataset Merging
- Feature Engineering
- Pandas Operations
- Handling Missing Values
## Author

**Mehreen Fatima**

```

This README is suitable for inclusion in your GitHub repository and clearly documents the AFL Match Data Integration task in a professional format.
