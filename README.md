# Food_Data_Analysis

This project performs exploratory data analysis (EDA) on a dataset of Indian dishes, aiming to uncover insights into regional culinary variations, dietary preferences, and preparation times.  The analysis involves data cleaning, handling missing values, and visualizing key features.

Key aspects of the project include:

* **Data Cleaning and Preprocessing:** Addresses missing values in crucial columns like `img_url`, `region`, and `state`, employing imputation techniques to ensure data completeness.  Inconsistent or erroneous values in categorical columns (e.g., `course`, `flavor_profile`, `state`) are corrected.  Outliers in `prep_time` and `cook_time` are handled using the Winsorizing method.
* **Exploratory Data Analysis:** Utilizes various visualization techniques, including histograms, box plots, bar charts, scatter plots, pie charts, and heatmaps, to reveal patterns and relationships within the data.  Key explorations focus on:
    * Distribution of preparation and cooking times.
    * Regional variations in dish characteristics (e.g., number of dishes, preparation times).
    * Dietary preferences across regions.
    * Relationships between preparation and cooking times.
* **Key Visualizations:** The project provides informative visualizations summarizing the data's key characteristics. These visualizations are designed to quickly communicate insights about the dataset.

The repository contains the Python code used for the analysis, including data loading, cleaning, and plotting, allowing for reproducibility of the findings.  The project provides a valuable overview of Indian cuisine's diversity and characteristics based on the provided dataset.
