# ada-2020-project-milestone-p3-p3_littlepandas
### Gender disparities in police stops across the United States

##### Abstract 
This research extension will change the focus from race to gender, in order to assess a potential bias in the police regarding the driver’s sex. This analysis will evaluate if state patrol and police departments officers’ decisions, i. e. stop, search and frisk decisions, are affected by the driver’s gender. The main idea is to assess if officers perform more frisk on women than on men. 

##### Research question(s)
Is there any bias existing in police stop decisions regarding the driver’s gender. How do the gender stop rates compare ? 
Is there any bias in decisions in frisk of the driver regarding its gender ?
What differences, if any, exist between different states regarding these disparities ? 

##### Proposed datasets 
Use of datasets available on https://openpolicing.stanford.edu/data/ : .csv files available to download. The analysis will focus on some state patrols and police departments of big cities for which the required data is provided (driver’s age, sex and race, state patrol or police department , location of the stop, whether a search was conduted and the outcome of the search, whether a frisk was performed, etc.). For example North Carolina, Tennessee (Nashville) or Louisiana (New Orleans) could be investigated, as they seem complete regarding the information needed. 

##### Methods 
Determine which states’ datasets contain enough useful information and choose at least 3 to perform inter-states comparisons, among state patrols and cities, if possible. 
Filtering of the datasets to ensure the used datasets contain the exclusivity of the needed information to perform the analysis. 
Data wrangling to get it operational for the statistical analysis.
Balance the dataset by matching man-woman pairs on the following features : category of age (probably dividing into <50 years old, >50y.o.), race, whether a search was conducted, the reason for the stop. These features will allow to avoid the infra-marginality problem discussed in the additional papers, as individuals with the most similar probability to be carrying contraband are matched. We match drivers on the race because it allows to avoid the racial bias in the frisk decision. We match drivers on the car search feature because it is an indicator of the officer suspicion to find contraband. We match drivers on the age because the desire to performed unmotivated frisk as well as the probability of the driver to carry contraband might decrease with the age of the driver.
Evaluate the mean difference in outcome “Frisk performed” of all pairs. 
Present and discuss the results, compare results from different states/cities. 
Address outlook and improvements of the analysis, and further information that could have been interesting to perform our analysis (antecedents of stopped/frisked people and sexual orientation of the officer).

##### Proposed timeline 
P3 due on the 27.11.20.
 - Week 30.11 : choice of states that present enough complete information, data wrangling, computation of stop rates.
 - Week 07.12 : Matching of pairs, outcome results computation. 
 - Week 14.12 : present, compare and discuss results.
Extension analysis due on the 18.12.20. 

##### Organization within the team 
We will first distribute all our data equally among each member.

Each member of the group  will be responsible for the data wrangling and computation of stop rates for their data

Then we will assign someone to write the analyse and the two others will do pair programming for the rest of the analysis. 

In group we will aggregate the results and discuss them.

##### Questions for TAs (optional)
Would it make sense to match the man-woman pairs also over the feature ‘Contraband found’? 

