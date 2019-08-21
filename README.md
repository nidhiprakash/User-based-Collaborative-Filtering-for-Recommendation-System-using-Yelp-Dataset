# User-based-Collaborative-Filtering-for-Recommendation-System-using-Yelp-Dataset
Recommender systems are a relatively new technology that is commonly being used by e-commerce websites and streaming services among others, to predict user opinion about products. Using the Yelp Challenge Dataset and using User-Based Collaborative filtering algorithm, our system would evaluate the similarity metrics using the Pearson correlation coefficient and use records in the training set (train.csv) to predict the stars/ratings for users and businesses in the testing set (test.csv.) using weighted sum of other users’ ratings. Further, using the stars/ratings in testing data as the ground truth we evaluate the accuracy of our recommendation system using Root mean square error (RMSE) values that are calculated. Using the results of the project, one could build a recommendation system that could analyze the results to recommend to the businesses which particular set of users it should target for more profits.


User-based Collaborative Filtering for Recommendation System using Yelp Dataset

Dependencies
•	Python 3
•	pySpark
•	Jupyter Notebook

Steps to install dependencies

Install pySpark:
To install Spark, make sure you have Java 8 or higher installed on your computer. Then, visit the Spark downloads page. Select the latest Spark release, a prebuilt package for Hadoop, and download it directly.

Unzip it and move it to your /opt folder:

$ tar -xzf spark-1.2.0-bin-hadoop2.4.tgz
$ mv spark-1.2.0-bin-hadoop2.4 /opt/spark-1.2.0

Create a symbolic link:

$ ln -s /opt/spark-1.2.0 /opt/spark̀

Install Jupyter notebook:

$ pip install jupyter

Update PySpark driver environment variables: add these lines to your ~/.bashrc (or ~/.zshrc) file.

export PYSPARK_DRIVER_PYTHON=jupyter
export PYSPARK_DRIVER_PYTHON_OPTS='notebook'


Running the program
-	Make sure train_review.csv and test_review.csv files are in the same directory as colFilter.ipynb
-	Open colFilter.ipynb in Jupyter Notebooks / Anaconda.
-	Under the Menu select Kernel and select Restart & Run All.
