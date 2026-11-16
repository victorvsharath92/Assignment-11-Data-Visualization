# Assignment-11-Data-Visualization
Python DA Assignment 2 - Data Visualization

Assignment Tasks Covered

1. Loading the Dataset
Load the taxis dataset into a Pandas DataFrame using sns.load_dataset("taxis").

2. Handling Missing Values
Inspect missing values across all columns (df.isnull().sum()).
Impute missing values for categorical columns (pickup_borough, dropoff_borough, pickup_zone, dropoff_zone, and payment) using their respective mode (most frequent value).
Drop remaining rows with un-imputable missing values using df = df.dropna().

3. Handling Missing Values
Inspect missing values across all columns (df.isnull().sum()).
Impute missing values for categorical columns (pickup_borough, dropoff_borough, pickup_zone, dropoff_zone, and payment) using their respective mode (most frequent value).
Drop remaining rows with un-imputable missing values using df = df.dropna().

4. Data Transformations & Visualizations (Matplotlib / Pandas Plot)
Datetime Conversion: Convert pickup and dropoff columns to datetime format using pd.to_datetime().
Line Chart: Plot fare over time using the pickup timestamp.
Bar Chart: Visualize total fare grouped by pickup_borough.
Pie Chart: Display trip distribution by payment method.
Histogram: Show the distribution of trip distances with customized bins.
Box Plot: Analyze the distribution of tip amounts across different pickup boroughs.

5. Advanced Visualizations (Seaborn)
Count Plot: Show the number of trips per pickup_borough.
Scatter Plot: Illustrate the relationship between distance and fare, hue-mapped by pickup_borough.
Heatmap: Display the correlation matrix for numeric columns (distance, fare, tip, tolls, total).
Pair Plot: Plot pairwise relationships across numeric metrics color-coded by pickup_borough.
Violin Plot: Visualize fare distribution for each payment method.
