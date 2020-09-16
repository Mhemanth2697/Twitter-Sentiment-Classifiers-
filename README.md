# Twitter-Sentiment-Classifiers-
Multiple Machine Learning Models were built to compare their performance on classifying Twitter sentiments about Airlines. 

The objective was to understand the working of various Machine Learning models, and weigh them against one another.

Pre-Processing
We preprocessed the data to make it ready for the various Machine Learning models which included conversion to corpus, removal of punctuation, stopwords and stemming.
We built a Bag of Words and passed this as the input data for the models. 

Models Implemented
•	Logistic Regression
•	KNN Classification
•	Neural Nets
•	Support Vector Machine
•	Linear Discriminant Analysis
•	Decision Tree
•	Random Forest

Performance and Results
Overall, we feel selecting the Random Forest model would be the most optimal. The accuracy is almost equal to other models (SVM and LDA), however, it has the second highest sensitivity among all models. Since our objective was to check if we can successfully classify negative feedback first, its sensitivity, coupled with its accuracy, it is the most sensible model. 
However, if we were to prioritize complete negative feedback classification, we would recommend Decision Tree model.

Project and files
The project was implemented in RStudio. The files for the project are CaseStudy. If the Data Analysis plots are to be replicated, then use the Plots file.
A complete Project report has also been included, along with the final performance comparision graphs for the various models.


