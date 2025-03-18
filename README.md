# New York City AirBnb Data Analysis

New York City AirBnb Data Analysis using Excel

## Objective: Providing guidance to potential host/invester on the property types to invest in New York City Neighborhood

## Executive Summary
The following anaysis is to determine the most attractive vacation rental in Manhattan, so that it provides a guidance on which property types to invest in:
1. Analysis show that Lower East Side, Hells Kitchen and Harlem are the top 3 popular rental neighborhoods.
2. 1 bedroom type properties are more popular than any other types.
3. The top listing generates  $29,940.00 in a single month.

### Summary
  ➔	Methods/Techniques: Cleaned data, created new columns for new data calculation, used formulas, VLOOKUP, pivot tables, pie charts and graphs.

  ➔	Results: 1 bedroom type properties are more popular than other types. Lower East Side, Hells Kitchen and Harlem are the top 3 popular rental neighborhoods based on the number of reviews earned, with Lower East Side 1-bedroom properties earning an average annual revenue of $68134.83.

  ➔	Recommendations: Suggested investing in 1-bedroom properties in the Lower East Side, Hells Kitchen and Harlem neighborhood.

The Excel File can be found here: [NYC AirBnb Rental Data Analysis](https://docs.google.com/spreadsheets/d/1KHray3mL1PWpxHVrHHHsYnM-rqO_PNyQ/edit?gid=324620310#gid=324620310)
(Note some excel features were removed unintentionally when uploading file in Google Drive)

Raw data file can be found here: [NYC AirBnb Rental Data](https://docs.google.com/spreadsheets/d/1wwAMY7OQLe7u36yPVbKu9dSmWuIwNMHb/edit?usp=share_link&ouid=109309021359791811778&rtpof=true&sd=true)

The top 10 Neighborhoods in Manhattan: 

<img src="https://github.com/vandanadhakal/New-York-City-AirBnb-Data-Analysis/blob/main/Top%2010%20Neighborhood.png">

Attractive bedroom size for top neighborhood:

<img src="https://github.com/vandanadhakal/New-York-City-AirBnb-Data-Analysis/blob/main/Top%20Neighborhood-%20Attractive%20Bedroom%20Type.png">

### Assumptions
1. Popularity is assumed based on the number of reviews left in the past 12 months.
2. Data only reflects from 09/07/2022 - 10/06/2022. Yearly revenue is calculated assuming this data as a reflection of 30 day(month) period.

### Data Cleaning Steps
1. Removed inconsistent capitalization and trailing spaces from "neighborhood" column to "neighborhood_clean" column.
2. Cleaned data from "bedrooms" column to "bedrooms_clean" column replacing empty cells by 0(zero) indicating studio apartment.








