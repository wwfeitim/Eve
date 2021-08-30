# Eve (Electric and fuel combustion vehicle Evaluation)
Car data collection, analysis and modelling

# 30/08/2021 
The first stage collecting raw data is done and updated. There are 76819 cars collected in the "data_collect_raw_08_30_2021.csv". 
The next stage is to clean the data. I made some mistakes during the scraping, and I want to write them here as a lesson. 
1. In the seller variables, there are approx. 50% data are wrongly repeated due to the coding issue. I found this issue until #47999 row. 
2. I did not classify the new and used cars, and most of the new cars do not record odometers whilst I applied the same approach of scraping these two categories.

# 30/08/2021 6pm
The data clean is commpleted
generated three data tables: for all, new and used cars.
