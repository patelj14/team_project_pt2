# Reposistory log

## 9 August 2024 _ Commit changes: CNN_model
I applied a Convolutional Neural Network (CNN) to analyze a dataset to investigate whether CNNs could uncover patterns or relationships not captured by simpler models. 
I have done the analysis for both datasets, namely the data_all.csv and the data_first_third.csv.
The finding of 'age' amd 'sex' relating to the 'target' in data_all.csv with CNN is not significant. 
As for the data_first_third.csv, I firstly compare the features with the target using a loop feature, to find out which of the features would be highly related to the target outcome.
Then, I find 'ST_slope' and 'chest_pain_type' being top two most significantly related features to the target outcome.
So, I have done the analysis with CNN with 'ST_slope' and the combination of 'ST_slope' and 'chest_pain_type'.
The CNN model, designed to leverage convolutional layers for advanced feature extraction, was tested on a dataset with a straightforward relationship between features and target. 
Despite this, the CNN's performance did not significantly surpass that of the logistic regression model previously used, highlighting that while CNNs are powerful for complex and hierarchical data, their advantages may be limited when the underlying data structure is simple. 
This comparison underscores the importance of model selection based on the complexity and nature of the dataset.
