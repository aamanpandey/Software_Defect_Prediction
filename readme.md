Software Defect Prediction Data

Goal : Predict software defect

Dataset: Software Defect Prediction 

    Number of instances: 10885

    Number of attributes: 22

    Attribute Information:
        loc : numeric % McCabe's line count of code
        v(g) : numeric % McCabe "cyclomatic complexity"
        ev(g) : numeric % McCabe "essential complexity"
        iv(g) : numeric % McCabe "design complexity"
        n : numeric % Halstead total operators + operands
        v : numeric % Halstead "volume"
        l : numeric % Halstead "program length"
        d : numeric % Halstead "difficulty"
        i : numeric % Halstead "intelligence"
        e : numeric % Halstead "effort"
        b : numeric % Halstead
        t : numeric % Halstead's time estimator
        lOCode : numeric % Halstead's line count
        lOComment : numeric % Halstead's count of lines of comments
        lOBlank : numeric % Halstead's count of blank lines
        lOCodeAndComment: numeric
        uniq_Op : numeric % unique operators
        uniq_Opnd : numeric % unique operands
        total_Op : numeric % total operators
        total_Opnd : numeric % total operands 21: branchCount : numeric % of the flow graph
        defects : {false,true} reported defects

    Missing attributes: none

    Class Distribution: the class value (defects) is discrete

    False: 2106 = 19.35%

    True: 8779 = 80.65%

    Evaluation Metric: ROC - AUC

Objective:

Use Imbalanced data handling techniques
Make prediction model

Key Points:

Used Data Pipelines for data pre-processing

Used ROC-AUC as scoring metrics

Used different technique to handle imbalanced dataset

Used Cost Sensitive Techniques

Used Data Sampling Techniques

Used Grid Search to tune hyperparameter of the ML models

Used corss validation score to decide best model for the dataset
