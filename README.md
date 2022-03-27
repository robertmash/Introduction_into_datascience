# [Project 1: Focusing on cleaning and visulisation using R](https://github.com/robertmash/intro_to_data_science)
- used packages: Tidyvserse, ggplot2, janitor, here, and lubridate.
- Uses data from Nasa and GOV.uk, I've linked these below. 
- Visualise trends and statistics based of climate change, and rates of stops and searches throughout my investigation.
- I find that In 2017, we can denote that black people were up to 8 times more likely to be stopped in comparison to white people. This is similar with the Asian population who are increasingly more likely to be stopped over white individuals. I didn't include the "Other" variable as it was missing some data, which wouldnt add any impact to the conclusion. 

## Visualisations after cleaning:

![](https://github.com/robertmash/Projects/blob/main/images/visualisations.png)


### [Data used in this investigation](https://github.com/robertmash/intro_to_data_science/tree/main/data)

# [Project 2: Statistical Methods and Data Analysis](https://github.com/robertmash/stats_project)
- Firstly cleaning the datasets and collecting summary stats about each variable. 
- We look at 3 main datasets, car data, comicbook characters and premier league players.
- Also look at 'Salaries' dataset within R, which illistrates the 
- Implementing statistical analysis on a multitude of datasets to derive statistically significant results
- Using linear, multi-linear and logistic regression methods. 
- Plotting confidence intervals & checking for normality. 
- Plotting ROC, interpretting the AUC. Graphing my findings, showing both sensitivity and specificity values. 
- Creating a GLM for the 'divisionWinners' of our baseball dataset. This is then split into a test and training set, to graph the ROC and a confusion matrix.

## Findings: 

- We can see that our first confusion matrix for the training data identified 100/106  correctly. Illustrating that 94.34% of Divwinners were identified correctly. In comparison, we can denote that 346/418 were identified as non Divwinners. Which gives us a 82.78% accuracy of finding the those teams that weren't division winners. This emphasizes that our model for our training data is a good fit. 

- Similarly, our second confusion matrix identifies 19/26 correctly. Giving us a 73.07% accuracy in recognizing individuals who were Divwinners. Still a high percentage, but not as accurate as the other model. Additionally, 94/104 individuals are reconfigured as not division winners. Giving us a 90.38% of acknowledging those who weren't division winners. In conclusion, both models give relatively high rate of identifying division winners, evidently our first model is significantly better at identifying division winners. 

- (10/19+10) works out our false negative rate for the testing data, this equates to 0.096 2.dp. Which gives us a false positive rate of 9.65%. Next we can work out the false positive rate for the testing data. This is equal to (7/7+19), Which equates to 0.26923, percentage wise this = 26.923%. The rate of false positives is greater than estimating false negatives for the testing data. 

## Statistical visualisations (ROC, log10 relationships, Residual vs Leverage and Specificity & Sensitivity, Confidence Intervals):

![](https://github.com/robertmash/robertmash_portfolio/blob/main/images/statistical_graphs.png)

### [Data used in this investigation](https://github.com/robertmash/stats_project/tree/main/data)


