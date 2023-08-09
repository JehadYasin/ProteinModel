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
- IL6_Peptides_Analysis.ipynb: Jupyter notebook
- Data.csv: dataset used
    columns: Target Variable + Amino Acids;
    Values in cells represent amino acid percentage composition;

Jehad Yasin, August 2023
Amman, Jordan
  
