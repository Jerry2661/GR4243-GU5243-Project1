GR4243/GU5243 Project 1  


The project follows task: 1. Data acquisition
                          2. Data cleaning and handling inconsistencies 
                          3. Exploratory data analysis (EDA)
                          4. Data preprocessing and feature engineering


Data Sources: 1. NYC Taxi Trip Data: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page  
              2. Historical Weather Data: https://www.ncdc.noaa.gov/cdo-web/  


Dataset Download Instructions(Due to GitHub file size limitations, raw and processed datasets are hosted on Google Drive. Please download the following files before running the notebook):
- https://drive.google.com/file/d/1k9BHQWIgCYYTR9UsBLSXVSG2ORz5mP8a/view?usp=drive_link  
- https://drive.google.com/file/d/17lRIsWyX3G4Oy5HJWkNyFfTi3G7mu5_E/view?usp=drive_link  
- https://drive.google.com/file/d/1xPIyJ5vaCEoctoqetcAS2h4YdJYvtKCh/view?usp=drive_link  
- https://drive.google.com/file/d/1PcijEa6s6m9keZvNoIFTEHvYQjiKL-4v/view?usp=drive_link  
- https://drive.google.com/file/d/11NFI_unaV5L_lQZVo6KOpEhs26whRBp9/view?usp=drive_link  
- https://drive.google.com/file/d/1ZdeeNQSTzFUjouMrX937nT-CKNi_pAID/view?usp=drive_link  
- https://drive.google.com/file/d/1b5iFVs_GpQHNC_ztxKUgEuSADpWAzrVh/view?usp=drive_link  
- https://drive.google.com/file/d/15LoCwT4g75i83ldc2ZxXghRIohgRY_oH/view?usp=drive_link  


Data Acquisition: 1. Taxi trip records were downloaded in Parquet format.
                  2. Weather data was retrieved from NOAA databases.
                  3. Multiple datasets were merged using date-based joins.


Data Cleaning： 1. Converted datetime columns into proper formats 
                2. Handled missing values through removal
                3. Removed unrealistic trip distances and fare values
                4. Addressed outliers using logical thresholds


Exploratory Data Analysis (EDA): 1. Distribution of trip distances and fare amounts
                                 2. Weather variable distributions
                                 3. Time-series visualization of taxi demand vs weather changes


Data Preprocessing: 1. Normalization of numerical variables
                    2. Encoding categorical features
                    3. Creation of time-based features


Feature Engineering: 1. Daily ride demand
                     2. Temperature deviation indicator
                     3. Rain-day binary variable
                     4. Weather severity index


GR4243-GU5243-Project1/
│
├── nyc_taxi_weather_analysis_UPDATED.ipynb
├── README.md


How to run: 1. pip install pandas numpy matplotlib seaborn pyarrow
            2. jupyter notebook nyc_taxi_weather_analysis_UPDATED.ipynb
