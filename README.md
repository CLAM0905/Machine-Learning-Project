C8Proj1 Machine Learning
CLAM0905
January 14, 2020

Please look at the PDF document or use the following link to view full analysis: http://rpubs.com/CLAM0905/566196

This assignment is designed to perform prediction analysis on a large dataset, in order to predict the class of 20 test cases. Details can be found on the website, included below, and can be summed up by the following. Six participants were asked to perform one set of 10 repetitions of the Unilateral Dumbbell Biceps Curl in five different fashions: exactly according to the specification (Class A), throwing the elbows to the front (Class B), lifting the dumbbell only halfway (Class C), lowering the dumbbell only halfway (Class D), and throwing the hips to the front (Class E). My algorithm uses the “KNN: K nearest neighbor” approach to classify the existing 19,000+ cases into their appropriate class, where I will validate the efficiveness by comparing the predicted class to the actual class. From there, I will use my algorithm to classify the test cases into their predicted class, verifying the accuracy using the follow up quiz.

HAR website with background and more details: http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har

Conclusion: My knn algorithm was able to predict the class of the 20 test cases with 75% accuracy. The accuracy on the train dataset was 98%. This leads me to the conclusion that my knn algorithm was accurate, but overfit the train model and was not able to accurately predict on the test dataset to the same accuracy. More work needs to be done on my knn algorithm to be more accurate on test datasets, but it is a good start to learning and practicing machine learning techniques. Thank you for reading!
