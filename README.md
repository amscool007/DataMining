# DataMining

The Global Terrorism Database (GTD) documents about 190,000 international and domestic terrorist attacks that occurred worldwide since 1970. With details on various dimensions of each attack, the GTD familiarizes analysts, policymakers, scholars, and journalists with patterns of terrorism. The GTD defines terrorist attacks as:- The threatened or actual use of illegal force and violence by a non-state actor to attain a political, economic, religious, or social goal through fear, coercion, or intimidation.


We will be addressing the question that can the number of kills and wounded be predicted from the various attack characteristics. We will be following the CRISP-DM technique by understanding the various stages firstly and understanding those, then going through the data pre-processing and how it was done. Firstly, the business understanding of the dataset and understand the problem statement by looking into the research question. Then we look into the data for a better understanding to get to know what features and take only useful columns for our analysis. Then we did the data preparation i.e. cleaning our dataset by removing null values and its values are removed in every step of the heat map.

After the data Preparation, we will now go through the transformation phase .i.e. making our model. We will first use an extra tree classifier that helps in getting what features are to be taken that tells what are the important features that play a part in our research question.

We then implement our model so that we research question can be solved easily. Firstly we use Random forest, Logistic Regression and Support Vector Machines for the research question i.e.


correlation between terrorist attacks and weather conditions which is done by merging weather database and terrorist database, Then we go through the second part of the question i.e. understanding significant features which have more effect on the number casualties in the terrorist attacks over the world and implement Random Forest . We plot the ROC curve, get the F1 score and confusion matrix. Using the same question, we predict using logistic regression and SVM and plot the confusion matrix, F1 score.
