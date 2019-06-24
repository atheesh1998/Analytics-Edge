# Synopsis

## I: Nutrition Analysis
EDA on nutritional data extracted from the United States Departmetn of Agriculture database, which includes data complied from over 7000 individual food items.

1. Compiling profile report in pandas.
2. Summary statistics of the dataset.
3. Figuring skewed Sodium levels (in mg).
4. Creating separate dataframe for high sodium content foods.
5. Visualization of different permutations of dataframe columns.
6. Segregating rows based on their values compared with the mean value, and classifying as High or Low.
7. Converting the previous metadate to numeric values.

## II: Chicago Grand Theft Auto
There are two main types of crimes: violent crimes, and property crimes. Here, the focus is on one specific type of property crime, called grand theft auto. This is the act of stealing, or attempting to steal, a car. EDA is done on the dataset to understand the motor vehicle thefts in Chicago. 

1. Importing dataset and creating pandas Profile Report.
2. Parsing Date column to datetime format.
3. Extracting month and day for each observation and append as separate column.
4. Sorting crimes commited by year, month, and day (values_counts()).
5. Classify the above data by arrests.
6. Visualization of the occurence of GTA throough histogram and kernel density estiamation plot.
7. Using boxplot to determine the majority instance of arrests within the timeframe of the dataset.
8. Using crosstab to classify arrest value for each year.
9. Sorting location by occurences of GTA.
10. Separating top 5 locations to another dataframe; classified by arrest values.

## III: Stock Dynamics
EDA on stockdata of 5 blue chip companies in the US.

1. Importing dataset and creating pandas Profile Report.
2. Parsing Date column to datetime format.
3. Summary statistics
4. Plotting price action of the stocks superimposed over each other.
5. Extracting data of a certain timeframe from the entire timeframe.
6. Creating a function 'monthy_trends' to create a new column for month and return a dataframe with mean stockprice grouped by month.

