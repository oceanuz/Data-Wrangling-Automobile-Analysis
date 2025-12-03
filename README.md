#  [Data-Wrangling-Automobile-Analysis] - Data Wrangling on Automobile Price Data

This repository contains a practical study conducted under the [Institution Name, e.g., IBM Data Science Professional Certificate]. Its goal is to address common quality issues in raw datasets and prepare the data for modeling (machine learning).

##  Main Purpose and Applied Techniques

In this Jupyter Notebook file (practice_data_wrangling.jupyterlite.ipynb), the following basic data wrangling techniques were applied to an automobile dataset:

1. **Missing Data Management:** Identifying NaN or missing values ​​and filling or deleting them with the mean.
2. **Data Type Correction:** Converting columns that should be numeric (e.g., Price, RPM) to the correct data type (float/int).
3. **Data Standardization:** Bringing data into a consistent format (e.g., converting from L/100km to US MPG).
4. **Data Normalization:** Scaling numerical values ​​(e.g., length, width) in different ranges to the 0-1 range (Min-Max method).
5. **Binning:** Separating continuous numerical data (e.g., Horsepower) into categorical groups.
6. **Creating Dummy Variables:** Converting categorical text data into numeric format for machine learning models.

##  Technologies Used

* **Language:** Python
* **Libraries:** Pandas, NumPy
* **Environment:** Jupyter Notebook (JupyterLite)

##  How to Run

1. Clone the repository: `git clone [Repository URL]`
2. Install the required libraries: `pip install pandas numpy`
3. Open the `practice_data_wrangling.jupyterlite.ipynb` file in Jupyter Lab or Visual Studio Code and run the cells one by one.
