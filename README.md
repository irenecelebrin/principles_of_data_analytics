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

[UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/53/iris)

#### Task 2: 

[load_iris](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html)

[gist.github.com/curran](https://gist.github.com/curran/a08a1080b88344b0c8a7)

[numpy review](https://ds100.org/fa17/assets/notebooks/numpy/Numpy_Review.html)

#### Task 3:

[numpy.mean](https://numpy.org/doc/stable/reference/generated/numpy.mean.html)

[numpy.min](https://numpy.org/doc/stable/reference/generated/numpy.max.html)

[numpy.min](https://numpy.org/doc/stable/reference/generated/numpy.min.html)

[numpy.std](https://numpy.org/doc/stable/reference/generated/numpy.std.html)

[numpy.median](https://numpy.org/doc/stable/reference/generated/numpy.median.html)

[Mean, Wikipedia](https://ds100.org/fa17/assets/notebooks/numpy/Numpy_Review.html)

[Maximum and Minimum, Wikipedia](https://en.wikipedia.org/wiki/Maximum_and_minimum)

[How to Calculate Standard Deviation (Guide) | Calculator & Examples](https://www.scribbr.com/statistics/standard-deviation/#:~:text=The%20standard%20deviation%20is%20the,clustered%20close%20to%20the%20mean.)

[Median in Statistics](https://www.geeksforgeeks.org/median/)

#### Task 4: 

[Pyplot vs Object Oriented Interface](https://matplotlib.org/matplotblog/posts/pyplot-vs-object-oriented-interface/)

[matplotlib.pyplot.hist]( https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.hist.html)

[List of named colors](https://matplotlib.org/stable/gallery/color/named_colors.html)

[What Is a Boxplot?](https://builtin.com/data-science/boxplot#:~:text=A%20boxplot%20is%20a%20graph,in%20comparison%20to%20the%20IQR)

[matplotlib.axes.Axes.boxplot](https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.boxplot.html)

[Change the colors of outline and median lines of boxplot in matplotlib](https://stackoverflow.com/questions/57668399/change-the-colors-of-outline-and-median-lines-of-boxplot-in-matplotlib)

[Box plots with custom fill colors](https://matplotlib.org/stable/gallery/statistics/boxplot_color.html#sphx-glr-gallery-statistics-boxplot-color-py)

[matplotlib.axes.Axes.set_xticks](https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.set_xticks.html#matplotlib.axes.Axes.set_xticks)

#### Task 5: 

[Matplotlib essentials](https://medium.com/@The_Gambitier/matplotlib-essentials-e376ed954201)

[matplotlib.pyplot.scatter](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.scatter.html)

[Making a Python Scatter Plot with Different Colors for Different Labels](https://jamesmccaffrey.wordpress.com/2020/10/22/making-a-python-scatter-plot-with-different-colors-for-different-labels/)

[matplotlib.markers](https://matplotlib.org/stable/api/markers_api.html#module-matplotlib.markers)

[OpenAI chatGPT](https://chatgpt.com/share/67f2c42b-a108-800f-9b47-c15d529b5264)

#### Task 6: 

[Simple Linear regression, Wikipedia](https://en.wikipedia.org/wiki/Simple_linear_regression)

[Slope and Intercept, W3School](https://www.w3schools.com/datascience/ds_linear_slope.asp)

[Slope and intercept of the regression line, Minitab](https://support.minitab.com/en-us/minitab/help-and-how-to/statistical-modeling/regression/supporting-topics/basics/slope-and-intercept-of-the-regression-line/)

[numpy.polyfit](https://numpy.org/doc/stable/reference/generated/numpy.polyfit.html)

#### Task 7: 

[Box plot and Histogram exploration on Iris data](https://www.geeksforgeeks.org/box-plot-and-histogram-exploration-on-iris-data/)

[Selecting rows in pandas DataFrame based on conditions](https://www.geeksforgeeks.org/selecting-rows-in-pandas-dataframe-based-on-conditions/)

[numpy.quantile](https://numpy.org/doc/stable/reference/generated/numpy.quantile.html)

#### Task 8: 

[Pearson correlation coefficient, Wikipedia](https://en.wikipedia.org/wiki/Pearson_correlation_coefficient)

[Correlation Coefficient | Types, Formulas & Examples, Scribbr](https://www.scribbr.com/statistics/correlation-coefficient/#:~:text=A%20correlation%20coefficient%20is%20a,variables%20are%20across%20a%20dataset)

[NumPy, SciPy, Pandas, correlation, Real Python](https://realpython.com/numpy-scipy-pandas-correlation-python/#linear-correlation)

[numpy.corcoeff](https://numpy.org/doc/2.2/reference/generated/numpy.corrcoef.html)

[Annotated heatmap](https://matplotlib.org/stable/gallery/images_contours_and_fields/image_annotated_heatmap.html)

[Choosing Colormaps in Matplotlib](https://matplotlib.org/stable/users/explain/colors/colormaps.html#sphx-glr-users-explain-colors-colormaps-py)

[The correlation coefficients between measurement variables:](https://www.angela1c.com/projects/iris_project/investigating-the-iris-dataset/#:~:text=The%20correlation%20coefficients%20between%20measurement%20variables%3A&text=a%20strong%20positive%20correlation%20between,Iris%20Virginica%20at%20over%200.86)

[Linear correlation](https://realpython.com/numpy-scipy-pandas-correlation-python/#linear-correlation)

#### Task 9: 

[Coefficient of determination](https://en.wikipedia.org/wiki/Coefficient_of_determination)

[scipy.stats.linregress](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.linregress.html)

[Writing Mathematic Fomulars in Markdown](https://csrgxtu.github.io/2015/03/20/Writing-Mathematic-Fomulars-in-Markdown/)

#### Task 10: 

[seaborn.pairplot](https://seaborn.pydata.org/generated/seaborn.pairplot.html)

[pandas.DataFrame.replace](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.replace.html)

[Indexing and selecting data](https://pandas.pydata.org/docs/user_guide/indexing.html)


#### Extra: Some shortcuts to run the notebooks on Jupyter notebooks 

**Some shortcuts**
- render markdown cell: shift + enter | run code cell: shift + enter 
- delete a cell : D D 
- enter in edit mode: Enter 
- go in escape mode: Esc 
- add a cell above: A, add a cell below: B -- a code cell
- turn code cell in md cell: M
- turn md cell in code cell: Y
- fn + F1 to add shortcuts 


### TODO 

- How users can get started with the project
- Links to documentation. Where users can get help with your project
- Who maintains and contributes to the project
