1. Data Overview & Summary Statistics. I provided a table showing the count, mean, std, min, median (50%), and quartile ranges for Age, Fare, SibSp, and Parch.2. Numeric Feature Visualizations.
Histograms for Age and Fare.
Boxplots for Age and Fare.
3. Use pairplot/correlation matrix 4. Feature Relationships & Patterns".
A Correlation Matrix heatmap.
A Pairplot (coloring by Survived).
4. Identify patterns, trends, or anomalies
Screenshots:
1. categorical_count_plots.png
This image displays four separate bar charts, each showing the total count of passengers for a different categorical feature:
Survival Count: Shows the number of passengers who survived (1) versus those who did not (0).
Passenger Class Count: Shows the breakdown of passengers by class (1st, 2nd, and 3rd).
Gender Count: Shows the total number of male versus female passengers.
Port of Embarkation Count: Shows how many passengers boarded from each port (S, C, or Q).
2. histograms_age_fare.png
This image contains two histograms to show the distribution of numerical data:
Age Distribution: This plot shows the frequency of passengers across different age groups. It helps to see how many young, middle-aged, and elderly passengers were on board.  
Fare Distribution (Log Scale): This plot shows the frequency of different ticket prices. Because the fares are heavily skewed (most are cheap, a few are very expensive), a log scale is used to make the pattern more visible.
3. boxplots_age_fare.png
This image contains two boxplots, which are useful for identifying the median, spread, and outliers:
Age Boxplot: This plot visualizes the age range of the middle 50% of passengers (the "box") and highlights any individual passengers whose ages were statistical outliers.
Fare Boxplot: This plot clearly shows that the vast majority of fares were low (a compressed box), while also highlighting the many extreme outliers (passengers who paid a very high fare).
4. correlation_matrix.png
This image is a heatmap that visualizes the correlation coefficient (a value between -1 and +1) for every pair of numerical features.
Color: The color (e.g., from red to blue) indicates the strength and direction of the relationship.  
Numbers: The number in each square gives the precise correlation value.
Purpose: It helps you quickly identify which features are related (e.g., to see that Pclass and Fare are strongly negatively correlated).
5. pairplot_survived.png
This is a grid of smaller plots that compares each numerical feature against every other.
Scatterplots: The squares in the grid are scatterplots (e.g., Age vs. Fare).
Histograms: The plots on the diagonal show the distribution of a single feature.
Color (Hue): This is the most important part. The dots are colored based on Survived (e.g., red for 'Did not Survive', green for 'Survived'). This allows you to visually see how survival was impacted by combinations of factors (e.g., you can see that Fare (y-axis) vs. Pclass (x-axis) plot shows most survivors (green dots) are in the high-fare, 1st-class areas). identified the significant missing data in Cabin and Age as a major anomaly. I also noted the extreme outliers in the Fare column.
Patterns/Trends: identified clear trends, such as 3rd class having the most passengers, more males than females, and most passengers embarking from 'S'
5. Make basic feature-level inferences
From Statistics: Inferred that most passengers traveled alone (from SibSp and Parch medians).
From Visuals: Inferred the high survival rate for females (from the pairplot) and the negative correlation between Pclass and Survived (from the correlation matrix).