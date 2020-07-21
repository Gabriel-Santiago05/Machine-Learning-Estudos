# Comparações entre os algorítimos


## • Base: Credit Data

Precisão – Algoritmo – Atributos (Pré processamentos)
0.8720 – Base Line Classifier
0.9379 – Naive Bayes (inconsistências + valores_faltantes + escalonamento)
0.9800 – Decision Tree (inconsistências + valores_faltantes + escalonamento)
0.9840 – Random Forest – n_estimators=40 (inconsistências + valores_faltantes + escalonamento)
0.9860 – KNN - n_neighbors=5, metric='minkowski', p=2 (inconsistências + valores_faltantes + escalonamento)

--------------------------------------------------------------------------------------------------------------

## • Base: Census

0.4767 - Naive Bayes (LabelEncoder + OneHotEncoder + escalonamento)
0.7930 - Naive Bayes (OneHotEncoder + escalonamento)
0.7952 - Naive Bayes (LabelEncoder) 
0.7950 - Naive Bayes (LabelEncoder + OneHotEncoder)
0.8057 - Naive Bayes (LabelEncoder + escalonamento)


0.8102 - Decision Tree (LabelEncoder + OneHotEncoder + escalonamento)
0.8128 - Decision Tree (LabelEncoder)
0.8128 - Decision Tree (LabelEncoder + OneHotEncoder)
0.8128 - Decision Tree (LabelEncoder + escalonamento)


0.8476 - Random Forest (LabelEncoder + OneHotEncoder + escalonamento)
0.8481 - Random Forest (LabelEncoder)
0.8489 - Random Forest (LabelEncoder + OneHotEncoder)
0.8483 - Random Forest (LabelEncoder + escalonamento)
--------------------------------------------------------------------------------------------------------------


## • Base: Bank-Full

0.8571 - Naive Bayes (LabelEncoder + OneHotEncoder + escalonamento)

0.8571 - Naive Bayes (OneHotEncoder + escalonamento)

0.8602 - Naive Bayes (OneHotEncoder)

0.8457 - Naive Bayes (LabelEncoder) 

0.8602 - Naive Bayes (LabelEncoder + OneHotEncoder)

0.8414 - Naive Bayes (LabelEncoder + escalonamento)



0.8796 - Decision Tree - criterion='entropy' (LabelEncoder + OneHotEncoder + escalonamento)

0.8789 - Decision Tree - criterion='entropy' (LabelEncoder)

0.8798 - Decision Tree - criterion='entropy' (OneHotEncoder)

0.8798 - Decision Tree - criterion='entropy' (LabelEncoder + OneHotEncoder)

0.8790 - Decision Tree - criterion='entropy' (LabelEncoder + escalonamento)


0.9066 - Random Forest - n_estimators=30 ,criterion='entropy' (LabelEncoder + OneHotEncoder + escalonamento)

0.9035 - Random Forest - n_estimators=30 ,criterion='entropy' (LabelEncoder)

0.9069 - Random Forest - n_estimators=30 ,criterion='entropy' (OneHotEncoder)

0.9069 - Random Forest - n_estimators=30 ,criterion='entropy' (LabelEncoder + OneHotEncoder)

0.9029 - Random Forest - n_estimators=30 ,criterion='entropy' (LabelEncoder + escalonamento)
--------------------------------------------------------------------------------------------------------------