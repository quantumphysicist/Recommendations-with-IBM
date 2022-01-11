### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
Anaconda distribution of Python 3.0. 

## Project Motivation<a name="motivation"></a>

I want to show that we can take data regarding the articles users have interacted with on the IBM Watson Studio platform to make article recommendations.

## File Descriptions <a name="files"></a>
README.md  
Recommendations_with_IBM.html (An html version of the jupyter notebook)  
Recommendations_with_IBM.ipynb (**This jupyter notebook is the main document**)  
project_tests.py (Functions to test that the jupyter notebook is giving the expected answers)  
top_10.p (pickled data to test notebook functions)  
top_20.p (pickled data to test notebook functions)  
top_5.p (pickled data to test notebook functions)  
user_item_matrix.p (pickled data to test notebook functions)  

-- data  
|- aricles_community.csv  (data that is analysed)       
|- user-item-interactions.csv  (data that is analysed)      
  

### Key file: `Recommendations_with_IBM.ipynb`
The jupyter notebook is in four parts.  
1) Exploratory Data Analysis  
We load the csv data, clean it and explain its main features.  
2) Rank Based Recommendations  
We find the most popular articles based on the most interactions.  
3) User-User Based Collaborative Filtering  
We recommend articles accord to the user_id by finding other the articles that similar users have interacted with.  
6) Matrix Factorization  
We use a machine learning approach--single value decomposition (SVD)--to predict new articles a user might interact with.  


## Licensing, Authors, and Acknowledgements <a name="licensing"></a>
Thanks to Udacity for the idea for this project, for the skeleton of the jupyer notebook and to IBM for making available their data about articles on the IBM Watson Studio platform.
