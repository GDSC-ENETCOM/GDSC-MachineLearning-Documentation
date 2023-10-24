# Introduction
In this second session, we will delve into the world of data visualization and the key libraries that empower us to transform raw data into insightful visual representations.
By the end of this session, participants will have a comprehensive understanding of the pivotal role data visualization plays in enhancing data exploration, analysis, and ultimately model performance. We will focus on essential Python libraries such as Pandas, Matplotlib, and Seaborn to achieve this goal.
Data Visualization: Unveiling the Power
Data visualization is the art and science of representing data graphically.
It is a crucial tool in the data scientist's arsenal, serving several critical purposes.

## 1. Enhancing Understanding
Data visualization helps us bridge the gap between raw, complex datasets and human comprehension. Through visual forms, we can represent data in a way that's intuitive and easier to grasp, making it more accessible to both technical and non-technical audiences. This visual translation aids in the identification of patterns, trends, and anomalies within the data.

## 2. Facilitating Data Exploration
One of the initial steps in any data analysis journey is to get an overview of the dataset. Visualization provides this essential insight. It allows us to quickly grasp the dataset's size, distribution, and structure. Moreover, it can highlight potential issues like missing values or outliers that require attention.

## 3. Feature Selection
Data visualization empowers us to identify the most relevant features for our model. By visually exploring the relationships between various features and the target variable, we can make informed decisions about which variables to include in our modeling process.

# Tools and Libraries
To make data visualization a reality in Python, we rely on a set of libraries that work seamlessly together. Here are the primary libraries we'll be using in this session:
![image](https://github.com/GDSC-ENETCOM/GDSC-MachineLearning-Documentation/assets/115191512/77f97416-a2b5-449c-a465-df99ed9736f3)

### 1. Pandas
Pandas is a powerful library for data manipulation and analysis. It provides data structures like DataFrames and Series, which are pivotal for data organization. Participants will learn how to leverage Pandas for data preparation and cleaning before visualization.

### 2. Matplotlib
Matplotlib is a versatile plotting library in Python. It allows us to create a wide array of static, animated, or interactive visualizations. We'll explore the basics of Matplotlib, including line plots, scatter plots, bar charts, and more, to visualize data effectively.

### 3. Seaborn
Seaborn is built on top of Matplotlib and provides a high-level interface for creating informative and attractive statistical graphics. It simplifies the creation of complex visualizations and is particularly useful when dealing with statistical data analysis.
 # General overview : 
 ### 1 - Data Computation With NumPy
Creating a NumPy Array
Selecting Data: Indexing and Slicing An Array
Performing Mathematical and other Basic Operations
Performing Basic Statistics
Manipulating Data
![image](https://github.com/GDSC-ENETCOM/GDSC-MachineLearning-Documentation/assets/115191512/8ef6b998-7ff2-4bad-85ed-7141163a94e6)
### 2 - Data Manipulation with Pandas
Basics of Pandas
Series and DataFrames
Data Indexing and Selection
Dealing with Missing data
Basic operations and Functions
Aggregation Methods
Groupby
Merging, Joining and Concatenate
Beyond Dataframes: Working with CSV, and Excel
Real World Exploratory Data Analysis (EDA)
![image](https://github.com/GDSC-ENETCOM/GDSC-MachineLearning-Documentation/assets/115191512/2d2eaffc-4095-4be9-9fa3-25ffd8ada244)
# Data Visualization :
### Data Visualizations with Matplotlib : 
To gain more insights or understand the problem you're solving, it is very important to visualize the dataset that you are working with.
Matplotlib is powerful visualization tool in Python. It can be used to create 2D and 3D figures. Seaborn that we will see later is built on Matplotlib.
This is what you will learn:
1. Basics of Matplotlib
2. Types of Plots
3. Image Plotting
4. Further Resources
### Data Visualization with Seaborn :
Seaborn is a fantastic and easy to use Python Visualization which is built on Matplotlib.
For a quick look, check out the gallery page.
To be covered:
1. Relational Plots:
Scatter plots
Line plots
2. Distribution Plots:
Plotting Histograms with displot() and histplot()
Plotting Bivariate Data with Jointplot()
Plotting Many Distribution with pairplot()
Plotting Distributions with rugplot()
Kernel Density Estimation (KDE) Plot with kdeplot() and displot()
Cumulative Distributions
3. Categorical Plots:
Categorical estimate plots
Categorical distribution plots
Categorical scatter plots
Plotting multiple categorical plots
4. Regression Plots
5. Multiplots:
Facet grids
Pair grids
Pair plots
6. Matrix Plots: Heat and Cluster Maps
Heat maps
Cluster maps
7. Style and Color
### Pandas for Data Visualization  :
Pandas that we used for data analysis and manipulation can also be used to visualize data.
And it is so simple. To step back a bit, Matplotlib is the primary visualization library in Python. Both Seaborn and Pandas visualization are built on top of Matplotlib.
Contents:<br>
1. Imports and loading datasets<br>
2. Basic Plots<br>
3. More Plots<br>
A. Bar plots<br>
B. Histogram<br>
C. Box plots<br>
D. Area plots<br>
E. Kernel Density Estimation (KDE) plots<br>
F. Scatter plots<br>
G. Hexagonal plots<br>
H. Pie plots<br>
4. Further learnings<br>
Styles and themes<br>
Colors<br>
# How choose visualization :
Choosing the right visualization for your data is crucial for effectively communicating your insights and making data-driven decisions. Here are some steps to help you decide which visualization is most suitable for your data:

Understand Your Data: Before selecting a visualization, you need a deep understanding of your data. Consider the type of data you have, whether it's categorical, numerical, time-series, or something else. Understand the relationships within the data, including trends, patterns, and outliers.

Define Your Objective: Clearly define the goal of your visualization. Are you trying to compare data, show trends over time, identify patterns, or display proportions? Your objective will guide your choice of visualization.

Select the Right Chart Type: Different data types and objectives call for specific chart types. Here are some common types of visualizations and when to use them:

Bar Chart: Use for comparing categories or showing discrete data.<br>
Line Chart: Ideal for displaying trends over time or ordered categories.<br>
Pie Chart: Use to show parts of a whole (proportions).<br>
Scatter Plot: Suitable for visualizing relationships between two numerical variables.<br>
Heatmap: Shows the intensity of relationships between two categorical variables.<br>
Histogram: Great for visualizing the distribution of a single numerical variable.<br>
for more details check this book : [ Resources/How-to-Choose.pdf](https://github.com/wissemkarous/Machine_Learning-Documentation-GDSC/blob/5faa0ff20e0b18427b93c050b82749977b0b1dc3/Resources/How-to-Choose.pdf)https://github.com/wissemkarous/Machine_Learning-Documentation-GDSC/blob/5faa0ff20e0b18427b93c050b82749977b0b1dc3/Resources/How-to-Choose.pdf
