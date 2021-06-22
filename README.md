# Risk Return Analysis

This application takes in historical price data from 4 large portfolios as well as the S&P-500 and examines the performance of each of the 4 funds against the S&P-500 ultimately choosing one and recommending it as an investment for a retirement account. It takes into account various performance and statistical metrics like annual expected return, standard deviation, variance, sharpe ratio and Beta.

---

## Technologies

This project uses the Python Programming language in a Jupyter Notebook as well as the following libraries
    
    - Pandas
    - Pathlib
    - matplotlib
    - Numpy


---

## Installation Guide

To install you will want to pull the entire Risk_Return folder from github including its subfolder
    
    * Subfolder
        * Resources (data folder)
        * risk_return_analysis.ipynb (the jupyter notebook itseld)


---

## How it works

1) First the user will open the risk_return_analysis.piynb notebook in the Risk_Return folder
2) Then the user will simply run each cell in the notebook to get its output

    i) The app will collect the data from the whale_navs.csv and read it into a dataframe
    
    ii) Then it will check each dataframe for null values
    
    iii) Then it will process the data, calculating the daily % change and dropping the NaN values from the % change calculation
    
    iv) Then it will plot the daily % returns of each fund on one plot and gather the basic statistical data of each fund by use of the pandas describe function
    
    v) Then it will calculate the cumulative performance of each fund as well as the S&P-500 and plot them together
    
    vi) Then it will create a box plot to help visualize the volatility of each fund (it will do this twice, once with the S&P and once without it)
    
    vii) Then it will calculate and examine the mean and standard deviation of each portfolio ranking them from smallest to largest
    
    viii) Then it will plot the 21 day rolling standard deviation (it will do this twice, once with the S&P and once without it)
    
      ix) Then it will calculate and plot the Sharpe Ratio of each fund
      
      x) It will then conclude by calculating the Beta of the two funds with the best Sharpe Ratios and making a reccomendation on which of the two to buy.

---

## Usage

Overall it should be a very simple application to use, all you need to do is open the risk_return_analysis.ipynb app in the Risk_Return folder and run each cell in order


---

## Contributors

Colin Benjamin

Linkedin: [Colin Benjamin](https://www.linkedin.com/in/colinbenjamin/)
    
email: cbenjamin33@gmail.com

---

## License

MIT
