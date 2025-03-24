# Effects of Urbanization on Deforestation over Time: DS4002 Data Divas Project 2
## Software and Platforms:
We used Python to run the majority of our code in Jupyter Notebooks in either Google Colab or locally using Anaconda Jupyter Lab. Platform varied by group member, so we used both Mac and Windows. In order to use Python in the most efficient manner, we used the following additional packages imported with this code: pandas, numpy, os, seaborn, matplotlib.pyplot, and .... 

## Documentation Map: <br>![Sitemap Whiteboard in Green Purple Basic Style-2](https://github.com/user-attachments/assets/bc7ac443-f61e-4a6a-9af7-930b2c11ef0c)


## How to Reproduce our Results:
* **Step 1: Data Collection** <br>
Download Environmental Performance Index data from the Yale Center for Environmental Law and Policy ([https://epi.yale.edu/downloads](url)). After accessing all of the data and perusing the technical appendix, save the appropriate datasets (PFL_raw_na.csv, IFL_raw_na.csv, and URB_raw_na.csv).
* **Step 2: Exploratory Data Analysis & Cleaning** <br>
Use SCRIPTS/cleaning_and_eda.ipynb to remove NA values and subset the data to the 50 countries that have all the PFL, IFL, and URB data. Use the same file to output line plots and scatter plots to gain a deeper understanding of the data that you are working with.
* **Step 3: Cross Correlational Analysis** <br>
Use SCRIPTS/real.cross.cor.analysis.&.forecasting.ipynb to calculate cross-correlation coefficients between urbanization rates and deforestation metrics (PFL, IFL), test for lag effects to determine whether urbanization precedes or lags behind forest loss, and compare time lags to assess whether urbanization has an immediate or delayed impact on deforestation.
* **Step 4: Forecasting Future Forest Loss With Exponential Smoothing** <br>
Use SCRIPTS/real.cross.cor.analysis.&.forecasting.ipynb to apply Holt’s linear trend method to forecast future values, compare model accuracy with R-squared values, and predict future deforestation rates.
* **Step 5: Conclusions** <br>
Summarize findings and assess the strength of the relationship between urbanization and deforestation.
Determine regions with the greatest changes in deforestation and regions at the greatest risk for future deforestation.
