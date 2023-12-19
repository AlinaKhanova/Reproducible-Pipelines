# Reproducible-Pipelines

## Project overview.

This project analyzes the U.S. Inflation Rate by Year from 1929 to 2023. The data is sourced from Investopedia, with a series code of "inflation-rate-by-year-7253832". The data was accessed on Oct. 10, 2023, and it provides a yearly inflation rate.

## Instructions on how to run the pipeline.

1. Clone the GitHub repository: git clone [https://github.com/your_username/your_project.git](https://github.com/AlinaKhanova/Reproducible-Pipelines.git)
2. Navigate to the project directory: cd Reproducible-Pipelines
3. Install dependencies: pip install -r requirements.txt
4. Run the pipeline: bash run_pipeline.sh
   
## Dependencies and installation instructions.

* Dependencies are listed in the requirements.txt file.
* To install dependencies, run: pip install -r requirements.txt

## Brief explanation of the data source and its structure.

* The dataset is stored in the 'data' directory as 'data_khanova.xlsx'.
* The data cleaning process involves visual inspection for outliers and breaks. Extreme values (e.g., 1940-1946, 1974, 1979, 2021) are considered outliers or related to specific events (e.g., post-war recovery or the COVID crisis). The analysis focuses on data from the 1952nd year onward, excluding the post-COVID surge in inflation.
* A time series plot is created for visual inspection.
  
## Code organization and structure.

* The main analysis code is in HWII_script_Khanova.
* Results, plots, and diagnostic tests are documented at each step.
