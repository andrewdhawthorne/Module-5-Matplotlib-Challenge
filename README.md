# Module-5-Matplotlib-Challenge
files for Data Boot Camp Module 5 Matplotlib Challege

# Challenge Overview 
In this challenge I analyzed data from an animal study on mice with tumors receiving a range of drug treatments. The drug of focus was Capomulin, which was compared to three other regimens over 45 days. My first step was to combine the provided datasets and clean the data by removing data from duplicate time points. The number of observations per drug were visualized through bar charts and the gender distribution was illustrated with pie charts. I created a boxplot depicting the final tumor volume of mice treated by Capomulin, Ramicane, Infubinol, and Ceftamin, and used a line chart and regression line to visualize the correlation between mouse weight and average tumor volume. I also created a line plot depicting the affect of Capomulin on the tumor volume of one randomly-selected mouse. 

Please see final analysis and recommendations at the beginning of the Jupyter Notebook for this assignment. 

# Sources

Starter code provided by instructional team.

Classmates: I worked extensively with cohort members Caleb Gould and Fidel Carrillo.

Links & Class Activities: 

Finding and removing duplicate data - https://sparkbyexamples.com/pandas/pandas-get-list-of-all-duplicate-rows/#:~:text=You%20can%20use%20df%5Bdf,duplicate%20rows%20in%20our%20DataFrame, https://sparkbyexamples.com/pandas/pandas-rename-multiple-columns/, https://www.statology.org/pandas-drop-rows-with-value/

Creating summary table - 06-Ins_GroupBy (Pandas day 2), cohort member Caleb Gould 

Creating summary table in one line - https://pandas.pydata.org/pandas-docs/version/0.22/generated/pandas.core.groupby.DataFrameGroupBy.agg.html, cohort member Fidel Carrillo 

Creating bar plot with Pandas and saving images to files - https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.plot.html, https://www.youtube.com/watch?v=C8MT-A7Mvk4 

Resetting DataFrame index and creating bar plot with pyplot - https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.reset_index.html, https://towardsdatascience.com/change-font-size-matplolib-480630e300b4, 08-Stu_PyBars (Matplotlib day 1)

Creating pie plot with Pandas - https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.plot.html, https://matplotlib.org/stable/gallery/color/named_colors.html

Creating pie plot with pyplot - 10-Stu_PyPies (Matplotlib day 1)

Boxplot of final tumor volumes - https://github.com/jaysueno/pymaceuticals/blob/master/Pymaceuticals/Pymaceuticals_jay_v2_FINALSUBMISSION.ipynb, https://www.tutorialspoint.com/how-to-adjust-marker-size-in-matplotlib, https://towardsdatascience.com/creating-boxplots-of-well-log-data-using-matplotlib-in-python-34c3816e73f4, https://stackoverflow.com/questions/65648502/how-to-change-outlier-point-symbol-in-python-matplotlib-pyplot#:~:text=To%20only%20change%20the%20symbol,also%20returned%20by%20box%20%3D%20plt.

Calculating quartiles and outliers - https://github.com/jaysueno/pymaceuticals/blob/master/Pymaceuticals/Pymaceuticals_jay_v2_FINALSUBMISSION.ipynb, 02-Ins_Quartiles_and_Outliers (Matplotlib day 3)

Line and scatter plots - https://github.com/jaysueno/pymaceuticals/blob/master/Pymaceuticals/Pymaceuticals_jay_v2_FINALSUBMISSION.ipynb, https://www.statology.org/pandas-select-rows-based-on-column-values/, https://www.geeksforgeeks.org/how-to-randomly-select-rows-from-pandas-dataframe/, 06-Ins_Correlation_Conundrum (Matplotlib day 3), 08-Ins_Fits_and_Regression (Matplotlib day 3)