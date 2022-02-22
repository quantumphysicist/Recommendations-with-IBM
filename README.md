# Recommendations Engine

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
Anaconda distribution of Python 3.0. Please see requirements.txt for modules.

## Project Motivation<a name="motivation"></a>

I want to show that we can use data regarding user-article interactions on the IBM Watson Studio platform to make article recommendations.

## File Descriptions <a name="files"></a>

|-**Recommendations_with_IBM.ipynb**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(**This jupyter notebook is the key file**)  
|-Recommendations_with_IBM.html&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(An html version of the jupyter notebook)      
|-project_tests.py&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(Functions to test that the jupyter notebook is giving the expected answers) 

(The following four files are pickled data used to test notebook functions)  
|- top_10.p    
|- top_20.p   
|- top_5.p   
|- user_item_matrix.p   

— data  
|- aricles_community.csv&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(data that is analyzed)       
|- user-item-interactions.csv&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(data that is analyzed)      
  

### Key file: `Recommendations_with_IBM.ipynb`
The jupyter notebook is in four parts. 
 
I. Exploratory Data Analysis  
We load the csv data, clean it, and explain its main features. 
 
II. Rank Based Recommendations  
We find the most popular articles based on the most interactions.  

III. User-User Based Collaborative Filtering  
We recommend articles accord to the user_id by finding other articles that similar users have interacted with. 
 
IV. Matrix Factorization  
We use a machine learning approach—single value decomposition (SVD)—to predict new articles a user might interact with.  


## Licensing, Authors, and Acknowledgements <a name="licensing"></a>
Thanks to Udacity for the idea for this project, for the skeleton of the jupyter notebook, and to IBM for making available their data about articles on the IBM Watson Studio platform.
