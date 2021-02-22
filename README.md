# python-api-challenge
 
## Introduction

This is an analysis of the weather for cities around the world using API queries. It is a cool exercise to blend in the Python with APIs, JSON and gmaps skills. With these, we are going to find the weather for any city you want to know.

## Instruction

In this analysis, *two* parts of analysis are done. 

1. The first part is called **WeatherPy**, which is to find cities weather across the world using the API key. Hundreds of random cities are selected from our raw data, and API inquiries are done to find weather information for those cities. The results from this part are exported to a **weather_data.csv** file, and graphs drew from this analysis are stored at the **Images** folder.

2. The second part is called **VacationPy**. This part is to base on the **weather_data.csv** from the first part, further narrow done to interested cities, and then use *gmaps* to find nearby hotels for those interested cities. Visualizations of hotel maps can also be seen in this part of analysis.

please refer to the following *three* files:

[starter_code](https://github.com/Grace-Bijun-Li/python-api-challenge/tree/main/starter_code)
- This is the folder that contains the **WeatherPy.ipynb** and **VacationPy.ipynb** notebooks. These notebooks are the main scripts to run this analysis.

[output_data](https://github.com/Grace-Bijun-Li/python-api-challenge/tree/main/output_data)
- This file consists two *.csv* files. The **cities.csv** is the raw data to start the analysis with. The **weather_data.csv** is the results output from the **WeatherPy** analysis.


[Images](https://github.com/Grace-Bijun-Li/python-api-challenge/tree/main/Images)
- This file consists the scatter plots and linear regression graphs drew from the **WeatherPy** analysis.

## Conclusion (**based on Part I - WeatherPy analysis**)

1. For the relationship between latitudes and max temperatures, as the latitude moves from the equator to the two poles of the earth, **northern hemisphere tends to have greater slope of declination of max temperatures** than the southern hemisphere. This is probably because the analysis is drawing for random **cities** selected. Hence, by common sense, there are a lot more cities located in high northern latitudes than in high southern latitudes. This means **more high northern latitudes data are captured in northern hemisphere**, which then causes the greater declination slope for the max temperature in northern hemisphere.

2. Similar logic may apply to the humidity vs. latitude changes in the two hemispheres. Cities in teh northern hemisphere tend to have greater changes in humidity as latitude changes. Generally, cities in the southern hemisphere have quite stable humidities.

3. In terms of wind speeds, both hemispheres have relatively stable wind speeds across the sample cities selected. Latitude changes do **not** impact the wind speed as much.