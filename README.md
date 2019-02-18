
Umuzi assignment: Predicting salaries differences

Start: Monday 11 June
Due: Tuesday 12 June 12pm

In the next series of challenges, we will predict employee salaries from different employee characteristics (or features). We ask employees working in four different fields to state their salary and some background information. 

Import the data salary.csv to a Jupyter Notebook and answer the following questions:

Question 1
    a) How many responders are there? Are there any missing values in any of the variables?
        514 responders with 1 missing entry in the salary column
    b) What is the lowest salary and highest salary in the group?
        Lowest salary: 29000
        Highest salary: 96156
    c) What is the mean salary for the sample? Include the standard error of the mean.
        Mean: 50863.22
        Standard error mean: 560.0622
    d) What is the standard deviation for the years worked?
        9.4378
    e) What is the median salary for the sample?
        50096
    f) What is the interquartile range for salary in the sample?
        20345
    g) How many men are there in the sample? How many women are there in the sample? Present this information in a table. 
        Men
        Women
        385
        128

    h) How many women are executives compared to men? 
        19 female executives
        191 Male executives

    i) Create a histogram for the variable Salary.

    j) Examine the histogram and describe the distribution for Salary.
        Salary is skewed right
    k) Create a bar graph to show the different average salaries of men and women. (Bonus: Add error bars to the bars showing the 95% confidence interval). What does the graph tell you about the difference between men and women’s salaries? 
        Males have higher average salaries than women
    l) Create a scatterplot showing the relationship between Years Worked and Salary (don’t forget to insert a trend line). What is the relationship between Years Worked and Salary?
        1. Describe any patterns in the scatterplot. Do you notice any unusual/extreme values that do not fit the general trend? If you see any unusual values, briefly describe them (Who are they? In what way are they different?)
            There is a positive-linear relationship in the data. With a moderate relationship between years worked and salary. We’ve got outliers that either have high salaries with fewer years worked or many years worked with lower salaries
    m) Using the pearsonr function from the scipy.stats package, calculate the Pearson correlation coefficient (and its corresponding p value) to determine the nature of the relationship between Years Worked and Salary. See help(pearsonr) for help on this function.
        1. Interpret the size and direction of the correlation statistic. 
            A moderate uphill (positive) relationship
        2. Is the relationship statistically significant? Report the appropriate statistic(s) to support your answer. 
            It is not because the p-value is 1.2873351342921916e-56



