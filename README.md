# Eve (Electric and fuel combustion vehicle Evaluation)
Car data collection, analysis and modelling

# 30/08/2021 
The first stage collecting raw data is done and updated. There are 76819 cars collected in the "data_collect_raw_08_30_2021.csv". 
The next stage is to clean the data. I made some mistakes during the scraping, and I want to write them here as a lesson. 
1. In the seller variables, there are approx. 50% data are wrongly repeated due to the coding issue. I found this issue until #47999 row. 
2. I did not classify the new and used cars, and most of the new cars do not record odometers whilst I applied the same approach of scraping these two categories.

# 30/08/2021 9pm
The data clean is commpleted  
generated three data tables: for all, new and used cars.  
Data generated in this project is for study purpose only.  

# 31/08/2021 11am
The models were properly separated from title variable, ready to analyse.

# 31/08/2021 2pm
The overview of data is completed, I will soon upload to my blog. 

# 01/09/2021 10pm
Start the analysis of model and body types in six selected brand. Some interest patterns found.  
Cross checked the data and did some minor changes.  

# 02/09/2021 5:30 pm
Completed the new post: Models and Body Types Analysis in Australia car market

# 07/09/2021 7:40pm
Electric car data collected including 858 electri cars on sale.

# 08/09/2021 4:47pm
Electric car data clean completed, ready to analysis.  
The output csv file is : "df_EV_clean.csv"

# 10/09/2021 6:00P,
The overview of electric car analysis is completed.  
I will have to spend few days to be familiar with Shiny Package. I want to embed a calculator app into the blog to measure how much can be saved in 5/10/15 years if people switch from fuel combustion cars to pure electric cars, which is also a answer I want to find.  
In order to make the measurement accurate, I might take longer time to consider what variables is necessary. I plan to complete this calculator before October.

# 11/10/2021 2:30pm
After tests of linear & IV regression models for regressors, I find the depreciation rates for gasoline and electric cars. The rates explains the relationship between price/value and odometers. The tasks left are:
- fuel cost prediction. I need to investigate the fuel price trend from 2010 to 2021.
- electric consumption. I can find it information on carsales and manufactory information. This is extremely important for EV as well as fuel consumption for gasoline cars.
- electricity cost. This one is likely to be optional for consumers. I will need to find a default value for Shiny app. 

# 12/10/2021 5:45pm
The Shiny app is completed over 65%. Sidebar, mainpanel and depreciation of car value (table and plot) are completed. 
The rest of tasks are:
- Description of output
- prediction of future cost
- plot improvement