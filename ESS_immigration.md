#### Motivating question(s)

How we chose this data set (broadly: ESS; narrowly: specific survey questions)

What we hope to get out of it

How does the willingness to accept particular immigrant groups into a country vary across different European countries?

Jews

Muslims

Gypsies

Which countries’ respondents have a strong affinity for or aversion to a particular immigrant group? Which countries’ respondents have a strong affinity for or aversion to immigration in general?

#### Methodology
What methods we chose to use and why

Chose to use histograms, bar graph to represent mean
Mean as a summary statistic

No outliers (values from 1-4), so the measure does not need to be robust to outliers

Representative sample, so do not need to sample further from minority groups

#### Results
Plot of the top 5 and bottom 5 overall unwillingness to accept immigrants (means)

Represent 2.5 as 0 to show distance from neutrality

#### Interpretation
Identify countries with specific affinity/aversion to a particular group

## Abstract

## ~Title goes here~
How do Europeans feel about Jewish, Muslim, and Gypsy immigration?

## Interpretation/analysis

As of 2014, the group that is least preferred for immigration among Europeans is Gypsies. This is consistently true all European nations. Generally, the most preferred group of these three are Jews.

Do countries with a strong preference against immigration from one group tend to have a strong preference against immigration over all three groups?

(yes?)

Do countries with a strong preference for immigration from one group tend to have a strong preference for immigration over all three groups?

(not necessarily, especially not when there is a preference for Jewish immigration. Nobody particularly likes Gypsy/Muslim immigrants?)

Do any countries not follow the order of preference Jews, Muslims, Gypsies?

(I don't think so?)

## Results
-plot of cdf for all groups-

This plot shows the cumulative distribution for each of the three variables (measuring how much the respondent wants to allow immigrants who are Jews, Muslims, or Gypsies) among all the respondents.


-plot of all the countries-

This plot shows the breakdown by country of the mean values for each of the three variables.

Each country is on the x axis. The y axis shows the difference between the mean response and 2.5  or the middle "neutral" value, where positive values indicate more unwillingness to accept immigrants from that group into their country and negative values indicate more willingness to accept those immigrants.

-plot of top 5 countries-

This figure has the same format as the figure above, but shows only the countries with the 5 lowest and 5 highest mean values for the mean of all the three variables.

## Methodology

This analysis is based on the European Social Survey (ESS) Round 7 done in 2014. We used three variables from the survey where the respondent indicated whether they would like to allow many, some, few, or none of the people of each group (Jews, Muslims, and Gypsies).

The text of the question for Jewish people is as follows, and the other two are of the same format:

I am going to ask you about different groups of people who might come to live in [country] from other countries. Using this card, please tell me to what extent you think [country] should allow? ...Jewish people from other countries to come and live in [country]?

  The possible allowed responses were:

  * 1: 	Allow many to come and live here 	

  * 2: 	Allow some 	

  * 3: 	Allow a few 		 

  * 4: 	Allow none 	

  * 7: 	Refusal

  * 8: 	Don't know

  * 9: 	No answer

We considered values 1-4 valid and removed the other responses from our analysis. Thus, we set our "neutral" value to 2.5.

To provide an overview of the values for each variable, we plotted the cumulative distribution function for each of the variables in the dataset to compare them.

In order to understand this information more, we examined the same variables country by country. For each respondent, we identified their country and value for each one of these variables. We found the mean by country for each of the variables. We also did this for the sum of the values across all the three questions. We found the distance from the neutral value of the mean in each case. We chose to use the mean as a summary statistic because we didn't need to be too concerned with outliers since the values were bounded from 1 to 4. We were then able to compare the mean values for various countries for each of the three variables.

We then chose to look at the extreme cases (the 5 highest and 5 lowest mean values overall).
