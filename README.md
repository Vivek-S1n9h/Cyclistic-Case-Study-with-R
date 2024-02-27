# How-Cyclistic-customers-use-bikes-differently
A [casetudy](https://github.com/Vivek-S1n9h/Cyclistic-Case-Study-with-R/blob/main/bike-share-trip-casestudy.ipynb) that analyzes the Cyclistic customer shared bike usage trends and then recommends the future marketing strategy.

## Dataset Source
[Cyclistic trip data](https://divvy-tripdata.s3.amazonaws.com/index.html)

## Business task or goal:
- Design marketing strategies aimed at converting casual riders into annual members.
  - Understand how annual members and casual riders usage trends.

## Tools used:

- **Microsoft Excel**
- **Kaggle**
- **R**
  - Packages used:
      - tidyverse - to wrangle and manipulate data - metapackage of all tidyverse packages
      - lubridate - to wrangle date attributes
      - ggplot2 - to visualize data

## Cleaning and Merging:


## Summarizing:

## Analysis or User Trends:

### Key Insights:



1. **No of Rides by Weekdays:**
![number_of_rides_by_weekday](https://github.com/Vivek-S1n9h/Cyclistic-Case-Study-with-R/assets/121023465/8cb8f93c-1393-4ca8-aecd-f0ea7c030403)

2. **No of Rides by Months:**
![no_of_rides_by_month](https://github.com/Vivek-S1n9h/Cyclistic-Case-Study-with-R/assets/121023465/9a3dd91d-327c-41aa-9cc6-6458a969f0c1)

3. **Avg duration by Weekdays:**
![rides_avg_duration_by_weekday](https://github.com/Vivek-S1n9h/Cyclistic-Case-Study-with-R/assets/121023465/4b192c9c-32ec-4b53-8fb7-865bf1ae71eb)

4. **Avg duration by Months:**
![avg_duration_by_month](https://github.com/Vivek-S1n9h/Cyclistic-Case-Study-with-R/assets/121023465/a95c6e5d-d300-4cea-ac60-a7f2852ca9b9)

## Conclusions and Insights:
1. **Casual vs. Member Usage:**
   - Casual users exhibit significantly longer average ride durations compared to members.
   - Casual riders contribute substantially to weekend rides, particularly on Saturdays and Sundays, while member rides are evenly spread throughout the week.
2. **Weekday Analysis:**
   - Both casual and member riders experience an increase in rides from Monday to Friday, with Friday being the peak day for casual users.
   - Member riders show a distinctive peak on Mondays and a gradual decline through the week.
3. **Monthly Trends:**
   - Casual ridership peaks during the summer months, notably in July and August, suggesting a potential tourist or seasonal rider trend.
   - Member ridership remains relatively consistent, with a slight dip during the winter months.
4. **Average Duration:**
   - Casual riders consistently have longer average ride durations across all weekdays and months compared to members.
  
## Questions to be considered now:
  - Why casual riders would buy a membership?
  - How digital media could affect their marketing tactics?

## Recommended strategy:
1. **Targeted Promotion Strategies:**
   - Implement targeted promotions or marketing campaigns for casual users during the summer months to capitalize on peak ridership.
   - Consider offering incentives or promotions for member riders on weekdays, especially on Mondays when member rides peak.
2. **Improving and Optimizing Service Quality:**
   - Enhance bike availability and service quality during weekends, particularly on Saturdays and Sundays, to accommodate higher demand from casual riders.
   - Explore the potential for introducing shorter-duration ride options to cater to the preferences of member riders who generally prefer shorter rides.
3. **Engage with riders and get feedback:**
   - Encourage user engagement through loyalty programs or exclusive offers for members to boost retention and loyalty year-round.
   - Solicit feedback from both casual and member riders to understand preferences and enhance overall user experience.
4. **Plan and Spend resources based on Season:**
   - Assess the need for additional bike stations or resources during peak months, especially in areas with high casual ridership, to ensure a seamless experience for all users.

By implementing these recommendations, the bike-sharing service can improve its offerings, attract and retain users, and optimize operations based on observed patterns in user behaviour.

## Acknowledgement
A great thanks to Motivate International Inc. for this [dataset](https://divvy-tripdata.s3.amazonaws.com/index.html). The data has been made available by Motivate International Inc. under this
[license](https://divvybikes.com/data-license-agreement) The datasets have a different name because Cyclistic is a fictional company.
