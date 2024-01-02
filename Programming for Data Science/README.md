# Programming For Data Science Project

## The Data

The datasets that are being used for my project are __countries of the world.csv__ and __life_expectancy.csv__. These datasets are from __Kaggle__ and the links to them are: https://www.kaggle.com/datasets/fernandol/countries-of-the-world and https://www.kaggle.com/datasets/amirhosseinmirzaie/countries-life-expectancy/data.

## __countries of the world.csv__:
 This dataset contains information about countries, the regions they belong to, population, area size, GDP, mortality and more. The "Countries of the World" dataset is derived from the World Factbook (https://gsociology.icaap.org/dataupload.html), which is a dataset created by the US government. As such, the data originates from US government sources. The World Factbook is a public domain resource, which means that anyone can use it freely without asking for permission. This characteristic makes it a suitable source for academic projects and research purposes because of the open accessibility and wide range of information it provides about different countries worldwide. The dataset's last update was 5 years ago.

The columns of this dataset are as follows: Country, Region, Population, Area (sq. mi.), Pop. Density (per sq. mi.), Coastline (coast/area ratio), Net migration, Infant mortality (per 1000 births), GDP ($ per capita), Literacy (%), Phones (per 1000), Arable (%), Crops (%), Other (%), Climate, Birthrate, Deathrate, Agriculture, Industry, Service.

### Accuracy

The accuracy and quality of this dataset can be proven by the fact that they are made up of data provided by the US government. Considering the source of this dataset, which is the US government and more specifically, the World Factbook, we can infer a very high degree of accuracy and data integrity. The World Factbook is a popular and reputable source used mainly by researchers, policymakers, and academicians globally. However, there are a few things to consider:

* __Timeliness__: The dataset's update frequency is unspecified and its last update was 5 years ago. It’s important to make sure the data is current, as outdated information can lead to skewed analysis.

* __Completeness__: While the World Factbook covers most countries, some information may be missing or not reported for specific nations due to political or other reasons.

* __Usability Score__: The dataset has a usability score of 8.24 on Kaggle, which means that users find it easy and efficient to work with.

## Additional Dataset Insights:

* __Engagement Metrics__: The dataset has seen significant engagement on Kaggle, with 295,912 views, 54,925 downloads, and a download-per-view ratio of 0.19. This amount of engagement indicates the dataset’s popularity and potential usability for different kinds of projects.

* __Collaboration and Discussion__: According to Kaggle, the dataset has inspired 177 notebooks, it has 287 comments and an upvote-per-notebook ratio of 6.62, which indicates that it is actively used and discussed within the Kaggle community.

* __License__: The dataset comes under the CC0: Public Domain license, providing unrestricted usage and the ability to freely integrate other datasets.

* __Potential for Merging__: The nature of this dataset—country-based attributes—makes it suitable for merging with other nation-specific datasets. By matching country names, one can easily append other datasets and their indicators, thus enriching the information base for comprehensive analysis.


## __life_expectancy.csv__:
 This dataset contains information about different countries in the world in regard to their life expectancy in the period between the years 2000-2015. The "Countries Life Expectancy" dataset is provided on Kaggle. It's primarily centered on the research of life expectancy and other related indicators across various countries. The exact origin of the data is not explicitly mentioned in the provided details, but given its focus, it can be speculated that the data could have been be compiled from various health organizations or global health surveys.

### Content and Attributes:
The dataset is dedicated to understanding life expectancy. This is a vital health metric that tells us the average lifespan of individuals in a specific country. The description indicates that an in-depth analysis has taken place and its aim is to unearth the reasons for the differences in longevity across different countries. Through this dataset, researchers could:

* __Explore the Relationship__: Between life expectancy and various factors such as diseases, socioeconomic conditions, and perhaps lifestyle or environmental factors.

* __Predictive Analysis__ : The dataset can act as input for performing predictive algorithms, providing predictions on life expectancy based on the associated indicators.

* __Statistical Tools__: Insights into the intricate connection between healthcare provisions, socioeconomic determinants, and life expectancy are drawn using robust statistical methodologies.

The columns of this dataset are as follows: Country, Year, Status, Population, Hepatitis B, Measles, Polio, Diphtheria, HIV/AIDS, infant deaths, under-five deaths, Total expenditure, GDP, BMI, thinness  1-19 years, Alcohol, Schooling, and Life expectancy.

### Accuracy and Quality:

The accuracy and quality of this dataset can be proven by the fact that its most recent update was 3 months ago, and it has excellent reviews and the following metrics also indicate its quality:

* __Usability Score__: This dataset has a perfect score of 10.00 in usability on Kaggle which could suggest that users find the dataset very accessible and user-friendly.

* __Engagement Metrics__: With 8,645 views and 1,699 downloads, there's a decent level of engagement, which proves its relevance and utility for various projects.

* __Community Feedback__: The dataset has prompted 8 notebooks with a total of 90 comments and a high upvote-per-notebook ratio of 18.75. These metrics suggest that the Kaggle community actively uses and values this dataset, although direct comments on its cleanliness or documentation are minimal which doesn't give us much information about its overall quality.

### License and Restrictions:

The dataset is licensed under the "Community Data License Agreement - Sharing - Version 1.0". This indicates that while the data can be shared, there may be certain conditions or requirements in regard to its usage, especially in commercial applications. Users must consult the license in detail to ensure compliance.

### Additional Dataset Insights:

* __Usage__: Judging by the data provided by Kaggle, the dataset has primarily been used for learning (10 instances), followed by research (4 instances) and application (2 instances). This could indicate its academic significance.

* __Activity Overview__: The dataset's activity metrics, which include a download-per-view ratio of 0.20 and a limited number of unique contributors (11), could indicate a focused interest but may also suggest that the dataset is either niche or relatively new on Kaggle.

* __Potential for Merging__: Given the dataset's thematic focus on life expectancy, it can be easily combined with other country-specific datasets, like the "Countries of the World" dataset mentioned earlier. Merging them would enable more in-depth analyses that incorporate GDP, population, area size, and life expectancy—all in one combined dataset.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Project Aim and Objectives

## Project Aim:

The aim of this project is to understand the relationships that GDP, an indicator of a country's economic health, shares with other indicators like death rate, birth rate, literacy rate, the prevalence of certain diseases, and a country's geographical characteristics (Coastline (coast/area ratio)). By combining these two comprehensive datasets we can capture a variety of socioeconomic indicators that countries across the globe share. This project seeks to provide a holistic perspective on how economic growth influences health indicators, and how geography and population dynamics play a part in this intricate interplay. The project will use correlation analyses in order to draw links between GDP and these factors, and will be aiming to answer questions such as: Does a higher GDP correlate with better health outcomes? How does the economy of coastal countries fare in comparison to landlocked ones? And how does population density influence a country's economic growth?

### Specific Objectives:

* __Objective 1__: Correlation Analysis between GDP and Key Indicators:

    * Merge the "countries of the world.csv" and "life_expectancy.csv" datasets.
    * Investigate the relationship between GDP and other indicators.
    * Employ visualizations to represent the correlation findings, ensuring they are easy to understand and interpret.

* __Objective 2__: Disease Prevalence:

    * Delve deep into the correlation between the cases of specific diseases, namely polio, diphtheria, HIV/AIDS, and hepatitis B, focusing on the years 2000-2015.
    * Employ visualizations to represent the correlation findings, ensuring they are easy to understand and interpret.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Architecture

The architecture of the project is linear. Datasets are being loaded into DataFrames via Pandas, a process of data aggregation takes place for the  life_expectancy dataset, the 2 datasets are then joined by 'Country', and lastly the visualization and data processing functions necessary for the analysis are declared, and then used.

<img src="diagram.png">

## System Design

My solution to this problem consists of several straightforward steps:

* Importing the necessary libraries: pandas, numpy, matplotlib, and seaborn
* Loading the datasets into 2 separate DataFrames
* Creating a function that aggregates the data from the life_expectancy.csv dataset by calculating the average values for the columns: Hepatitis B, Measles, Polio, Diphtheria, HIV/AIDS,
    BMI, Alcohol, Life expectancy, and GDP for each unique country in the dataset and creates a new dataset for this aggregated data.
* Merging the countries of the world.csv dataset with the aggregated dataset by removing rows with null values which are a result of the fact that some countries from the countries of the world.csv dataset are missing in the life_expectancy.csv dataset.
* Drawing a correlation graph for the new merged dataset in order to see possible correlations between different columns.
* Declaring functions that visualize analysis and correlations between different columns of the final dataset regarding GDP and diseases.
