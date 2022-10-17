# Making-Matplotlib-Magic-and-the-Midterm-Project

For the Midterm project, each team will use the five CSV files located in the Resources folder to complete the analysis. Each team will get started by using the provided Midterm_project_starter_code.ipynb file in the Midterm project resources download link. Feel free to copy this file to work through the three requirements and your additional analyses.

As a team, complete the following steps:

Create a Jupyter Notebook describing the data exploration and cleanup process for the three requirements and two additional analyses.

Complete all three requirements in the starter code to perform a high-level analysis.

For Requirement 1, you'll create a DataFrame that displays the total number of alternative fuel stations grouped by "State" and "Fuel Type" by doing the following:

Read in each CSV as a DataFrame and rename columns as follows:

"85% Ethanol": "85E"
"Compressed Natural Gas": "CNG"
"Liquified Natural Gas": "LNG"
"Liquified Petroleum Gas": "Propane"
"Biodiesel", "Electric", and "Hydrogen" do not need to be renamed.
Next, for each original DataFrame apply the melt function to create new DataFrames, and rename the columns using id_vars="State", var_name="Fuel Type", and the "year" for the value_name parameter.

For each new DataFrame created using the melt function, retrieve the total number of alternative fuel stations grouped by the "State" and "Fuel Type."

Finally, merge all five DataFrames to create a DataFrame as the following image shows:

An image that shows a DataFrame of with the total number of alternative fuel stations grouped by State and Fuel Type.

For Requirement 2, you'll create a bar chart that shows the total number of alternative fuel stations for each year by doing the following:

Create a list that holds the total number of alternate fuel stations for each year from the merged DataFrame from Requirement 1.

Create a list that holds the years from the merged DataFrame from Requirement 1.

Finally, create a bar chart that shows the total number of alternative fuel stations for each year, and add x- and y-axes labels and a title as the following image shows:

An image shows a bar graph that depicts the total number of alternative fuel stations for each year

For Requirement 3, you'll create a table that shows the alternative fuel types sorted from the greatest to least number of alternative fuel stations for each year by doing the following:

Get the total number of each alternative fuel type by grouping each melted DataFrame from Requirement 1 on "Fuel Type", and resetting the index.

Merge all five grouped DataFrames on "Fuel Type."

Sort the merged DataFrame on the year columns in descending order to create a DataFrame as the following image shows:

An image that shows a DataFrame sorted from greatest to least number of alternative fuel stations for each year.

After completing all three requirements, each team must perform two additional analyses that produce two visualizations, i.e., one visualization per question asked about your data.

NOTE
Due to the time constraints for teams to work on this project, no additional datasets are allowed.

Create a Jupyter Notebook illustrating the final data analysis.

The repository README must contain a summary that supports the major findings. The summary should include a heading for the high-level analysis and one for each "question" you asked of your data, and a short description of your findings with any relevant plots or tables.

Each student will prepare and record a 2-minute summary video presentation of their team's midterm project that will be submitted with their analysis.

© 2020 - 2022 Trilogy Educati
