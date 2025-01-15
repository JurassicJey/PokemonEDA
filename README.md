# Pokemon Data Analysis

This project analyzes a dataset of Pokemon, exploring various attributes and statistics. The analysis includes visualizations and statistical evaluations to uncover patterns and insights within the Pokemon data.

## Dataset

The dataset used in this analysis is `pokedex_(Update_05.20).csv`, which contains information about various Pokemon, including their types, stats, abilities, and more.

## Data Preprocessing

-   **Data Cleaning**: Removed entries for Mega Evolutions, G-Max forms, and Alolan forms to focus on base Pokemon forms.
-   **Handling Missing Values**: Checked for missing values and found some, will be dealt with in future iterations.

## Exploratory Data Analysis (EDA)

### Distribution of Pokemon Types

-   Analyzed the distribution of Pokemon types using a bar chart, revealing the frequency of each type.

### Pokemon Stat Analysis

-   **Histograms and Outlier Detection**:
    -   Generated histograms for each base stat (HP, Attack, Defense, Special Attack, Special Defense, Speed).
    -   Identified and listed outliers for each stat using the Interquartile Range (IQR) method.

### Type and Generation Analysis

-   **Type Distribution**: Visualized the distribution of primary and secondary types and the count of Pokemon per generation.
-   **Flying Type Analysis**: Investigated the number of Flying-type Pokemon across different generations.

### Correlation Analysis

-   **Scatter Plots**: Created scatter plots to visualize the relationships between different pairs of stats.
-   **Correlation Heatmap**: Generated a heatmap to visualize the correlation coefficients between numerical features, highlighting correlations greater than or equal to 0.7.

### Other Analyses

-   **Type Combination Frequency**: Analyzed the most frequent combinations of primary and secondary types.
-   **Total Points Analysis**:
    -   Created a box plot to compare the distribution of total points across different Pokemon statuses (e.g., Legendary, Mythical).
    -   Plotted the average total points per generation.
-   **Height and Weight Analysis**:
    -   Used joint plots to visualize the relationship between height/weight and total points, with outlier removal based on IQR.
    -   Created a 3D scatter plot to visualize the relationship between weight, height, and total points, with outliers removed.

## Visualizations

-   Bar charts for Pokemon type counts, generation counts, and average total points per generation.
-   Histograms for base stats.
-   Scatter plots for stat relationships.
-   Correlation heatmap.
-   Box plot for total points by status.
-   Joint plots for height/weight vs. total points.
-   3D scatter plot for weight, height, and total points.

## Dependencies

-   pandas
-   numpy
-   matplotlib
-   seaborn
-   mpl\_toolkits.mplot3d

## Running the Code

To run the analysis, execute the Python script provided in the repository. The script will generate the visualizations and print the outlier analysis results.

## Conclusion

This analysis provides insights into the distribution of Pokemon types, stats, and their relationships. The visualizations and statistical evaluations offer a comprehensive overview of the Pokemon dataset, revealing interesting patterns and potential areas for further investigation.
