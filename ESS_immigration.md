# How do Europeans feel about Jewish, Muslim, and Gypsy immigration?
Apurva Raman and Celina Bekins

As tensions over immigration increase with Europe dealing with a huge influx of refugees, some countries are more ready to accept immigrants while others close their borders to them. To understand the opinions of Europeans on immigration of particular groups, we investigated if respondents from different countries in Europe have consistent opinions toward immigrant groups.

In order to answer this question, we used data from the most recent European Social Survey (ESS), which was Round 7 done in 2014. This was before the peak of the Syrian refugee crisis, but establishes a recent baseline for understanding attitudes toward immigration for Muslim immigrants relative to other groups. In one section of the survey, the respondent indicated whether they would like to allow many, some, few, or none of the people of each of three groups: Jews, Muslims, and Gypsies. The responses for each of these groups became the three variables we used in our analysis.

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

In order to understand this information more, we then examined the same variables country by country. For each respondent, we identified their country and variable values. We found the mean by country for each variable. We also did this for the mean of the values across all three questions. We found the difference between the neutral value and the mean in each case. We chose to use the mean as a way of summarizing information because the fact that the values were bounded 1 to 4 made outliers an irrelevant concern. We were then able to compare the mean values for various countries for each of the three variables.

We then chose to look at the extreme cases (the 5 highest and 5 lowest mean values overall).


![CDF](/cdf.png)

Figure 1. This plot shows the cumulative distribution functions (CDFs) for each of the three variables (measuring how much the respondent wants to allow immigrants who are Jews, Muslims, or Gypsies) among all the respondents. The blue line corresponds to Jews, the green line corresponds to Muslims, and the purple line corresponds to Gypsies.

As of 2014, the group that is least preferred for immigration among Europeans is Gypsies, indicated by the low values in the early part of the CDF. This is consistently true throughout all European nations (see Figure 3). Generally, the most preferred group of these three is Jews.


Jewish Immigrants

![Full Jew](/fulljew.png)

Muslim Immigrants

![Full Mus](/fullmus.png)

Gypsy Immigrants

![Full Gyp](/fullgyp.png)

Figure 2. This plot shows the breakdown by country of the mean values for each of the three variables.

Below are the countries that correspond to each abbreviation.

| Abbreviation  | Country       |
| :------------ |:--------------|
| AT            | Austria       |
| BE            | Belgium       |
| CH            | Switzerland   |
| CZ            | Czech Republic|
| DE            | Germany       |
| DK            | Denmark       |
| EE            | Estonia       |
| ES            | Spain         |
| FI            | Finland       |
| FR            | France        |
| GB            | United Kingdom|
| HU            | Hungary       |
| IE            | Ireland       |
| LT            | Lithuania     |
| NL            | Netherlands   |
| NO            | Norway        |
| PL            | Poland        |
| PT            | Portugal      |
| SE            | Sweden        |
| SI            | Slovenia      |

Each country is on the x axis. The y axis shows the difference between the mean response and 2.5, the middle "neutral" value. Positive values indicate less willingness to accept immigrants from that group into the country and negative values indicate more willingness to accept those immigrants. A mean of 1.5 corresponds to all respondents saying to allow none of the immigrants of that group, and a mean of -1.5 corresponds to all respondents saying to allow many of the immigrants of that group.

We can see by comparing the values for Jews, Muslims, and Gypsies for each country that the countries with high mean values for Muslims tend to have high mean values for Gypsies and vice versa. This indicates that countries with a strong preference against Jews or Gypsies will also not prefer the other group. This does not hold true for Jews; countries that are willing to allow Jews are not necessarily willing to allow Muslims or Gypsies. Countries that are not accepting of Jews are not accepting of any of these three groups. The clearest case of this is Israel, which has an expectedly strong preference for immigration of Jews but not the other groups.


Jewish Immigrants

![Short Jew](/shortjew.png)

Muslim Immigrants

![Short Mus](/shortmus.png)

Gypsy Immigrants

![Short Gyp](/shortgyp.png)

Figure 3. This figure has the same format as the figure above, but shows only the countries with the 5 lowest and 5 highest mean values for the means of all three variables.

Comparing the sorted data from the smaller set of countries allows us to clearly see the preference order of Jews, Muslims, and Gypsies even among the countries with the most extreme mean values. We can see that even the third most accepting country by mean is not welcoming to Gypsies. This more extreme set of countries tends to be more consistent in either preferring to accept or reject immigrants, which is to be expected given that outliers cannot have very much of an influence on a scale from -1.5 to 1.5.
