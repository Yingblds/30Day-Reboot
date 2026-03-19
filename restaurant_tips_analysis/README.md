# Restaurant Tips Analysis

## Project Overview

This project analyzes tipping behavior using a restaurant dataset to uncover patterns that can help improve business decisions. The goal is to understand how factors such as total bill, time of day, and group size influence tipping.

## Objective

- Identify key factors that influence tipping behavior
- Explore relationships between bill size and tip amount
- Provide actionable insights for restaurant operations

## Business Questions

- Does tipping behavior vary by time of day (Lunch vs Dinner)?
- Is tipping proportional to the total bill?
- Do larger groups tip more that smaller groups?
- Are there differences in tipping across days of the week?

## Dataset

- Source: Seaborn built-in tips dataset
- Records: ~244 transactions
- Features include:
  •	Total bill
  •	Tip amount
  •	Time (Lunch/Dinner)
  •	Day of the week
  •	Number of people (size)

## Tool & Technologies

- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

## Key Insights

- Tipping is strongly correlated with total bill size
  Customers generally follow percentage-based tipping behavior.
  -> Implication: Increassing order value (e.g., upselling) can indirectly boost tips.

- Dinner generates higher total tips than lunch
  This is likely driven by larger group sizes and higher spending.
  -> Implication: Allocate more staff and focus on service quality during dinner hours.

- Larger groups contribute to higher overall tips
  Total tips increase with group size, although per-person tipping remains relatively stable.
  -> Implication: Restaurants can prioritize accommodating group customers.

- Tipping patterns are relatively consistent across days
  No major variation suggests stable customer behavior throughout the week.
  -> Implication: Operational strategies can remain consistent across weekdays.

## Conclusion

Tippping behavior is primarily driven by total bill size, with additional influence from time of day and group size. Dinner service and larger groups contribute the most to overall tip revenue. These insights can help restaurants optimize staffing, improve service focus, and increase revenue through strategic upselling.

## Future Improvements

- Include customer demographics for deeper insights
- Build a predicrtive model for tip estimation

## Author

Github: https://github.com/Yingblds

## Note

This project is part of my 30-day analysis reboot.
This repository contains both a full learning notbook (with detailed notes and intermediate steps) and a cleaned final version for presentation.