# Principles of Data Analytics 

Course project for Principles of Data Analytics - Higher Diploma in Science in Computing in Data Analytics. 

## About this repository

### The project 

This project was started in February 2025 as part of the course *Principles of Data Analytics*. 
It includes sourcing and manipulating the Iris dataset from the [UCI Machine Learning repository](https://archive.ics.uci.edu/dataset/53/iris). 

The dataset is explored and manipulated to extract meaningful data and represent them grafically through plots and charts. 

### Packages and Libraries  

**Getting started**

Pyhton: This projects was developed using Python 3.12 inside Jupyter Notebooks. It can be run in a virtual environment, or locally with Anaconda (Jupiter Notebooks). 

**Libraries** 

In the notebook, a number of external libraries are used: these libraries are listed in the file requirements.txt. 
If the notebook is run locally and not in an virtual enviroment/Anaconda, these libraries need to be installed. 
- To install all the required libraries at once, run the command 'pip install -r requirements.txt' in your terminal. 
- To install the libraries individually, run the code 'pip install *module name*'.

## Tasks 

All the tasks are included in the Notebook [tasks.ipynb](/workspaces/principles_of_data_analytics/tasks.ipynb) in this repository. 

### Task 1: Source the dataset 
Loading the dataset and introducing it.
### Task 2: Explore the data structure
Exploring the dataset features, targets (classes) and other information through scikit-learn and pandas.
### Task 3: Summarize the data 
Using NumPy to calculate Minimum, Maximum, Mean, Meadian and Standard deviation for each feature. 
### Task 4: Visualize features
Plotting histograms for each feature and highlight trends. 

Extra: plotting all histograms togther to compare features, and plotting boxplots for each feature to observe feature variation. 
### Task 5: Investigate relationships 
Plotting a scatter plot to investigate the correlation between two features: Petal length and Petal width. Each class is represented with a different color, to highlight class-specific trends. 
### Task 6: Analyze relationships 
Fitting a line in the data to highlight the correlation between Petal length and Petal width. Using numpy.polyfit to calculate the values of slope and intercept of the ideal line, and calculate simple linear regression. 
### Task 7: Analyze class distribution 
Plotting boxplots to represent Petal length in each class of the dataset. 
### Task 8: Compute correlations 
Calculating Pearson's Correlation Coefficient for each feature pair and plotting the data in a heatmap to highlight wether features have a positive or negative correlation. 
### Task 9: Fit a simple linear regression 
Using SciPy to calculate the coefficient of Determination between Petal length and Petal width, in addition to slope and intercept values. Fitting a line on the scatter plot based on these values. 
### Task 10: Too many features
Plotting a pairplot with Seaborn to represent the correlation that each feature has with the other features, highlighting class distribution. Drawing some conclusions on the dataset. 



## References

#### Libraries: 

[Sklearn](https://scikit-learn.org/stable/) to source the dataset 

[Numpy](https://numpy.org/doc/stable/index.html) to make calculations on the data 

[Pandas](https://pandas.pydata.org/docs/getting_started/index.html) to load the data in tabular format 

[SciPy](https://docs.scipy.org/doc/scipy/index.html) to calculate linear regression 

[Matplotlib](https://matplotlib.org/) to plot the data

[Seaborn](https://seaborn.pydata.org/index.html) to plot the data 
#### Task 1: 

[UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/53/iris) View the dataset and its characteristics.

#### Task 2: 

[load_iris](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html) Load_iris() package by scikit learn. 

[gist.github.com/curran](https://gist.github.com/curran/a08a1080b88344b0c8a7) Iris dataset in tabular format.

[numpy review](https://ds100.org/fa17/assets/notebooks/numpy/Numpy_Review.html) Numpy arrays. 

#### Task 3:

[numpy.mean](https://numpy.org/doc/stable/reference/generated/numpy.mean.html) Calculate mean value in an array. 

[numpy.min](https://numpy.org/doc/stable/reference/generated/numpy.max.html) Calculate minimum value in an array. 

[numpy.min](https://numpy.org/doc/stable/reference/generated/numpy.min.html) Calculate maximum value in an array.

[numpy.std](https://numpy.org/doc/stable/reference/generated/numpy.std.html) Calculate standard deviation in an array.

[numpy.median](https://numpy.org/doc/stable/reference/generated/numpy.median.html) Calculate median in an array. 

[Mean, Wikipedia](https://ds100.org/fa17/assets/notebooks/numpy/Numpy_Review.html) Definition of mean. 

[Maximum and Minimum, Wikipedia](https://en.wikipedia.org/wiki/Maximum_and_minimum) Definition of minimum and maximum value.

[How to Calculate Standard Deviation (Guide) | Calculator & Examples](https://www.scribbr.com/statistics/standard-deviation/#:~:text=The%20standard%20deviation%20is%20the,clustered%20close%20to%20the%20mean.) Definition of Standard deviation.

[Median in Statistics](https://www.geeksforgeeks.org/median/) Definition of mediam. 

#### Task 4: 

[Pyplot vs Object Oriented Interface](https://matplotlib.org/matplotblog/posts/pyplot-vs-object-oriented-interface/). Difference between stateless and stateful approach in Matplotlib. 

[matplotlib.pyplot.hist]( https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.hist.html) Official documentation in Matplotlib. 

[List of named colors](https://matplotlib.org/stable/gallery/color/named_colors.html) Colors in Matplotlib, official documentation.

[What Is a Boxplot?](https://builtin.com/data-science/boxplot#:~:text=A%20boxplot%20is%20a%20graph,in%20comparison%20to%20the%20IQR). Boxplots. 

[matplotlib.axes.Axes.boxplot](https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.boxplot.html) Boxplots, officiala documentation. 

[Change the colors of outline and median lines of boxplot in matplotlib](https://stackoverflow.com/questions/57668399/change-the-colors-of-outline-and-median-lines-of-boxplot-in-matplotlib) Personalise boxplot colors. 

[Box plots with custom fill colors](https://matplotlib.org/stable/gallery/statistics/boxplot_color.html#sphx-glr-gallery-statistics-boxplot-color-py) Personalise boxplot colors. 

[matplotlib.axes.Axes.set_xticks](https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.set_xticks.html#matplotlib.axes.Axes.set_xticks) Personalise boxplot ticks. 

#### Task 5: 

[Matplotlib essentials](https://medium.com/@The_Gambitier/matplotlib-essentials-e376ed954201) Staless vs Stateful approach on Matplotlib. 

[matplotlib.pyplot.scatter](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.scatter.html) Scatteplots, official documentation of Matplotlib. 

[Making a Python Scatter Plot with Different Colors for Different Labels](https://jamesmccaffrey.wordpress.com/2020/10/22/making-a-python-scatter-plot-with-different-colors-for-different-labels/) Personalise colors and legend in scatterplots.

[matplotlib.markers](https://matplotlib.org/stable/api/markers_api.html#module-matplotlib.markers) Personalise markers

[OpenAI chatGPT](https://chatgpt.com/share/67f2c42b-a108-800f-9b47-c15d529b5264) Assign labels according to class color. 

#### Task 6: 

[Simple Linear regression, Wikipedia](https://en.wikipedia.org/wiki/Simple_linear_regression) Definition of Simple Linear Regression.  

[Slope and Intercept, W3School](https://www.w3schools.com/datascience/ds_linear_slope.asp) Definition of slope and intercept. 

[Slope and intercept of the regression line, Minitab](https://support.minitab.com/en-us/minitab/help-and-how-to/statistical-modeling/regression/supporting-topics/basics/slope-and-intercept-of-the-regression-line/)  Definition of slope and intercept. 

[numpy.polyfit](https://numpy.org/doc/stable/reference/generated/numpy.polyfit.html) Numpy official documentation. 

#### Task 7: 

[Box plot and Histogram exploration on Iris data](https://www.geeksforgeeks.org/box-plot-and-histogram-exploration-on-iris-data/) Boxplots on the Iris dataset. 

[Selecting rows in pandas DataFrame based on conditions](https://www.geeksforgeeks.org/selecting-rows-in-pandas-dataframe-based-on-conditions/) Pandas functionalities.

[numpy.quantile](https://numpy.org/doc/stable/reference/generated/numpy.quantile.html) Official Numpy documentation. 

#### Task 8: 

[Pearson correlation coefficient, Wikipedia](https://en.wikipedia.org/wiki/Pearson_correlation_coefficient) Definition of PCC. 

[Correlation Coefficient | Types, Formulas & Examples, Scribbr](https://www.scribbr.com/statistics/correlation-coefficient/#:~:text=A%20correlation%20coefficient%20is%20a,variables%20are%20across%20a%20dataset) Another definition of PCC. 

[NumPy, SciPy, Pandas, correlation, Real Python](https://realpython.com/numpy-scipy-pandas-correlation-python/#linear-correlation) Calculating PCC with Numpy, SciPy, Pandas. 

[numpy.corcoeff](https://numpy.org/doc/2.2/reference/generated/numpy.corrcoef.html) Official Numpy documentation. 

[Annotated heatmap](https://matplotlib.org/stable/gallery/images_contours_and_fields/image_annotated_heatmap.html) Official Matplotlib documentation. 

[Choosing Colormaps in Matplotlib](https://matplotlib.org/stable/users/explain/colors/colormaps.html#sphx-glr-users-explain-colors-colormaps-py) Personalise colormaps, official documentation. 

[The correlation coefficients between measurement variables:](https://www.angela1c.com/projects/iris_project/investigating-the-iris-dataset/#:~:text=The%20correlation%20coefficients%20between%20measurement%20variables%3A&text=a%20strong%20positive%20correlation%20between,Iris%20Virginica%20at%20over%200.86) Correlation matrix. 

[Linear correlation](https://realpython.com/numpy-scipy-pandas-correlation-python/#linear-correlation) Definition of Linear Correlation.  

#### Task 9: 

[Coefficient of determination](https://en.wikipedia.org/wiki/Coefficient_of_determination) Definition of Coefficient of Determination. 

[scipy.stats.linregress](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.linregress.html) Official SciPy documentation. 

[Writing Mathematic Fomulars in Markdown](https://csrgxtu.github.io/2015/03/20/Writing-Mathematic-Fomulars-in-Markdown/) How to write mathmatical formulas in markdown. 

#### Task 10: 

[seaborn.pairplot](https://seaborn.pydata.org/generated/seaborn.pairplot.html) Official Seaborn documentation. 

[pandas.DataFrame.replace](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.replace.html) Replacing values in Pandas dataframes. 

[Indexing and selecting data](https://pandas.pydata.org/docs/user_guide/indexing.html) Selecting data in Pandas dataframe. 
