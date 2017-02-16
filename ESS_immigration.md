

# How do Europeans feel about Jewish, Muslim, and Gypsy immigration?
Celina Bekins and Apurva Raman

We wanted to understand how Europeans felt about immigration, so we used data from the [European Social Survey](http://www.europeansocialsurvey.org/) to explore this space. Upon looking at the data, we found the questions about particular immigrant groups compelling and wanted to find out how the responses varied by country per group. We were also interested in knowing which group was preferred overall.

## Interpretation/analysis

As of 2014, the group that is least preferred for immigration among Europeans is Gypsies. This is consistently true throughout all European nations. Generally, the most preferred group of these three is Jews.

We can see in Figure 1 that the countries with high mean values for one group tend to have high mean values for all groups. This indicates that countries with a strong preference against immigration from one group tend to have a strong preference against immigration over all three groups.

However, as we can see in Figure 1, the countries with the low mean values for a particular group tend to have low mean values for the other groups with the exception of Israel, which has an expectedly strong preference for immigration of Jews.

From Figure 2, it is clear by comparing  that even among the countries with the highest and lowest preference for immigration, respondents tend to prefer Jewish immigration the most, Muslim immigration second, and Gypsy immigration third.

(I don't think so?)

## Results
![CDF](/cdf.png)

Figure 1. This plot shows the cumulative distribution for each of the three variables (measuring how much the respondent wants to allow immigrants who are Jews, Muslims, or Gypsies) among all the respondents.

Jewish Immigrants

![Full Jew](/fulljew.png)

Muslim Immigrants

![Full Mus](/fullmus.png)

Gypsy Immigrants

![Full Gyp](/fullgyp.png)

Figure 2. This plot shows the breakdown by country of the mean values for each of the three variables.

Each country is on the x axis. The y axis shows the difference between the mean response and 2.5, the middle "neutral" value. Positive values indicate less willingness to accept immigrants from that group into the country and negative values indicate more willingness to accept those immigrants.

Jewish Immigrants

![Short Jew](/shortjew.png)

Muslim Immigrants

![Short Mus](/shortmus.png)

Gypsy Immigrants

![Short Gyp](/shortgyp.png)

Figure 3. This figure has the same format as the figure above, but shows only the countries with the 5 lowest and 5 highest mean values for the means of all three variables.

## Methodology

This analysis is based on the European Social Survey (ESS) Round 7 done in 2014. In one section of the survey, the respondent indicated whether they would like to allow many, some, few, or none of the people of each of three groups: Jews, Muslims, and Gypsies. The responses for each of these groups became the three variables we used in our analysis.

The text of the question for Jewish people is as follows, and the other two are of the same format:

"I am going to ask you about different groups of people who might come to live in [country] from other countries. Using this card, please tell me to what extent you think [country] should allow? ...Jewish people from other countries to come and live in [country]?"

  The possible allowed responses were:

  * 1: 	Allow many to come and live here 	

  * 2: 	Allow some 	

  * 3: 	Allow a few 		 

  * 4: 	Allow none 	

  * 7: 	Refusal

  * 8: 	Don't know

  * 9: 	No answer

We considered values 1-4 valid and removed the other responses from our analysis. Thus, we set our "neutral" value to 2.5.

To provide an overview of the values for each variable, we plotted each cumulative distribution function to compare them.

In order to understand this information more, we examined the same variables country by country. For each respondent, we identified their country and variable values. We found the mean by country for each variable. We also did this for the mean of the values across all three questions. We found the difference between the neutral value and the mean in each case. We chose to use the mean as a way of summarizing information because the fact that the values were bounded 1 to 4 made outliers an irrelevant concern. We were then able to compare the mean values for various countries for each of the three variables.

We then chose to look at the extreme cases (the 5 highest and 5 lowest mean values overall).
