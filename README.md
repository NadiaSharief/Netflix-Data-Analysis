# Netflix-Data-Analysis

## Background Information:

we use Python Pandas & Python Matplotlib to analyze and answer business questions about Netflix data. The data contains thousands of entries about Show_Id,Category	Title	Director,Cast,Country,Release_Date,Rating,Duration,Type and Description

We start by cleaning our data. Tasks during this section include:

- Deleted duplicated rows using .duplicated() and .drop_duplicates()
-Identify the null records using .isnull()
-Represented null values through a heat map using sns.heatmap(data.isnull())
-Selected data for a specific attribute or attributes
-Converted object data type to new date time column using pd.to_datetime()
-Counted the number of occurences per year using .dt.year.value_counts()
-Plotted a bar graph to show the year and number of occurences of tv shows and movies
-Grouped data using .category.count()
-Filtered all those records in resepct to certain conditions
-Counted records based on condition using .value_counts()
-Performed analysis using Logical operators like | (OR) , & (AND)
-Filtered data to remove all null values using .dropna() and used .str.contains() to select data
-Used .unique() to filter the unique data
-Splitted the column into two columns from the given column using .str.split()
-Checked the data types of columns using .dtypes
-Sorted columns using .sort_values()
-Plotted area,bar,line charts using Matplotlib library 
