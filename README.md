# **planet_dataset_analysis**
In my project, I first tried to understand the story behind the planet dataset. This dataset contains information such as the discovery dates of planets, the methods of their discovery, their masses, and their distances from the galaxy. The method column in the dataset is of type object and, since it is a nominal variable, it was not mandatory to convert it to category type. However, I converted it to category in order to make the analysis more understandable. I noticed that there were missing values in the dataset, so I filled them either with zero or with the mean of the corresponding column. After performing these steps, I used a barh chart based on the method categorical variable. I observed that the "Radial Velocity" method was used more frequently for planet discovery. When I researched the reason, I found that the "Radial Velocity" method is dominant in the dataset because it was developed earlier, has a wide range of applications, and is considered highly reliable.
<img width="1123" height="514" alt="image" src="https://github.com/user-attachments/assets/a701a04c-7982-4138-8f6e-9bb2c450e39d" />
# **diamonds_dataset_analysis**
In this project, I performed certain analyses on the diamonds dataset. The diamonds dataset provides information about different types of diamonds. Since variables like color, cut, and clarity are ordinal-type objects, I converted them to category type. I then visualized my analyses using various plots, such as histograms. For example, I found which price ranges diamonds appear most frequently in the dataset.

However, analyzing this dataset alone was not sufficient for me to interpret it correctly; therefore, I added the cut column as a hue (used to add a new category) parameter. Using this plot, I set the x-axis according to the minimum and maximum values I had previously found in the histogram. Based on my analyses, I can say that Ideal, the highest quality diamonds, are mostly concentrated in the $2000–$3000 range in my dataset. From this, I can conclude that in the market, high-quality but low-priced diamonds are more common.
<img width="968" height="520" alt="image" src="https://github.com/user-attachments/assets/80e928a6-2c1d-4243-a5c3-89e8aaa14981" />
# **tips_dataset_analysis**
The Tips dataset briefly shows how many customers visited a restaurant, on which days and during which time intervals, and how much tip they left. I used this dataset to perform analyses, particularly employing violin and boxplot plots. This allowed me to understand the purpose and use of these types of graphs.

I would like to explain one of my analyses: the boxplot graph. (Boxplots are especially important in machine learning to show whether a dataset contains outliers; they are also quite effective as they display the median.) I placed the days on the x-axis and the total bills on the y-axis. To see how much men and women paid during these time intervals, I categorized the data using the gender column. Based on my results, I can say that the average total bill paid by men is higher than that paid by women.
<img width="1025" height="491" alt="image" src="https://github.com/user-attachments/assets/1b17d658-17d2-4ffa-9850-60b0794fc701" />
# **tips_dataset_analysis2**
In another analysis on the Tips dataset, I used correlation plots, namely lmplot and scatterplot. Scatterplots and lmplots are used to show the relationship between numerical values. For example, if there is a direct proportion between two numerical variables in my dataset, it indicates a positive correlation; if there is an inverse proportion, it indicates a negative correlation. Additionally, in lmplot, the more the data points cluster around the line, the stronger the correlation is.

But what exactly is a strong correlation? A strong correlation indicates that the predictions made by the graph are very close to the actual values. For instance, if the total bill is 20 TL and the tip given is 3 TL, looking at the graph, the more the data points for that price cluster around the line, the stronger the correlation is.

I analyzed the relationship between the total bill and tips for customers who smoke and do not smoke, according to lunch and dinner hours. Based on my results, I observed that more customers, both smokers and non-smokers, visit the restaurant during dinner hours. This information can help the restaurant owner pay more attention to these peak hours.
<img width="1671" height="624" alt="image" src="https://github.com/user-attachments/assets/ce2c0ea0-5cd9-4dd2-aebc-8f97795b3b17" />
# **iris_dataset_analysis**
I used the Iris dataset to better understand pairplot graphs. A pairplot relates each column in the dataset to the others, allowing us to observe the relationships between values. For example, if we put the Iris dataframe into a pairplot and analyze it based on the species column:

Looking at the fourth row, when we examine the relationship between sepal_length and petal_length in the first column by species, the distributions are not completely uniform for each species, indicating a weak relationship. The second column shows a similar pattern. However, in the third column, when looking at the relationship between petal_length and petal_width, a strong correlation is observed for each species. This indicates that petal_width is closely related to petal_length but has little effect on sepal_length.

In the last column, we can see how petal_width is distributed among species. For Setosa, the frequency is high but petal_width is low; for Versicolor, the frequency is moderate and petal_width values are slightly higher; and for Virginica, the frequency is relatively low but petal_width is at the highest level. This shows that petal_width is an important variable for distinguishing species and, when used together with petal_length, highlights the differences between species more clearly.
<img width="1385" height="561" alt="image" src="https://github.com/user-attachments/assets/dd3261b4-9d50-4a5f-acc9-e82be058e6ef" />
#**flights_dataset_analysis**
The Passengers dataset shows the total number of passengers on specific dates. I used this dataset to better understand heatmap graphs. From my analysis, I observed that the number of airline passengers increases especially during the summer months and gradually rises over the years. This indicates that people travel more in the summer and that air travel has become increasingly popular over time.
<img width="938" height="530" alt="image" src="https://github.com/user-attachments/assets/140dba51-3e77-40dd-8ce1-d7203218ae59" />


























