# ProteinModel

*Comparing various classification models in terms of their performace in predicting whether proteins are IL6-inducing proteins or not ("Pos" or "Neg")
based on their amino acid compisition.*

**Models utilized**
- "KNN": KNeighborsClassifier(),
- "Naive Bayes": GaussianNB(),
- "SVM": SVC()
- "Decision Tree": DecisionTreeClassifier()
- "Random Forest": RandomForestClassifier()
- "Logistic Regression": LogisticRegression()
- "Linear Discriminant Analysis": LinearDiscriminantAnalysis()

**Performance metrics**

    - Mean accuracy score and standard deviation upon 10-fold cross-validation;
    - AUROC (Area Under Reciever Operator Characteristic Curve)

*Highest performace shown for Random Forest Model.*

**Files**
- IL6_Peptides_Analysis.ipynb: Jupyter notebook
- Data.csv: dataset used
    columns: Target Variable + Amino Acids;
    Values in cells represent amino acid percentage composition;

*Jehad Yasin, August 2023*

*Amman, Jordan*
  
