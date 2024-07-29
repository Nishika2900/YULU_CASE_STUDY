# YULU_CASE_STUDY

## Overview
This project involves analyzing a dataset related to bike-sharing usage for YULU. The goal is to gain insights from the data and build predictive models to understand and forecast bike demand.

## Dataset
The dataset includes the following columns:
- `datetime`: Date and time of the record
- `season`: Season of the year (1 = Spring, 2 = Summer, 3 = Fall, 4 = Winter)
- `holiday`: Whether the day is a holiday (1 = Yes, 0 = No)
- `workingday`: Whether the day is a working day (1 = Yes, 0 = No)
- `weather`: Weather condition (1 = Clear, 2 = Misty, 3 = Light Snow/Rain, 4 = Heavy Snow/Rain)
- `temp`: Temperature (in Celsius)
- `atemp`: Feels-like temperature (in Celsius)
- `humidity`: Relative humidity (in %)
- `windspeed`: Windspeed (in km/h)
- `casual`: Number of casual users
- `registered`: Number of registered users
- `count`: Total number of bike rentals

## Installation
To set up the environment for this project, you can create a virtual environment and install the required packages using the following steps:

1. Clone the repository:
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
