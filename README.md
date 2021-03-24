

# Project proposal for MTA turnstile data analysis

Innovative street marketing firm approaches my firm (JM Corp) with a need to find the highest foot traffic to distribute samples of a new beverage using NYC as a test market.  Publically available subway transit data seems like a good dataset to find foot traffic concentration.  Firm is undecided yet on specific boroughs (Manhattan, Queensi, etc.), days of week(weekend or weekday), or hour of the day.   

## Source data
The primary dataset will be the MTA turnstile data.

A secondary dataset may be the Station Locations to provide more information on individual stations. 
https://atisdata.s3.amazonaws.com/Station/Stations.csv


Both datasets are provided by the MTA and are anticipated to be easy to link 

## Approach
The turnstile data is available in a set of weekly CSV files in the format **turnstile_YYMMDD.csv** where YY is year, MM is month, and DD is the last day of the week (week ends on Saturday)
Each station has multiple turnstiles which each maintain there own cumulative trip counter - entries and exits by day need to be calculated for each turnstile and then aggregated for the stations. 

Data cleaning - not sure at this point what cleaning necessary

Ultimately station volumes will be compared to identify the greatest traffic at specific times and days.  

