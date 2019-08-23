# nbaanalysis

I last worked on this project in Spring '19 with my team in one of our classes, Elements of Data Analytics. Since then, we haven't been able to run the jupyter notebooks because our access to Darwin SDK is no longer active. I'd like to recreate the models we made with other packages like scikit-learn in the future.
---
Group 3 - Ethan Fuerst, Pierce Kotarski, Austin Jiang, Shirel Miller

Can we predict playoff outcome from regular season data?

**Files in this repository:**

*nba_data.csv* - The raw dataset, we run three different models on this dataset

*2019_season.csv* - Regular season data from this year, we run this through each of the three models to see what our model predicts for this year

*data_clean&exp.ipynb* - This notebook contains more info about our thoughts behind the data cleaning and some interesting data exploration

*bball_norm.ipynb* - Has markdown cells explaining our though process through each point and normalizes data for each season before analyzing it. The other two notebooks have almost the same code, they just use different approaches with feeding the data in to Darwin. The markdown cells in this notebook apply to the other notebooks.

*bbal_std.ipynb* - Data is standardized for each season

*bball_out.ipynb* - This data has all the original columns from nba_data.csv. In the other two notebooks, some columns we thought were redundant have been removed.

*norm_2019.csv* - Data after it had been normalized by bball_norm.ipynb

*out_2019.csv* - Data used by bball_norm.ipynb

*std_2019.csv* - Data after it had been standardized by bbal_std.ipynb

All other files are various training and testing .csv files

*test.csv*

*test_norm.csv*

*test_out.csv*

*test_std.csv*

*train.csv*

*train_norm.csv*

*train_out.csv*

*train_std.csv*
