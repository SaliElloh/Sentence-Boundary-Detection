# Sentence-Boundary-Detection
Utilizing the Decision Tree Classifier, the project focuses on the binary classification of whether a period "." is categorized as an "End of Sentence" or "Not End of Sentence." 

# Introduction

This project focuses on Sentence Boundary Detection (SBD) through the implementation of a Decision Tree Classifier. It leverages a set of features to distinguish between periods that signify the end of a sentence and those that do not. Additionally, the program explores the efficacy of various feature combinations, providing insights into the impact of feature selection on classification accuracy.

# Example Input/Output

Example Input:
"Mr. Smith went to the store. He bought a bag of apples."

Example Output:

Period after "Mr." classified as "Not End of Sentence"
Period after "store" classified as "End of Sentence"

# Pseudocode Explanation
The program employs a series of data preprocessing steps and the Decision Tree Classifier to achieve Sentence Boundary Detection. Key components of the pseudocode include:

Data preprocessing via Test_Preprocess.py and Train_Preprocess.py to remove extraneous characters and labels.
Training and testing using the Decision Tree Classifier (SBD.py) with varying feature combinations.
Creation of SBD.test.out to provide a summary of test word classifications.

# Conclusion
The analysis of the system's performance underscores the importance of feature selection. While accuracy generally improves with an increased number of features, a more nuanced understanding is revealed by evaluating precision, recall, and F1 score. This comprehensive assessment allows for a more informed judgment of the system's effectiveness.







