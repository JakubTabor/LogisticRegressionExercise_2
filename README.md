# LogisticRegressionExercise_2
# I get my "breast_cancer.csv" and it is ready to use
# So i make "train_test_split" on my "X" and "y", y is last column X is rest without firs column
# Then I import "LogisticRegression" model and train it """classifier.fit(X_train, y_train)"""
# I get "y_pred" on my "X_test" """y_pred = classifier.predict(X_test)""" 
# So I can import "confusion_matrix" and put my "y_pred" "y_test" into """cm = confusion_matrix(y_test, y_pred)"""
# and i can calculate "accuracy_score" from my "confusion_matrix" """(84 + 47)/(84 + 47 + 6)"""
# To compute accuracy with another model I can import "cross_val_score", set parameters and check results
# It is just a bit better, I print accuracy in fromat with "mean" and set (*100) to get percentage value
# And also print accuracy of "std"
