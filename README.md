
readme_content = """
# Lilly Tours and Travels Dashboard

## Project Overview
The Lilly Tours and Travels Dashboard is an interactive Power BI
dashboard designed to analyze customer bookings, revenue,
tour packages, popular destinations, and payment methods.

## Key Performance Indicators (KPIs)
- Total Customers: 900
- Total Revenue: ₹55M

## Dashboard Features
1. Year-wise Analysis
2. Booking Source Analysis
3. Monthly Booking Trends
4. Customers by State
5. Main Travel Destinations
6. Tour Package Analysis
7. Payment Mode Analysis
8. Customer Ratings
9. Trip Type and Vehicle Type Analysis

## Tools Used
- Microsoft Power BI
- Microsoft Excel

## Project Objective
To analyze travel business performance, understand
customer preferences, identify popular destinations,
and support better business decisions.

## Conclusion
This dashboard provides useful insights into booking
patterns, revenue generation, and customer preferences.
"""

with open("README.md", "w", encoding="utf-8") as file:
    file.write(readme_content)

print("README.md file created successfully!")
