# Data Modeling COVID-19 Spread using Data Analytics in Python

This project encompasses data modeling and analyzing COVID-19 spread with the use of data science and data analytics in Python. This analysis helps to find the scope of the virus spread from purely a dataset perspective.

There are a myriad number of data sources on the web that provide COVID-19 related data. For this project, I used the data set provided by John Hopkins University's Center for Systems Science and Engineering. You can access this data through this github link: https://github.com/CSSEGISandData/COVID-19. 

The data splits across worldwide confirmed cases, deaths, and recovered cases. To figure how the spread has progessed over a period of time, I plotted the confirmed cases using plotly.graph_objects.

For the first part, I did some exploratory analysis on the data and summarized some statistics by plotting trends in existing data.

# Graphical Progression

![Screen Recording 2020-08-12 at 12 15 13 AM](https://user-images.githubusercontent.com/59805673/89974508-4b1e3300-dc31-11ea-9f15-ecc2bbbd0acb.gif)

The sharp exponential curve towards the right end of the graph shows the mortifying rate at which the pandemic is spreading globally.

I continued to look at the progression of recovered and death cases in respect to the confirmed cases.

![Screen Recording 2020-08-12 at 12 19 04 AM](https://user-images.githubusercontent.com/59805673/89974612-8ae51a80-dc31-11ea-9940-60eaae4ed291.gif)


# Heatmap on World Map

For the second half of the project, I plotted a 2D heatmap with Matplotlib. This graphical representation of data uses a system of color-coding and intensity to represent different values. Specifically, I used plotly.express to create a mapbox density map in which each row of data frame is represented as a point smoothed with a given radius of influence. The larger the circle, the higher the number of cases. You can reference the datasets in the files uploaded above. 

Note: Since the datasets are not updated automatically and require manual changes, the two maps below illustrate the number of cases (confirmed and deaths) on August 9, 2020 when I extracted the data.

Worldwide Confirmed Coronavirus Cases (August 9, 2020)

![Screen Recording 2020-08-12 at 12 21 42 AM](https://user-images.githubusercontent.com/59805673/89974739-e1eaef80-dc31-11ea-8871-99b9eda285e2.gif)

Worldwide Coronavirus Deaths (August 9, 2020)
![Screen Recording 2020-08-12 at 12 24 05 AM](https://user-images.githubusercontent.com/59805673/89974863-38582e00-dc32-11ea-8eef-956cef2394b8.gif)


If you would like to see the most updated graphs and map models, you can use the github link mentioned in the beginning, download the datasets as a csv file (or convert the link to csv in jupyter notebook), and run my code after importing the new data.



