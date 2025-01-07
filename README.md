# Food_Data_Analysis


This project analyzes a dataset of Indian dishes, exploring relationships between various culinary attributes.  The analysis uses Python libraries like Pandas, Seaborn, and Matplotlib to visualize data and gain insights.

**Exploratory Data Analysis (EDA) and Visualizations:**

This project analyzes a dataset of Indian dishes, exploring various culinary aspects through data visualization.  The goal is to uncover insights into the relationships between different food characteristics, such as preparation time, cooking time, region of origin, dietary restrictions (vegetarian/non-vegetarian), and flavor profiles.

**Data Cleaning and Preprocessing:**

*   The project begins by handling missing values in the dataset, specifically for image URLs and regions, filling them with appropriate defaults.
*   Inconsistent values in categorical columns like 'state' and 'course' are identified and corrected using available information from the dataset.
*   Outliers in 'prep_time' and 'cook_time' are addressed using the Winsorizing method.

**Insights Gained from Visualizations:**

The visualizations provide a comprehensive overview of the dataset, allowing users to identify trends, patterns, and potential relationships between different features, leading to a better understanding of Indian cuisine's diversity and regional variations.

The visualizations provide several key insights:

* **Distribution Analysis:** Histograms reveal the frequency distribution of preparation and cooking times, providing an understanding of the typical time investment needed for preparing various dishes.
* **Regional Variations:** Box plots illustrate how preparation and cooking times differ across different regions of India, highlighting potential regional culinary practices.  Bar plots show the number of dishes per region and the distribution of vegetarian and non-vegetarian options within each region.
* **Dietary Preferences:**  Bar charts and pie charts visualize the distribution of vegetarian and non-vegetarian dishes overall and within regions, revealing potential regional dietary preferences.
* **Relationships between Variables:** Scatter plots examine the relationship between preparation time and cooking time, offering insights into whether there's a correlation between these two factors. Heatmaps display the relationship between regions and cooking or preparation times in a concise manner.
* **Data Cleaning and Preprocessing:** The project demonstrates how to handle missing values (NaNs and -1s) in the data and how to apply outlier treatment using the Winsorize method. This step is crucial for generating reliable visualizations and insights.


This analysis allows for a deeper exploration into the rich tapestry of Indian food, using the data to uncover and understand the relationship between regional differences and cooking practices.
