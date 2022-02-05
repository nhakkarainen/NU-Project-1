# Project-1

## Project Title 
Distribution of the environmental burden in Chicago 

## Team Members
* Ankita Mukhopadhyay
* Fatima Eldes
* Nicole Hakkarainen
* Caroline Shah
* Devyn Spruell

## Project Description/Outline
We are interested in analyzing the correlation between environmental complaints versus socioeconomic factors such as unemployment, income thresholds, and demographics. We will be utilizing three different data sets in which we will extract environmental complaints from the first, socioeconomic factors from the second, and demographic information from the third. We plan to merge data using APIs in order to overlap the different datasets over Zipcode/neighborhoods to determine if there is any correlation between the number of complaints versus the socioeconomic and demographic factors from certain areas. We will be analyzing data from the time period of 01-01-2010 to 12-31-2010. 

## Research Questions to Answer
1. What types of environmental complaints occured in Chicago during CY2020?
2. Are areas with lower income bearing more environmental burden?
3. Are environmental burdens distributed unequally in areas with minority communities? 

## Datasets to be used:
1. Chicago Data Portal: Environmental Complaints: provides types and details of 1,262 environmental complaints during CY2010 by street address.
2. Chicago Data Portal: Socioeconomic indicators of public health -  provides poverty, unemployment, and income demographics by neighborhood from years 2008-2012
3. CMAP 2010 Census Data Summarized to Chicago Community Area - provides race, gender, housing demographics by neighborhood
<br> *Use Google Places API(?) to merge datasets so that we can connect street address with neighborhood in Chicago - Possible Chicago neighborhood mapper

## Rough breakdown of tasks: 
### Ankita & Fatima
- Use Pandas to clean and format datasets
- Create a Jupyter notebook describing data exploration and cleanup process

### Nicole
- Create a Jupyter notebook illustrating final data analysis
- Use Matplotlib to create 6 - 8 visualizations of data (~2 per ‘question’)
- Save PNG images to visualizations
- Create a write-up summarizing major findings; include a heading for each question and short description of relevant findings

For Q1, What types of environmental complaints occured in Chicago during CY2020?
* Pie chart - complaint type
* Bar chart - # of complaints per complaint type
* Box and Whisker plot - frequency by complaint type?

### Caroline
- Create a Jupyter notebook illustrating final data analysis
- Use Matplotlib to create 6 - 8 visualizations of data (~2 per ‘question’)
- Save PNG images to visualizations
- Create a write-up summarizing major findings; include a heading for each question and short description of relevant findings

For Q2, Are areas with lower income bearing more environmental burden?
* Scatter plot? X - income - frequency of complaint; linear regression
* Bar - neighborhoods / by complaints (color bars by region)

### Devyn
- Create a Jupyter notebook illustrating final data analysis
- Use Matplotlib to create 6 - 8 visualizations of data (~2 per ‘question’)
- Save PNG images to visualizations
- Create a write-up summarizing major findings; include a heading for each question and short description of relevant findings

For Q3, Are environmental burdens distributed unequally in areas with minority communities?
* Charting the different races vs. neighborhoods
* Line graph by race



