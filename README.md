# Course "Business Analytics: Technologies, Methods, and Concepts"

This repository contains scripts related to the course tought at Friedrich-Alexander-University Erlangen-Nuremberg. Course participants can access other learning resources via [StudOn](https://www.studon.fau.de/studon/goto.php?target=crs_5706293).

Instructor: [Dr. Konstantin Hopf](https://www.uni-bamberg.de/eesys/team/konstantin-hopf/)

## Plan of the tutorial

| Session | Content | Notebooks |
|---------|---------|-----------|
| T01 | Python overview (variables, data types, operators, lists) | `1_Python_Introduction.ipynb` |
| T02 | Python program flow (loops, conditionals, functions) | `1_Python_Introduction.ipynb` |
|     | Pandas library intro | `2_Pandas.ipynb` |
| T03 | Pandas (cont'd)      | `2_Pandas.ipynb` |
| T04 | Data visualization | `3_data_visualization.ipynb` | 
| T05 | Linear regression | `5_Classification_LinearModels.ipynb` |
| T06 | Decision tree classifier | `6_Decision_Trees.ipynb` |
| T07 | Classifier evaluation | `7_Classifier_evaluation.ipynb` |

## List of Python functionalities used in this course

This list contains functions, methods, attributes, and classes that you should be familiar with after attending the course “Business Analytics”


### General functions for many classes (not all classes)
* len
* print
* type
* range
* & (and operator)
* | (or operator)
* ~ (not operator)
* ‘+’, ‘-’, ‘*’, ‘/’, ‘%’ 
* ‘+=’, ‘-=’, ‘*=’, ‘/=’ 
* ‘==’, ‘!=’, ‘>’, ‘<’, ‘>=’, ‘<=’ 

### Class ‘list’
* append
* extend
* remove
* insert

### Class ‘np.array’
* np.add
* np.multiply
* np.dot
* np.random
* np.sum
* np.mean
* np.median
* np.std
* np.max
* np.min
* np.argmax
* np.argmin
* np.transpose
* np.sqrt
* dtype
* shape
* ‘+’, ‘-’, ‘*’, ‘/’

### Class ‘pd.DataFrame’
* read_csv
* head
* tail
* describe
* dtypes
* unique
* replace
* isnull
* drop
* dropna
* fillna
* iloc
* loc
* columns
* copy
* astype
* map
* groupby
* agg and aggr. functions ‘count’, ‘mean’, ‘max’, ‘min’
* sort_values
* cat.codes
* get_dummies
* join
* shape
* sum
* mean
* ‘+’, ‘-’, ‘*’, ‘/’
* ‘==’, ‘!=’, ‘>’, ‘<’, ‘>=’, ‘<=’
* plot.scatter
* plot.line
* plot.hist
* plot.kde
* plot.pie
* plot.box

### Class LogisticRegression, LinearRegression, DecisionTreeClassifier/Regressor, GradientBoostingClassifier/Regressor, RandomForestClassifier/Regressor (sklearn)
* fit
* predict
* predict_proba

### Class OrdinalEncoder, OneHotEncoder, CountVectorizer (sklearn)
* fit
* fit_transform

### Helper functions sklearn
* accuracy_score
* confusion_matrix
* mean_squared_error
* mean_absolute_error
* cross_val_score
* shuffle
* train_test_split
