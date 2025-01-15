# Startup Funding Analysis App

This repository contains an interactive web application built using **Streamlit** for analyzing startup funding data. The application provides insights into overall funding trends and detailed investor-specific analytics. It is ideal for venture capitalists, entrepreneurs, or analysts looking to explore the startup ecosystem.

## Features

### Overall Analysis
- **Total Funding**: Displays the total amount of funding raised across startups.
- **Maximum Funding**: Identifies the startup with the highest single funding round.
- **Average Funding**: Calculates the average funding amount across all startups.
- **Number of Funded Startups**: Shows the total number of unique startups funded.
- **Month-on-Month (MoM) Analysis**: Interactive graph displaying funding trends over time (total amount or count of funding rounds).

### Investor-Specific Analysis
- **Recent Investments**: Displays the most recent investments made by a selected investor.
- **Biggest Investments**: Bar chart of startups receiving the highest investments from the selected investor.
- **Sector Analysis**: Pie chart showcasing the distribution of investments across different industry verticals.
- **Funding Round Analysis**: Pie chart of the investment amounts distributed across funding rounds.
- **City-Wise Investments**: Pie chart of investments categorized by city.
- **Year-on-Year (YoY) Analysis**: Line chart of the investor’s annual investment trends.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/akshat12375/startup-funding-analysis.git
   cd startup-funding-analysis
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the Streamlit app:
   ```bash
   streamlit run app.py
4. Open the app in your web browser at http://localhost:8501.
