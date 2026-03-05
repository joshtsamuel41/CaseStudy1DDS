# CaseStudy1DDS
Repository for MSDS 6306 Case Study 1
[Executive Summary.docx](https://github.com/user-attachments/files/25774159/Executive.Summary.docx)


Executive Summary: Case Study 1

Frito Lay has hired DDSAnalytics to figure out why employees are leaving the company, which is otherwise known as attrition. DDSAnalytics will be attempting to predict which employees might be more likely to leave, as well identify the main reasons behind attrition so that Frito Lay can take the necessary steps to reduce it. An employee’s monthly income, the total number of years they worked, and even their overtime status are just a few of the many factors that we found to be significantly related to attrition. We ran both a Naïve Bayes model, as well as a KNN (k=4) model on our data. We ran each model for 100 different iterations of train and test splits, and took the mean accuracy, sensitivity, and specificity. Our Naïve Bayes model outperformed our KNN model in all three metrics with an average accuracy of 73.46%, average sensitivity of 66.75%, and average specificity of 74.79%. From an estimated cost standpoint, our Naïve Bayes model would cost us $2,164,724 when trying to predict attrition on a test set of 261 observations. This is $309,532 less than what it would cost us if we used our KNN model. Overall, we do feel confident in our ability to predict attrition and hope to save Frito Lay significant amounts of money in the future.  
