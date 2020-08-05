# Project-1-Meteorites

# How Much Do We Know About Meteorite Landings On Earth? 

Questions We Found Interesting & What Motivated us to answer them

Project Description:
- We were interested in exploring Meteorite Landings Data from NASA, Data.Gov. to examine how many meteorites were landed on earth. 
- We were also interested in looking at articles about meteorites published in NYT.

Research Questions to Answer:
1) How Many Meteorites Were Found? 
2) Which Meteorites Were Found in the Earliest Year?
3) What Sizes of Meteorites Were Found So Far? 
4) Where Were the Largest Meteorites’ Landing Spots?
5) What Types of Meteorites Do We Have? 
6) Which Countries Found More Meteorites?
7) Is There a Difference on The # of Meteorites Between Northern vs Southern Hemispheres?
8) How Many Articles About Meteorites Were Published in NYT? What Were the Contents?

We obtained data from DATA.GOV and disovered that a CSV file was available, with a large data set: Total Data Rows were 45,716.
- We cleaned up the Date and Time column to include only the year of landing.
- Obtained City and Country Name using ‘citipy’
- We compiled how many meteorites were recorded, separated into Year Ranges of <1900, 1900-1999, and 2000-2020.
- Using the information in the <1900 bin, we found the earliest 10 meteorites found on earth, and created a map using the geolocation data.
- Using the original data frame, we located the size ranges of the meteorites found by gram.
- Using our Data.Gov data, as well as google for clarification, we recorded and created a chart for the different types of materials contained in meteorites.
- We then used our city/country data to determine which countries had the most meteorite landings, as well as which hemisphere had the most meteorite strikes.
- We also found that the Northern Hemisphere, even though it had fewer meteorite strikes, had an average meteorite size (in grams) that was higher than the Southern Hemisphere.

Since meteorites have more of a social impact, rather than economic, we decided to include the NYT Article Search API to find out what impact meteorite landings have on people's lives.
- We discovered that meteor sightings are a great source of delight to people all over the world, and newer developments in science have allowed meteor sightings to be predicted and enjoyed by all people, all over the world.
- We also discovered that there is quite a demand for the purchase of meteorites, due to the "extra terrestrial" qualities. We discovered that some areas of the world that have had significant meteorite landings have used meteorites as a way to make money - sometimes in small amounts, and sometimes upwards of $300,000.

Conclusions & Implications of Our Findings
- We had a great dataset from NASA DATA.Gov. for our project! A real time, scientific data was available. We used lots of methods, resources, and techniques that we learned from the class.

- More meteorites’ data was available from late 1900s, probably, due to more technology & resources availability (satellites, geolocation systems, international data exchange etc.)

- New Zealand and South Africa had more meteorite landings records; therefore, southern hemisphere had more meteorite records than northern hemisphere

- The NYT Article Search showed 11 articles from 2003-2020. Compared with the meteorites’ scientific records, the number of articles of meteorites was very small. Maybe, people are not interested in much about meteorites?

- We could have used NYT Archives or other article resources to search more articles about meteorites; however, we lost two teammates during the project week, and we could not do much for the section :(

- It was interesting to know people’s interests beside science: the monetary value of meteorites People are trying to find and sell meteorites!





