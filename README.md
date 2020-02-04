
# Prediction Analysis to Estimate Citation Count
## Abstract
Citation count is considered as a good measure in evaluating scientific
papers, in this paper, we are Analysis the estimation of citation count using three different machine learning models which are Linear Regression, Classification and Regression Tree, and Support Vector Regression. Using [Aminer](http://aminer.org/lab-datasets/citation/dblp.v10.zip) v10 as a dataset which contains eight features, among the latter, we used only four, that are, author, venue, reference and published year. And new features
as Average Cumulative Author Citation Count, Venue rank, Venue’s h5-index, Average citation count for the venue and paper age were created. We filtered the dataset in two different ways. For each case, the dataset was evaluated using the three machine learning models mentioned above and their prediction analysis in terms of R square and MAE are compared.

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required libraries before running the .ipynb file.
This project is executed on python v3.6.4

```bash
pip install jupyter
pip install scikit-learn
pip install pandas
pip install seaborn
pip install pydotplus
pip install graphviz

Configurations (with anaconda installed):
1. Windows user:
   a. conda install graphviz
   b. Add graphviz installed path (C:\Users\username\Anaconda3\Library\bin\graphviz) 
      to Control Panel > System and Security > System > System Settings > Environment Variables > Path > Edit > New
2. Ubuntu user:
   sudo apt-get install graphviz
```

### Dataset
Dataset for Case one and two after prepocessing are provided inside Data folder.
### Preprocessing
Preprocessing file is present inside "DoNotExecute" folder. Since current [Aminer](https://lfs.aminer.cn/lab-datasets/citation/dblp.v10.zip)  dataset does not contain citation count feature value. Therefore, it is not recommended to execute until Aminer v10 dataset is updated. 

### Experiments
"Case_One_Experiment.ipynp" is the complete IPython file for Case one. 

"Case_Two_Experiment.ipynp" is the complete IPython file for Case two.
