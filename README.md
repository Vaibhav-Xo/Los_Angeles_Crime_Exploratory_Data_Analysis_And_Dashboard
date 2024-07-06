# Los_Angels_Crime_Dataset_2020_Exploratory_Data_Analysis_And_Dashboard

![360_F_312695758_6vTfVYCRbqIUX8WlxjF0Syb03dJbvk6r](https://github.com/Vaibhav-Xo/Los_Angels_Crime_Dataset_2020__Exploratory_Data_Analysis/assets/172389348/c2ca2526-4555-4e17-af62-4130994d559d)
### Colab Link: https://colab.research.google.com/drive/1Fk8IJz_x1IqUG-dQN1bQaTjvGb49R5fb?usp=sharing
### Dashboard(.pbix) Link: https://drive.google.com/file/d/1UV58AMlzUd8glkb-q7jv8LuXZ2R6ppu8/view?usp=sharing
#### Note: As the dashboard file size is large for github, I have uploded it on drive where you can download the file and view the dynamic dashboard 


## Dashboard:
![Screenshot 2024-07-05 151518](https://github.com/Vaibhav-Xo/Los_Angels_Crime_Dataset_2020__Exploratory_Data_Analysis/assets/172389348/403ad71e-aebf-4a14-8ead-c168366e1ecb)


## Project Objective
The objective of this project is to conduct a comprehensive exploratory data analysis (EDA) of Los Angeles crime data. By leveraging advanced data visualization techniques and statistical analysis, I aim to uncover patterns, trends, and insights that can help public safety strategies.

## About Dataset
The dataset consist of 499 rows and 13 columns which include likes of DR_NO[Data Record Number], Date_Rptd, Date_Occ, Area_Name, Crm_Cd(Crime Code), Crm_Cd_Desc(Crime Code Description), Vict_Age, Vict_Sex, Premis_Desc(Premise Description), Status, Loaction, LAT, LAN.  

## Tools And Libraries Used
* Google Colab
* Pandas
* Numpy
* Matplotlib 
* Seaborn 
* Plotly
* Folium
* Power Bi

## Steps Performed 
### 1] Dataset Exploration 
* Loading CSV 
* Checking Shape of Dataset
* Checking Column Datatypes
* Checking Null Values
* Identifying Outliers

### 2] Data Preprocessing
* Filling Null Values
* Creating New Columns [Month_Rptd,Year_Rptd,Month_Occ,Year_Occ]
* Checking Unique values in Columns
* Creating new categories for analysis purpose by clubbing existing values in column 
* Deleting irrelevent columns for analysis

### 3] Data visualization
### Univariate Analysis 
* Drawing insights by checking distribution for each column at a time using charts like: [Countplot, Histogram, Piechart]

#### Bivariate Analysis
* Drawing insights by checking trends and relation between two columns simultaneously using charts like: [Boxplot, Heatmaps, Scatterplot, LinePlot]

#### Spatial Analysis
* Plotting Map to visualize hotspots of crime.

## Insights Drawn From Analysis
* 1] Crime Hostpots of LA
* 2] Top Occuring Crimes in LA
* 3] Distribution of Victim based on their age 
* 4] Count of crime based on Victim gender
* 5] Most dangerous premis in LA
* 6] Popular type of case in LA
* 7] Dangerious Regions of LA
* 8] No. of crime reported past years in LA 
* 9] No. of crime reported in each month of 2020 in LA 
* 10] Victims Age in different areas of LA 
* 11] Type of Crime commited in each area in LA
* 12] Type of Crime commited in different regions of LA 
* 13] Distribution of gender of victim affected from each crime type.
* 14] Distribution of victims gender and their corrosponding age
* 15] Age of victims involved in different crime premis
* 16] Victims age in different regions in LA 
* 17] Corrdinates of Crime hotspots
* 18] Age of Victms involved in crime reported over different Month in Los Angels
* 19] Crime Reported over the months for different gender in Los Angels
* 20] Spatial View of LA

## Conclusion 
* 1] Central Region of LA is most dangerous and active when comes to crime 
* 2] Theft is the top Occuring crime of LA
* 3] Majority of the victims where in their 30s and where Males
* 4] Streets are the most dangerous premis in LA followed by Sidewalks, Parking Lots, Aprtments etc
* 5] Majority of the crime were Individul Crime followed by Armed Attacks
* 6] January and February are the most dangerous month in LA lots of crime occour during this two months foloowed by December

#### Remember, data analysis is an ongoing adventure. So grab trenchcoat 🕵️‍♂️, investigate further, and keep drawing those insights! 🚨 Feel free to expand upon this conclusion or add any additional findings you discover. Happy analyzing! 😊👮‍♂️🚔
