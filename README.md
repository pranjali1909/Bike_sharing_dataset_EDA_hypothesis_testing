# Yulu Bike Sharing - EDA & Hypothesis Testing

## Project Overview

This project involves exploratory data analysis (EDA) and hypothesis testing on the Yulu Bike Sharing dataset. The primary objective is understanding the factors influencing bike rentals and providing actionable recommendations to optimize the bike-sharing service.

## Key Insight

1. **Seasonal Preferences**:
   - Summer and fall seasons see higher bike rentals compared to other seasons.
   - Clear weather conditions are associated with more bike rentals.

2. **Impact of Holidays**:
   - Bike rentals increase significantly on holidays.

3. **Day Type Influence**:
   - Slightly more bikes are rented on weekends and holidays than on weekdays.

4. **User Patterns**:
   - Registered users (mainly office commuters) are more active on weekdays.
   - Casual users (mainly tourists and recreation seekers) are more active on weekends.

5. **Weather Preferences**:
   - Both casual and registered users prefer warm climates with favorable humidity (>20%) and wind speed conditions (<35 kph) for riding bikes.

## Recommendations

1. **Optimize Inventory for Seasonal Demand**:
   Increase bike stock during summer and fall to meet higher rental demand and maximize revenue.

2. **Holiday and Weekend Readiness**:
   Ensure additional bike availability during holidays and weekends to capitalize on higher demand during non-working days.

3. **Weather-Responsive Inventory Management**:
   Reduce the number of bikes on days with extreme temperatures (below 10°C or excessively hot) or very low humidity to align supply with expected lower demand.

4. **Targeted User Engagement**:
   Implement marketing campaigns tailored to casual users on weekends and registered users on weekdays to enhance user satisfaction and increase rentals.

5. **Weather-Adaptive Maintenance Schedule**:
   Schedule bike maintenance on days with unfavorable weather conditions (e.g., high winds >35 kph or thunderstorms) to ensure bikes are ready for optimal usage during clear weather periods.

## Files in the Repository

- **Yulu Bike Sharing - EDA & Hypothesis Testing.ipynb**: Jupyter notebook containing the complete analysis, visualizations, and hypothesis testing.
- **README.md**: This README file provides an overview of the project, key insights, recommendations, and usage instructions.

## Usage Instructions

1. **Prerequisites**:
   - Python 3.x
   - Jupyter Notebook
   - Required Python libraries: pandas, numpy, matplotlib, seaborn, scipy

2. **Running the Analysis**:
   - Clone the repository to your local machine.
   - Open the Jupyter Notebook (`Yulu Bike Sharing - EDA & Hypothesis Testing.ipynb`).
   - Run the cells sequentially to reproduce the analysis, visualizations, and results.

3. **Exploring the Results**:
   - Review the EDA section to understand the data distribution and initial observations.
   - Check the hypothesis testing section for the statistical tests performed and their outcomes.
   - Refer to the insights and recommendations provided at the end of the notebook for actionable strategies.
