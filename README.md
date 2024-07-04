# kaggle
This repository will contain notebooks I have used in kaggle competitions I have joined. So far I have joined two competitions; one as a requirement for my training by ExploreAI and the second one was in fulfilment of requirements in the application of a fellowship opportunity by kaggle.

Recommender system
The first competition, which involved the building of recommender system contained several million 5-star ratings obtained from users of the online MovieLens movie recommendation service. The MovieLens dataset has long been used by industry and academic researchers to improve the performance of explicitly-based recommender systems.
Supplied Files
genome_scores.csv - a score mapping the strength between movies and tag-related properties. Read more here
genome_tags.csv - user assigned tags for genome-related scores
imdb_data.csv - Additional movie metadata scraped from IMDB using the links.csv file.
links.csv - File providing a mapping between a MovieLens ID and associated IMDB and TMDB IDs.
sample_submission.csv - Sample of the submission format for the hackathon.
tags.csv - User assigned for the movies within the dataset.
test.csv - The test split of the dataset. Contains user and movie IDs with no rating data.
train.csv - The training split of the dataset. Contains user and movie IDs with associated rating data.

Evaluation
The evaluation metric for this competition wass Root Mean Square Error. Root Mean Square Error (RMSE) is commonly used in regression analysis and forecasting, and measures the standard deviation of the residuals arising between predicted and actual observed values for a modelling process.

Submission Format
For every author in the dataset, submission files contained two columns: Id and rating. Id was a concatenation of the userID and movieID given in the test file (using an _ character). Rating was the predicted rating for a given user-movie pair. The file contained a header and had the following format:
Id,rating
1_2011,1.0

KaggleX Skill Assessment
The skill assessment challenge wass a component of the application that will allow the program team to validate the applicant's hands-on experience in data science.
The dataset for this competition (both train and test) was generated from a deep learning model fine-tuned on the Used Car Price Prediction Dataset dataset.

Files
train.csv - the training dataset
test.csv - the test dataset; objective was to predict the value of the target Price
sample_submission.csv - a sample submission file in the correct format

Evaluation
Root Mean Squared Error (RMSE)
Submissions were scored on the root mean squared error.

Submission File
For each id in the test set,  the price of the car was predicted. The file contained a header and had the following format:
id,price
54273,39218.443
54274,39218.443
54275,39218.443
