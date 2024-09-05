# SVM: Support vector machine 
It can be use for regression and classification model and when we are using for regession model that time it is called as CVR and When we are using it for classification that time we will called it SVC. 

# why we are using svm?
SVM is used to handle lage sizedata sent and when in this we can classified our data in 3 axis and if the classification of our model is non liner then we will use SVM concept. It is supervised machine learning. It is utilizing 4 concepts.
1. Karnel: it will convert non linear classification to liner classification.Three types of karne:
   ##Linerar
   ##polynomial
   ##RBF (radial basis function)
2. Hyper plane : Once ur nonliner dataset will convert into linear dataset then Hyper plan is used to classified the data.
3. Margin: Hyper plane will be in centor of 2 class but from lower class and upper class we will caluclate distance if that distance is masimum that means less chnaces for misclassification. Margin will be present in uper and lower side of upper side of hyper plane.We have two type of margin:
   ##Soft margin: if we capable to find margin easily then it is called soft margin.
   ##Hard margin: if it is difficult to find margin between hyperplane and lower or upper class that means hard margin is there.
 4. Support vector: The ponits which will be lies in the margin through that only we can maximize our margin.


If the hyperplane have equal distance from upper datapoint and lower datapoint that means less chances of missclassification but if one side distance is more that time high chance for miss classification.
We have 2 parameter to calulate margin:
Gammma: If value of gama is high that means we have hard margin and our model is complex model and chances of over fitting. 
c : if value of  c is high is that means we have hard margin and our model is complex model and chances of over fitting. 

