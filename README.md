# World_Population_by_Country
An analysis of World Population by Country

This is an attempt to analyze the data “World Population by Country” which is available in Kaggle. The dataset can be downloaded using the following link: https://www.kaggle.com/datasets/rajkumarpandey02/2023-world-population-by-country
1.	Data Overview
    The dataset comes with column names and most of the names are self-explanatory.  It has 19 columns: country, rank, area, landAreaKm, cca2, cca3, 
    netChange, growthRate, worldPercentage, density, densityMi, place, pop1980, pop2000, pop2010, pol2022, pop2023, pop2030, and pop2050.

     There are three categorical columns: country, cca2, cca3 which identify a country by name, two letter and three letter abbreviations. In our 
     analysis we did not use two letter abbreviation of a country. There are 234 countries. We use 18 features for our study.

     The data set has blank entries for netChange and worldPercentage fields. The missing values for countries which are ranked towards the bottom and 
      other countries which have values and ranked towards the bottom have 0.0 for both fields. So, we filled the missing values by 0.0. Except 
      netChange, growthRate, and worldPercentage fields, almost all fields have distinct values. Out of 18 features, 16 features have numeric values and 
      7 features have float/decimal numbers.

2.	Country by Area

  	2.1. Top 10 Country by Area

  	  Top 10 countries in the decreasing order of area are: Russia, Canada, China, United States, Brazil, Australia, India, Argentina, Kazakhstan, and 
      Algeria.

    2.2.	Bottom 10 Country by Area

  	  Bottom 10 countries in the increasing order of area are: Vatican City, Monaco, Gibraltar, Tokelau, Saint Barthelemy, Nauru, Tuvalu, Macau, Sint 
      Maarten, and Saint Martin.

3.	Country by Net Change

  	3.1.	Top 10 Country by Net Change

  	   Top 10 countries in the decreasing order of net change are: India, Nigeria, Pakistan, DR Congo, Ethiopia, Indonesia, Tanzania, United States, 
       Philippines, and Bangladesh.

    3.2.	Bottom 10 Country by Net Change

  	   Bottom 10 countries in the increasing order of net change are: Poland, Japan, Russia, China, Romania, Hungary, Italy, Lebanon, Moldova, and 
       Slovakia.

4.	Country by Growth Rate

  	4.1.	Top 10 Country by Growth Rate

  	   Top 10 countries in the deceasing size of growth rate are: Syria, Moldova, Niger, DR Congo, Chad, Somalia, Mali, Angola, Mayotte, and Tanzania.

    4.2.	Bottom 10 Country by Growth Rate

  	   Bottom 10 countries in the increasing size of growth rate are: Ukraine, Lebanon, Bulgaria, Lithuania, Latvia, Serbia, American Samoa, United 
       States Virgin Islands, Bosnia and Herzegovina, and Wallis and Futuna.

5.	Country by World Percentage
   
     5.1.	Top 10 Country by World Percentage

  	   Top 10 countries in the decreasing order of world percentage are: India, China, United States, Indonesia, Pakistan, Nigeria, Brazil, 
       Bangladesh, Russia, and Mexico.

     5.2.	Bottom 10 Country by World Percentage

  	   Bottom 10 countries in the increasing order of world percentage are: Vatican City, Isle of Man, Antigua and Barbuda, United States Virgin 
       Islands, Saint Vincent and Grenadines, Aruba, Seychelles, Tonga, Jersey, and Micronesia.

6.	Country by Density

    6.1.	Top 10 Country by Density

  	   Top 10 Countries in the decreasing order of density are: Macau, Monaco, Singapore, Hong Kong, Gibraltar, Bahrain, Maldives, Malta, Bangladesh, 
       and Sint Maarten.

    6.2.	Bottom 10 Country by Density 

  	   Bottom 10 countries in the increasing order of density are: Greenland, Falkland Islands, Western Sahara, Mongolia, Namibia, Australia, Iceland, 
       French Guiana, Libya, and Suriname.

7.	Country by Place

     7.1.	In this analysis place of a country is the ISO-3166-1 Numeric Code of a country

     7.2.	Top 10 Country by Place

  	   Top 10 countries in the decreasing order of place are: Zambia, Yemen, Samoa, Wallis and Futuna, Venezuela, Uzbekistan, Uruguay, Burkina Faso, 
       United States Virgin Islands, and United States.

     7.3.	Bottom 10 Country by Place

  	   Bottom 10 countries in the increasing order of place are: Afghanistan, Albania, Algeria, American Samoa, Andorra, Angola, Antigua and 
       Barbuda, Azerbaijan, Argentina, and Australia.

8.	Population Prediction

    8.1.	Population Prediction for Top 10 Country

  	   Based on the analysis India overtook China in 2022-2023 to become the most populous country in the world. While India’s population will grow in 
       the future, China’s population will decline further. Next, Nigeria’s population will overtake Pakistan and by 2050 it’s population will be 
       close to the population of the United States which has the third largest population in the world.

    8.2.	Population Prediction for Bottom 10 Country

  	   According to the analysis population of Vatican City will remain flat in the future. Next, the population of Tokelau will overtake the 
       population of Niue around 2025-2026. The population of Niue declined since 1980 until 2010 and then the growth rate is almost flat reaching 
       more than 2000 by the year 2050.

9.	Correlation Matrix

  	 We use Pearson Correlation Coefficients to determine linear relationship between two features/columns. Columns area and landAreaKm are linearly 
     dependent. worldPercentage and all the population columns by year are linearly dependent. density and densityMi are linearly dependent. Finally, all 
     the columns for population by year are linearly dependent on each other. For the above dependent features, Pearson Correlation Coefficients are
  	 greater than 0.90.
