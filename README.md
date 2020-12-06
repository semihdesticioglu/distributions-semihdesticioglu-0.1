# distributions-semihdesticioglu-0.1
*Distributions Package: Udacity - Data Scientist Nanodegree Program*

## Project Overview
In this project, I created a Distribution Package as a part of Data Scientist Nano Degree Program Software Engineering module.
Package contains functions to make calculations for normal distributions, binomial distributions and Gaussian distributions.
Package is uploaded to PyPi repository. 

**Install:**
```
pip install distributions-semihdesticioglu==0.1
```

## Package Information

### Distribution class

**Attributes:**
- mean : representing the mean value of the distribution
- standard deviation : representing the standard deviation of the distribution
- list of data : a list of floats extracted from the data file

**Methods:**
- read_data_file : given a file of numbers, reads data to create list of numbers

### Binomial class

**Attributes:**
- Distribution attributions 
- probability : representing the probability of an event occurring
- size : number of trials

**Methods:**
- calculate_mean : assigns and returns the mean
- calculate_stdev : assigns and returns the mean
- replace_stats_with_data : assign prob, size, mean, stdev
- plot_bar : plot bar graph of data
- pdf : Calculate the probability density
- plot_bar_pdf : Plot bar graph of the pdf

### Gaussian class

**Attributes:**
- Distribution attributes

**Methods:**
- calculate_mean: assigns and returns the mean
- calculate_stdev: assigns and returns the mean
- plot_histogram: plot histogram of data
- pdf: Calculate the probability density
- plot_histogram_pdf : Plot histogram of the pdf
