# FIFA-Player-Value-Predictor
This project analyzes data from FIFA 2019 to predict player wages and salaries. The code is written in Python and uses the pandas and seaborn libraries for data manipulation and visualization.

## Getting Started
To run the code, you will need to have Python and the pandas and seaborn libraries installed. You will also need to download the **`data.csv`** file, which contains the player data.

## Data Exploration
The code begins by reading in the **`data.csv`** file and displaying the shape of the data frame, which is (18207, 89). It then uses the **`describe()`** method to display summary statistics for the data.

The code also creates a new data frame **`df1`** containing only the columns 'Name', 'Wage', and 'Value'. It then defines a function **`value_to_float()`** to convert the wage and value columns to floats, and applies this function to create new columns 'Wage' and 'Value' with the converted values. Finally, it creates a new column 'difference' representing the difference between the player's value and wage, and sorts the data frame by this column in descending order.


## Data Visualization
The code uses the seaborn library to create a scatter plot of player wages versus player values. The plot shows a positive correlation between the two variables, with higher-value players generally having higher wages.

## Conclusion
This project uses data analysis and machine learning techniques to predict player wages and salaries in FIFA 2019. The code reads in the **`data.csv`** file and preprocesses the data to create a new data frame containing only the relevant columns. It then uses machine learning algorithms to build a predictive model based on the data.

The code also uses the seaborn library to create visualizations that help to explore the relationships between different variables in the data. The scatter plot of player wages versus player values shows a positive correlation between the two variables, with higher-value players generally having higher wages.




