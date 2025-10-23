# social-dashboard

This dashboard provides a multi-faceted visualization of aggregated demographic and physical data, likely for an HR or personal records dataset. It was created using Python.

Business Purpose
The primary business purpose of this dashboard is to offer quick and clear insights into key summary statistics and relationships within the dataset. It enables stakeholders to:

Assess overall distribution: Quickly identify the total Age contribution per person and the correlation between Age and Weight.

Compare individuals: Analyze differences in the Sum of Children and Sum of Pets across individuals.

Gender and attribute analysis: Compare total Weight across individuals, segmented by Gender.

Inform decision-making: Provide the groundwork for deeper analysis related to health, family status, or resource allocation based on these variables.

Dashboard Description
The dashboard is composed of three distinct visualizations, each addressing a different aspect of the data.

1. Bar Chart: Sum of Age Distribution 📊
Title/Metrics: "Sum of Age, Sum of Children, Fname, Gender, Sum of Pets, State and Sum of Weight" (This is likely the list of fields available, and the chart specifically shows the Sum of Age).

Description: This bar chart displays the Sum of Age for each individual (Fname), allowing for a straightforward comparison of total age contribution across the group. Mike has the highest aggregate age, followed by Sally and Tom.

2. Line Chart: Children and Pets Trends 🐾
Title/Metrics: "Sum of Age, Sum of Children, Fname, Gender, Sum of Pets, State and Sum of Weight"

Description: This dual-axis line chart (or a single chart with two series) plots the Sum of Children (blue line) and the Sum of Pets (red line) against individuals (Fname). It allows for an easy visual comparison of family size and pet ownership trends or differences among the individuals. For example, Tom has the highest number of Pets, and Abe has the highest number of Children.

3. Scatter Plot: Age vs. Weight Correlation ⚖️
Title/Metrics: "Sum of Age, Sum of Children, Fname, Gender, Sum of Pets, State and Sum of Weight"

Description: This scatter plot shows the relationship between Age (on the x-axis) and Weight (on the y-axis). Each point represents an individual's data. Visually, it suggests a loose positive correlation or perhaps no strong correlation, as the points are widely distributed, though there's an outlier at a very high age (around 80) with a relatively low weight.

4. Categorical Scatter Plot: Weight by Fname and Gender 👤
Title/Metrics: "Sum of Weight by Age, Fname and Gender"

Description: This chart is a specific type of categorical scatter plot or a stripplot/dot plot that displays the Sum of Weight, segmented first by Gender (F and M) on the x-axis, and then further broken down by Fname (Abe, Harry, June, Mike). It provides a granular view of how individual weights are distributed and compares total weight across genders.

Charts Used
The dashboard utilizes the following chart types:

Bar Chart

Line Chart (with two series)

Scatter Plot

Categorical Scatter Plot
screenshot

