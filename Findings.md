# Findings
-----

## Question 1: Which Chicago neighborhoods submitted the highest number of air pollution complaints in 2010?
-----
Overall, air pollution complaints were fairly scattered across neighborhoods in Chicago in 2010. At the regional level, the three regions with the highest number of air pollution complaints were: Southwest, Far North, and West regions of Chicago (seen in the barchart below). 

### Bar Chart of Number of Air Pollution Complaints by Region
![Q1_BarChart_Neighborhood](https://user-images.githubusercontent.com/95601005/153987375-a520ccf7-b5b1-44a9-b5f9-840198ed4007.png)

At the neighborhood level, there were no obvious differences between the number of complaints submitted by North, Central, and South side neighborhoods. The two neighborhoods with the highest number of complaints were West Englewood and Uptown with 14 and 12 complaints, respectively (seen in the barchart and heatmap below).

### Bar Chart of Number of Air Pollution Complaints by Neighborhood
![Q1_BarChart_Regions](https://user-images.githubusercontent.com/95601005/153987401-d07bcfe6-a695-49a6-af87-bd7e3abd4896.png)

### Heatmap of Number of Air Pollution Complaints by Neighborhood
![Q1_Heatmap](https://user-images.githubusercontent.com/95601005/153986093-c585def5-d39b-4e8c-b3ed-f36c172ba42d.png)

## Question 2: Did the number of air pollution complaints vary by neighborhood income level?
-----
There was virtually no correlation between the number of complaints submit by each neighborhood and the neighborhood per capita income (r-squared value of 0.00788), as seen in the line scatter plot with annotated linear regression model below.

### Scatter Plot of Number of Complaints by Neighborhood Per Capita Income
![Q2_ScatterPlot](https://user-images.githubusercontent.com/95601005/153986891-1305dd40-9331-4003-94b9-f3684c20977d.png)

The distribution of complaints submitted by higher- and lower-income neighborhoods was fairly similar overall, with both populations having the same median (4 complaints). The distribution of higher-income neighborhood complaints had a larger IQR and was more right-tailed than that for lower-income neighborhoods, indicating that a small number of high-income neighborhoods each submitted many complaints.

### Box Plots of Number of Complaints by Neighborhood Income Level
![Q2_Boxplot](https://user-images.githubusercontent.com/95601005/153987295-a33d23c2-8d0f-4434-803b-2cc04f83eff0.png)

## Question 3: Did the number of air pollution complaints vary by the presence of minority communities?
-----
There was no correlation between the number of complaints submit by each neighborhood and the neighborhood racial demographics (see scatter plot below).

### Scatter Plot of Number of Complaints by % Minority Population
![Q3_ScatterPlot](https://user-images.githubusercontent.com/95601005/153987548-094c550a-3900-43ee-9a3a-d924f254a572.png)

Interestingly, the racial composition of West Englewood and Uptown -- the two neighborhoods with the highest number of complaints -- were very different. West Englewood had a majority Black or African American population, whereas Uptown had a majority White population.
