# US Bikeshare Data Analysis

This project is a **Python-based interactive program** that allows users to explore and analyze bikeshare data from three major US cities: **Chicago**, **New York City**, and **Washington**. The program provides statistics on user travel patterns, trip durations, popular stations, and user demographics.

## Features

- **Interactive User Input**: Users can filter data by city, month (January to June), and day of the week.
- **Time Statistics**: Calculates the most common month, day, and start hour of travel.
- **Station Statistics**: Identifies the most popular start and end stations, and the most frequent trip combinations.
- **Trip Duration Statistics**: Provides total and average trip durations.
- **User Statistics**: Displays counts of user types, gender distribution (if available), and birth year statistics (earliest, most recent, and most common).
- **Raw Data Viewing**: Allows users to view the raw data in increments of 5 rows upon request.

## Files

- `chicago.csv` — Contains bikeshare data for Chicago.
- `new_york_city.csv` — Contains bikeshare data for New York City.
- `washington.csv` — Contains bikeshare data for Washington.

## Technologies

- **Python 3**
- **Pandas** — For data manipulation and analysis.
- **NumPy** — For numerical operations.

## How It Works

1. The program prompts the user to select a city, month, and day for analysis.
2. It loads the corresponding CSV file and filters the data based on user input.
3. Calculates and displays:
   - Time statistics
   - Station statistics
   - Trip duration statistics
   - User statistics
4. Optionally displays raw data in chunks of 5 rows.
5. Users can choose to restart the analysis with different filters.

## Usage

Run the program in a Python environment:

```bash
python bikeshare.py