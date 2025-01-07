# Food_Data_Analysis


This project analyzes a dataset of Indian dishes, exploring relationships between various culinary attributes.  The analysis uses Python libraries like Pandas, Seaborn, and Matplotlib to visualize data and gain insights.

**Data Cleaning and Preprocessing:**

*   The project begins by handling missing values in the dataset, specifically for image URLs and regions, filling them with appropriate defaults.
*   Inconsistent values in categorical columns like 'state' and 'course' are identified and corrected using available information from the dataset.
*   Outliers in 'prep_time' and 'cook_time' are addressed using the Winsorizing method.

**Exploratory Data Analysis (EDA) and Visualizations:**

The visualizations provide several key insights:

*   **Distribution of Preparation and Cooking Times:** Histograms reveal the typical preparation and cooking times, helping understand the time commitment involved in preparing different dishes.
*   **Regional Variations:** Box plots compare the preparation and cooking times across different regions of India, highlighting potential differences in cooking styles. Scatter plots provide a deeper dive into the joint distribution of preparation and cooking times.
*   **Dietary Preferences:** The analysis reveals the proportion of vegetarian and non-vegetarian dishes, and through stacked bar charts, the distribution of these categories within each region. Pie charts provide a clear summary of the overall dietary distribution and regional distribution of dishes.
*   **Number of Dishes per Region:**  Bar charts show the variety of dishes available in each region.
*   **State-wise Distribution:** Bar chart illustrating the number of dishes from each Indian state.
*   **Heatmaps:** Heatmaps visualize the relationships between regions and cooking times and preparation times, revealing potential correlations between these variables.

**Insights from Visualizations:**

The visualizations generated during this analysis can inform several conclusions related to Indian cuisine:

*   **Regional Culinary Differences:**  The box plots and heatmaps illustrate regional differences in average preparation and cooking time, suggesting variations in ingredients, techniques, and traditional recipes across India. The regional distributions of dishes and diets also highlight regional trends.
*   **Dietary Habits:** The analysis indicates a proportion of vegetarian to non-vegetarian dishes, with the stacked bar charts revealing which regions have a higher concentration of each type of food.
*   **Time Considerations:** The distributions of preparation and cooking times help in understanding how long it typically takes to prepare different types of dishes.
*   **Dish Variety:**  The bar charts illustrate the number of dishes offered from different regions, giving an overview of the diversity of cuisine.

This analysis allows for a deeper exploration into the rich tapestry of Indian food, using the data to uncover and understand the relationship between regional differences and cooking practices.
