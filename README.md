# ProteinModel

Comparing various classification models in terms of their performace in predicting whether proteins are IL6-inducing proteins or not ("Pos" or "Neg")
based on their amino acid compisition. 

Models utilized: 
- "KNN": KNeighborsClassifier(),
- "Naive Bayes": GaussianNB(),
- "SVM": SVC(probability=True, kernel='linear'),
- "Decision Tree": DecisionTreeClassifier(random_state=42),
- "Random Forest": RandomForestClassifier(random_state=42),
- "Logistic Regression": LogisticRegression(random_state=42),
- "Linear Discriminant Analysis": LinearDiscriminantAnalysis()

Files:
  
