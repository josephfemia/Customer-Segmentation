# Customer-Segmentation
Utilize PCA and Clustering to segment a customer base

This notebook aims to walk someone through unsupervised learning methods such as PCA and Clustering as well as feature engineering. This notebook utilizes customer spending csv provided by the [UCI Machine Learning Repo](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers). We go through and analyze the dataset by observing the distribution of the feature variables and what can be done to potentially make the distribution more friendly. After, we analyze the dataset for outliers and remove them from the dataset to prevent any significant skewing in our clustering. We then utilize PCA to reduce our dimensionality down to 2 dimensions from our original 6 dimensions. Then we try to cluster the customer spending with a few different cluster sizes and pick our best performing cluster based on silhouette score. Finally, we look at the center's for our cluster to try and understand what our cluster segments may potentially be. Further deatils of the actions that were taken and why they were taken is provided by the comments within each of the cells of the notebook. I also tried to make the code as user friendly as possible. If you have any questions feel free to open any issues, I will tend to them as soon as I see them. Thank you!!

## How to install and run the notebook
This project was made using [Pipenv](https://github.com/pypa/pipenv) for keeping track of dependencies. First you must have Pipenv installed:
```
pip install pipenv
```
After having Pipenv installed, you should create a virutalenv for the project. To do this, cd into the directory and run the command:
```
pipenv shell
```
Finally, to install the necessary dependencies run:
```
pipenv install
```
By calling ```pipenv install``` you install all of the necessary dependencies within the Pipfile.lock.

All that is needed to run the notebook now is just run the command below and check oyur browser instance for a new Jupyter Notebook tab:
```
jupyter notebook
```
