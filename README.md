# RandomForest_python
* This script provides implementation example of RandomForestClassifiler in scikit-learn library.  
* You can tune the hyperparameter and perform 10-closs validation.

GridSearch_10models.ipynb:
* generate 10 train-test set
* tune hyperparameter using grid search

RF_10models.ipynb:
* 10-fold closs validation, output results as;
	* accuracy
	* feature importance
	* class probability
	* confusion matrix

## Requirement
These codes created using by python language and save as Jupyter Notebook style.
It is suitable to open this script via Jupyter Notebook or JupyterLab.
#### Required python library:
* scikit-learn
* numpy
* pandas
* matplotlib

## Usage
* Create a working directory folder at an arbitrary location. *Multiple output files are generated in the working directory.  
* "sampledataset.txt" is an example file for import. If you do not have your own data, use this file. File structure; The first column is the spectral name, the second column is the class name, and the third and subsequent columns are the features.

#### Open the script "GridSearch_10models.ipynb"
* Change "sampledatase.txt" in `df = pd.read_table('sampledatase.txt')` to the name of the import file.  
* The value of `search_params` can be any numerical value of the parameter you wish to check.

#### Open the script "RF_10models.ipynb".
* Set the value of the hyperparameter determined by the grid search into `clf = RandomForestClassifier()`.  

#### "simple_script.ipynb"
Data is simply split into test and training data sets.  
This is for Random Forest beginners. 

## Examples
![exapmle](https://github.com/nkanno4n3a/RandomForest_python_test/blob/main/image/figure1.png)

## License
MIT License  
Copyright (c) 2022 Nanako Kanno

## Related articles
Original:   
[N. Kanno, S. Kato, M. Ohkuma, M. Matsui, W. Iwasaki, S. Shigeto. (2021) Machine learning-assisted single-cell Raman fingerprinting for in situ and nondestructive classification of prokaryotes. iScience 24(9):102975](https://doi.org/10.1016/j.isci.2021.102975)