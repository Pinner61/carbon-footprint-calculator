# Carbon Footprint Calculator

A simple and interactive Streamlit web application that estimates a user's annual carbon footprint based on transportation, electricity usage, diet, and waste generation.

## Overview

The Carbon Footprint Calculator is a Python-based web app designed to help users understand how everyday lifestyle choices contribute to yearly CO2 emissions. Users can enter basic information such as commute distance, monthly electricity consumption, number of meals per day, and weekly waste generation. The app then calculates an estimated carbon footprint and breaks it down by category.

This project is useful for sustainability awareness, environmental education, and learning how software applications can be used to present real-world climate-related data in a simple and accessible way.

## Features

- Interactive Streamlit user interface
- Country-based carbon footprint calculation
- Estimates annual CO2 emissions from:
  - Transportation
  - Electricity usage
  - Diet
  - Waste generation
- Displays category-wise emission results
- Calculates total yearly carbon footprint
- Clean and beginner-friendly Python project structure
- Simple interface suitable for educational and awareness-focused use

## Tech Stack

- Python
- Streamlit

## Project Structure

```text
carbon-footprint-calculator/
│
├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
├── LICENSE             # License file
└── .gitignore          # Git ignored files
```

## How It Works

The app takes user inputs and applies predefined emission factors to estimate the annual carbon footprint.

The main calculation categories include:

```text
Transportation = Daily commute distance × 365 × transportation emission factor

Electricity = Monthly electricity usage × 12 × electricity emission factor

Diet = Number of meals per day × 365 × diet emission factor

Waste = Weekly waste generated × 52 × waste emission factor
```

The final result is displayed in tonnes of CO2 per year, along with a breakdown of emissions by category.

## Installation

Clone the repository:

```bash
git clone https://github.com/Pinner61/carbon-footprint-calculator.git
cd carbon-footprint-calculator
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit app:

```bash
streamlit run app.py
```

## Usage

1. Select your country.
2. Enter your daily commute distance in kilometers.
3. Enter your monthly electricity consumption in kWh.
4. Enter the amount of waste generated per week in kilograms.
5. Enter the number of meals consumed per day.
6. Click the calculate button to view the estimated carbon footprint.

## Example Output

The application displays:

- Transportation emissions in tonnes of CO2 per year
- Electricity emissions in tonnes of CO2 per year
- Diet emissions in tonnes of CO2 per year
- Waste emissions in tonnes of CO2 per year
- Total annual carbon footprint

## Future Improvements

- Add more countries with region-specific emission factors
- Include different transportation modes such as car, bus, train, cycling, and walking
- Add renewable energy usage as an input
- Improve the accuracy of emission factors using verified environmental datasets
- Add charts and visual comparisons for better result interpretation
- Add downloadable reports for users
- Improve the user interface and mobile responsiveness

## Project Purpose

This project was created to practice building data-driven web applications using Python and Streamlit. It also demonstrates how software tools can be used to make sustainability-related information easier to understand for everyday users.

## License

This project follows the MIT License included in the repository.
