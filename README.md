# Election_Analysis

## Overview

The purpose of this project was to analyze and summarize the election results from 2018 for three Colorado counties and output the results into an easy-to-read text file. When completed, the text file shows analytics such as votes per county, total votes, the winner of the election and more. The benefit of using code and computers to do the work for us is vastly greater than sitting and counting the votes by hand. Using Python, math equations and election results can be displayed in mere seconds. 

## Election-Audit Results

- ### Total Votes

![Total](https://user-images.githubusercontent.com/60283799/171488460-3b1b0c1f-4f94-4823-b4bb-2525148d29f4.PNG)

In total, there were 369,711 votes cast between the three counties. As of 2020, the combined population of these counties was 1,944,653 total residents. This means that the percentage of people who votes was 19.01%. This seems low, but we have to take into account that many of these residents could be minors, new to the area, or not have American Citizenship as of the time of the election. 

- ### Votes per County 

![Votes per county](https://user-images.githubusercontent.com/60283799/171492086-f6624d0a-05b7-44b4-80e0-b44a52f195af.PNG)

When looking at votes per county it's clear that Denver county had the largest turnout at 82.8% of the total votes. One might think that this is because Denver has a higher population, but that is not quite the case. The population of Denver county (715,878) is not much bigger than Arapahoe (649,980) or Jefferson (578,795), yet it has a 70% higher turnout rate than the next county (Jefferson). From this analysis, it is unclear why that may be the case. 

![County winner](https://user-images.githubusercontent.com/60283799/171492660-ed327bf7-af48-4b19-ac1a-98bc17abe789.PNG)

- ### Votes per Candidate

![Candidate totals](https://user-images.githubusercontent.com/60283799/171494102-8248905c-3710-4cdb-94d6-38b99ecc0717.PNG)

The totals and percentages for the candidates were slightly closer than those for the counties, but not much. Charles made up for 23.0% (85,213) of the total election with Raymond Anthony Doane only getting 3.1% (11,606) of the votes. 

- ### Election Winner 

![Winner](https://user-images.githubusercontent.com/60283799/171495656-3087452e-fae7-459f-ad89-7bdf4cc88ada.PNG)

The landslide winner in this election was Diana Degette with 73.8% (272,892) of the total votes. She is still serving on the house of representatives to this day. 

## Summary 

This script was used to easily and quickly display the results for 2018 Colorado House of Representatives election and, with some modification, could be used to do the same for virtually any election. It is clearly much quicker than counting by hand with the same or even greater effectiveness. 

Some changes that could be made are:

- Modifying the script to read from a datatbase or API and convert the information to a text file or excel output.
- Writing the data to a website that neatly displays the results. Also possible to do a live version of this and have the results displayed as the votes come in.
- Adding other calculations such as percentage of votes by age, gender, income, or race.
