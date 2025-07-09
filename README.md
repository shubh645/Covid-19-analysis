# COVID-19 Data Analysis



## Overview

This project exploratory do the data analysis of COVID-19 statistics using publicly available datasets. The analysis involves loading, cleaning, and summarizing key metrics related to the pandemic.



## Data Sources

The analysis of this project utilizes data from two primary sources:

* `covid_19_india.csv`: Contains daily case information including confirmed cases, Cured, Deaths, Sno, Date, Time, and State/UnionTerritory.

* `StatewiseTestingDetails.csv`: Provides state-wise testing details, including Date, State, TotalSamples, Negative, and Positive results.



## Libraries Used

The following Python libraries are used for this project:

* `pandas`: Used for data manipulation and analysis.

* `numpy`: Employed for numerical operations.

* `matplotlib.pyplot`: Utilized for data visualization.



## Analysis Highlights

The project performs several key analytical steps:

* **Data Loading and Inspection**: Reads the COVID-19 India and State-wise Testing Details datasets into pandas DataFrames. Initial data inspection is performed using `head()` and `info()` to understand the structure and data types.

* **Data Cleaning**: Handles missing values, specifically converting the 'Negative' column to a numeric type and dropping rows with `NaN` values to ensure data integrity for analysis.

* **Descriptive Statistics**: Generates descriptive analyses of the cleaned testing data, providing insights into various statistical measures like count, mean, standard deviation, etc., for numerical columns.

* **Data Transformation**: Transposes a portion of the cleaned data for alternative viewing or further analysis.



## Usage

To run the source code of this, ensure you have Jupyter Notebook installed along with the specified Python libraries. Place the `covid_19_india.csv` and `StatewiseTestingDetails.csv` files in the appropriate directory as referenced in the notebook of this project, or update the file paths accordingly.
