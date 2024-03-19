# How-Cyclistic-customers-use-bikes-differently

Cyclistic, a fictional company, has launched a successful bike-sharing program. The program has now expanded into a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. Cyclists can unlock a bike from one station and return it to any other station in the system anytime.

The director of marketing thinks that the company's future success hinges on maximizing the number of annual memberships. To achieve this, they want to understand the differences between how casual riders and annual members use Cyclistic bikes. They plan to design a new marketing strategy that will convert casual riders into annual members based on these insights. However, Cyclistic executives must approve the recommendations, so they must be supported by compelling data insights and professional data visualizations.

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

- **Load Data:**
  - Load "q1_2019.csv" with Rows: 365069 and columns: 12.
  - Load "q2_2019.csv" with Rows: 1108163 and Columns: 12.
  - Load "q3_2019.csv" with Rows: 1640718 and Columns: 12.
  - Load "q4_2019.csv" with Rows: 704054 and Columns: 12.

- **Rename Column names in q2_2019.csv for Merging**

- **Merge Data:**
  - Merge the loaded data frames (from previous steps) into a single data frame named "all_trip_2019" with Rows: 381 Million(381,800,412) and Columns: 12.


## Summarizing:

- **Female-riders:** 857 Thousand(857,978)
- **Male-riders:** 2.4 Millions(2,400,820)

- **Casual riders:** 880 Thousand (880,637) 
- **Member riders:** 2.9 Million(2,937,367) 

- **Avg ride duration:**
  - Casual riders: 57.01802
  - Member riders: 14.32780
  - All riders: 24.17

- **Min ride duration:**
  - Casual riders: 1.016667
  - Member riders: 1.016667
  - All riders: 1.02

- **Max ride duration:**
  - Casual riders: 177200.4
  - Member riders: 150943.9
  - All riders: 177200.37

- **Median ride duration:**
  - Casual riders: 25.83333
  - Member riders: 9.80000
  - All riders: 11.82

## Analysis or User Trends:

### Key Insights:

1. **No of Rides by Weekdays:**
![number_of_rides_by_weekday](https://github.com/Vivek-S1n9h/Cyclistic-Case-Study-with-R/assets/121023465/8cb8f93c-1393-4ca8-aecd-f0ea7c030403)

2. **No of Rides by Months:**
![no_of_rides_by_month](https://github.com/Vivek-S1n9h/Cyclistic-Case-Study-with-R/assets/121023465/9a3dd91d-327c-41aa-9cc6-6458a969f0c1)

3. **Avg duration by Weekdays:**
![rides_avg_duration_by_weekday](https://github.com/Vivek-S1n9h/Cyclistic-Case-Study-with-R/assets/121023465/4b192c9c-32ec-4b53-8fb7-865bf1ae71eb)

4. **Avg duration by Months:**
![avg_duration_by_month](https://github.com/Vivek-S1n9h/Cyclistic-Case-Study-with-R/assets/121023465/8db45e40-e289-41db-a2ac-5714f71cd19e)


## Conclusions and Insights:
1. **Casual vs. Member Usage:**
   - Casual users exhibit significantly longer average ride durations compared to members.
   - Casual riders contribute substantially to weekend rides, particularly on Saturdays and Sundays
   - Member rides are evenly spread throughout the week.
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
