
# csda 1050F18S1 Sprint2
### Name: Eugene Park


### Sprint2

Continuing from Sprint1, as meaningful variables are discovered, those variables are used to build a predictive model. In the beginning, this exercise focuses on building a classification model that can predict employee's Active, Quit and Terminated status. Later on, a regression model gets developed to discover correlation between hiring cost and revenue. 

### Predictive Model Examples
For classification model, mostly Decision Tree model is used. Several different approaches are taken and below are a couple of examples using different variables. Its performance stats can be found in Sprint2 markdown files. 

Decision Tree model with more variable to reflect all three employee status
<img src="https://github.com/damnfastpig/CSDA-1050F18S1/blob/master/eugenepark/images/sprint2Rplot1.png">

Decision Tree model optimized for better accuracy  
<img src="https://github.com/damnfastpig/CSDA-1050F18S1/blob/master/eugenepark/images/sprint2Rplot2.png">

As classification lacks accuracy, regression models are developed to supplement the analysis. Its detail can be found in markdown files. 

Visualization of Hiring Cost and Revenue for correlation discovery
<img src="https://github.com/damnfastpig/CSDA-1050F18S1/blob/master/eugenepark/images/sprint2Rplot3.png">

Performance stats of linear regression model
<img src="https://github.com/damnfastpig/CSDA-1050F18S1/blob/master/eugenepark/images/sprint2Rplot4.png">

###Conclusion from Sprint2

Sprint2 analysis has started off with classification models such as Decision Tree and Random Forest. Although I was successful in increasing accuracy slightly, the overall performance was not satisfactory. Perhaps the failure was foreseen, given the limitation from small dataset. This does not mean that this analysis did not share any insights. As it was shown Data Exploration phase, this modelling has illustrated that more junior staff chooses to quit and more senior staff are terminated from the organization. Also bigger percentage in termination of senior staff hints that the organization tends to scrutinize senior staff's performance. Another discovery is that there is correlation between revenue and hiring cost. While it seemed obvious that hiring cost increase as revenue increases, it is very meaningful to quantify hiring cost in different business situations so it can help build budget for employee retention purpose. 

###Next step

Discoveries from sprint 1 and 2 will be put into a report for stakeholders. The goal is to create a report that insightful and beneficial to related party who are not necessarily familiar with machine learning. 