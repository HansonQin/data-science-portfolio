# Formality Model
Included in this directory is a formality model for Z-mail, an email creator for non-native english speakers. Built for UC Berkeley's DATA-X course.

### Methods Used
* Data Processing
* Machine Learning
* Feature Engineering
* etc.

### Technologies
* Python
* Pandas, MLTK, NumPy, spaCy, sklearn
* etc.

The "Formality_Checker" file trains a logistic regression model on a dataset of 90,000 sentences with their formality labeled 
as either 1 for formal or 0 as informal. Those sentences are curated from a combination of multiple online datasets and corpuses,
containing a wide variety of texts such as conversational, government papers, technical, financial papers, and newsletters, etc.
All of those sources are labeled based on their sources and cleaned to be formatted the same (look like sentences).

We have experimented with various other models such as SVM and gradient boosting, but we settled on the logistic regression
since it performed well compared to the other models while producing very interpretable results.

The "Formality_Model_Trained_Model_Load" file loads the pickled trained model from Formality_Checker and runs it on a sample input.
The code from that file is used in the Z-mail application to score the formality of sentences in user-inputted emails.
