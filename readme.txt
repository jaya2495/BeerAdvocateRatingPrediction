
Description of files.

1. beerRatingEDA : In this notebook i have performed extensive data Analysis, visualization , Question Answers on the basis of data, Feature Selection on basis of correlation.

2. beerRatingpredictionusingRatingCategories : I have predicted the rating of beer on the basis of Rating categories: 

● review/appearance - rating of the beer's appearance (1.0 to 5.0)
● review/aroma - rating of the beer's aroma (1.0 to 5.0) 
● review/overall - rating of the beer overall (1.0 to 5.0) 
● review/palate - rating of the beer's palate (1.0 to 5.0) 
● review/taste - rating of the beer's taste (1.0 to 5.0)

 Review.json file is used (It has mean values of all the rating categories) for model evaluation.

I have used these to predict overall rating As they have good correlation with the target overall rating.
steps:
● Data Preprocessing and Cleaning and Visualization
● Feature selection 
● Comparison of different ml models on relevant evaluation metrics(Rms, accuracy score)


3. RatingPredictionusingReviewText: I have predicted rating on the basis of review text using Ngram approach and Tfidf vectorization and comparison of Ml models. Linear svm, naive bayes , knn .


steps:
● Review text Preprocessing using Nltk
● Data cleaning & Visualization
● Comparison of different ml models on relevant evaluation metrics.(Precision , recall, kappa , f1 score, Sensitivity, speceficity, Accuracy)
● Display results using classification report and confusion matrix.


Results :

Beer rating prediction on the basis of review Text using N gram approach gives good results compared to the rating categories.


