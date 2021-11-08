# **Capstone Project**

This repository contains source code and related documents for my capstone project the Data Analytics, Big Data, and Predictive Analytics certificate program at Ryerson University.

# **Abstract**

Businesses these days are using every available platform to do marketing of their company, products, and services. Telemarketing is still the most used method of increasing sales of small to big companies. Predictive analytics uses data models, statistics, and machine learning to predict future events. It's a discipline that helps you to analyze your marketing campaigns, assess their efficiency, and see possible improvements to lead to an increase in sales in the future. This project focuses on predicting customers’ response to a potential subscription of a term deposit account with Bank Marketing Campaign. The prediction will be achieved by using Machine Learning Classification algorithms with coding in Python programming language. The accomplishment of this research is to help the company reliably predict future customer subscriptions before it occurs. This project will be able to answer the following questions:

- Will prospective customers respond "yes" or "no" to term deposit subscription?
- What type of customers are more likely to subscribe to term deposit and which feature has higher influence?
- What is the best time of year for a marketing campaign?

# **Project Structure**	

**1. Abstract** 

The abstract briefly describes the research question and methods that are used.  

**2. Literature Review**

The Literature Review research and review papers and technical articles related to the same problem were chosen.
 
**3. Initial Results and the Code**

Contains Data analyses, including summarizing and visualizing data, data preparation, including selecting, preprocessing, and transforming data, models evaluation, including testing options, exploring algorithms, and reporting results.

**4. Final Results and Project Report**

The Project Report documents the data analysis procedures and evaluates the developed machine learning. Documents the statistical analyses and covers the analysis limitations, study implications, and critical insights on improving the work. Fully interpret the achieved results of the proposed methodology.

**5. Final Presentation**

The presentation summarizes the research findings and conducted analyses.

# **Methodology**
- Data exploration and visualization
- Splitting data to training set 70% and testing set 30% 
- Cleaning data on training set including outliers, duplicates, gruping,   
- Categorical variables treatment
- Class Balance (Oversampling  SMOTE)
- Feature Training 
  - Filter (Mutual Information) 
  - Wrapper (Forward Selection)
  - Embedded method (LASSO Regularization L1) 
- Feature Selection, Extraction
- Classification Algorithms Logistic Regression, Desision Tree, Rendom Forest (12 times will run)
- Predicting on testing set
- Algorithms Evaluation ROC_AUC, Precision, Recall, F1, PR_AUC, Brier Score
- Classification Results



