# Polish_companies_Bankruptcy

Mini machine learning project playing with feature and model selection

Data Source: [UCI](http://archive.ics.uci.edu/ml/datasets/Polish+companies+bankruptcy+data#)

### What this project does

Variety factors can lead to failure in business performance. Detecting the pattern from the financial report can help detecting potential bankruptcy companies and provide timely consultant. My project is an exploration of the Polish companies Bankruptcy data, applies some models to find out which one can provide the best prediction of bankruptcy.

### How to run the analysis from beginning to end

1. First, download the data from this [link](http://archive.ics.uci.edu/ml/datasets/Polish+companies+bankruptcy+data#) of **UCI**
2. After download and unzip the file, choose the 3year.arff file as the data file only. This data contains financial rates from 3rd year of the forecasting period and corresponding class label that indicates bankruptcy status after 3 years. The data contains 10503 instances (financial statements), 495 represents bankrupted companies, 10008 firms that did not bankrupt in the forecasting period. 
   -  If you want to choose other year, it's okay, but the datafile name in the jupyter notebook should be changed accordingly.
3. Run the jupyter notebooks in the `src` (source) folder:
   - read_file.ipynb - to load the file, clean up and do some data wrangling to make a clean dataset
   - EDA.ipynb - takes in the data produced by read_file.ipynb and performs exploratory data analysis and creates a plot and two tables
   - [Model_ft_selection.ipynb](__) - takes in the data produced by read_file.ipynb and performs feature and model selection (one table and two visualizations to present these results)
4. OR you can open the [report]() in `result` folder.
5. OR you can see the whole process in the [bankruptcy_feature_selection.ipynb](link) file in the `src` folder.

### Software dependencies

- Jupyter Notebook

  Libraries:

- `scikitlearn`

- `pandas`

- `numpy`

### Report

The report could be found in [here](__) **Not Link yet**

