[![Python](https://img.shields.io/badge/Python-3.8-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-yellow?logo=scikit-learn)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Array-blue?logo=numpy&logoColor=white)](https://numpy.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Neural Networks](https://img.shields.io/badge/Neural%20Networks-ML-purple)](#)
[![Kaggle](https://img.shields.io/badge/Kaggle-Datasets-blue?logo=kaggle&logoColor=white)](https://www.kaggle.com/)

# Project description

This project aimed to develop an effective method for predicting NBA game outcomes by overcoming challenges in integrating data from diverse sources. Utilizing popular machine learning techniques such as Gaussian Naive Bayes and Artificial Neural Networks, we constructed a classification model. While our results did not achieve peak performance, they offer valuable insights for further investigation. Future studies could explore hidden dataset features like ball possession rates, substitution frequencies, and the influence of outlier players, among other potential areas. Overall, our project establishes a groundwork for exploring nuanced features within NBA datasets, paving the way for refining predictive models and enhancing our understanding of game dynamics.

# Steps to run the notebooks

1. Download the CMU dataset from http://www.cs.cmu.edu/~awm/10701/project/databasebasketball2.0.zip and keep it under the "Data" folder under root directory (./Data/)
2. Download the Kaggle data from https://www.kaggle.com/datasets/nathanlauga/nba-games and keep it under the "Kaggle data" folder under the root directory (./Kaggle data/)
3. Make sure you have numpy, sklear, pandas and matplotlib installed.
4. Run the notebooks in the sequence given in the name as #\_notebook name. For example first run 1_mergePlayerIds.ipynb then run 2_extractPlayersFromGameData.ipynb and so on.
