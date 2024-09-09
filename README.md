# Project 2 - Online Gaming Behavior

# Purpose/Description
This poject is to explore online gaming engagment patterns and identify who is most suceptible to different levels of engagment based on their gaming profiles.

# Goals
The goal of this project was to identfy, train and  test several classification models and determine which one(s) were the best.  Optmization was done on the top two models to try and improve their accuracy.

A secondary goal of the project was to build online gaming profiles for class members who were willing to share their information and then do a prediction on their profiles.

# Overview of Data Collection and Analysis
The data set that was used was found on kagle.  [link](https://www.kaggle.com/datasets/rabieelkharoua/predict-online-gaming-behavior-dataset/code)  
The data set is free to use as per licence found [here](https://creativecommons.org/licenses/by/4.0/)

Seven different classifaction models were used: KNN,
Logistic Regression, SVM, Decision Tree, Random Forest, Gradient Boosting, and Adaboost.

Elbow diagrams were developed on KNN, Random Forest, and Gradient Boosting to better optimize each of them.  


# Results
The final presentation of results can be found in the Power Point file [here](https://github.com/LaserLon/Project2/blob/main/Project2/Project-2-Presentation.pptx).  
The two best models identified through anlysis were Random Forest and Gradient Boosting.
The following table summarizes the training and test accuracty scores as well as the difference between them, the R2, mean square, and root mean square values.

![alt text](image.png)

The second goal of the project was to evaluate users profiles by doing a predicion.  Profiles for Mike & Lonnie were developed and ran though each model.

The following table summarizes the preductions for both Mike & Lonnie.  

![alt text](image-1.png)

With the exception of Adaboost, all the models made the same predction for each person.  Both Mike & Lonnie felt that the predtions made were accurate.

# File Struction/Links

The files for this project are organized as follows:  The files in folders Mike & Lonnie are individual working files used for the analysis. Once the analysis was completed, the code was organized and put into the final project results file, [model_analysis_final.ipynb](https://github.com/LaserLon/Project2/blob/main/Project2/model_analysis_final.ipynb).


Lonnie  
&nbsp;&nbsp;&nbsp;&nbsp;[model_analysis.ipynb](https://github.com/LaserLon/Project2/blob/main/Lonnie/model_analysis.ipynb)  
Mike  
&nbsp;&nbsp;&nbsp;&nbsp;[starter.ipynb](https://github.com/LaserLon/Project2/blob/main/Mike/starter.ipynb)  
&nbsp;&nbsp;&nbsp;&nbsp;[starter_organize.ipynb](https://github.com/LaserLon/Project2/blob/main/Mike/starter_organize.ipynb)  
Project2  
&nbsp;&nbsp;&nbsp;&nbsp;[model_analysis_final.ipynb](https://github.com/LaserLon/Project2/blob/main/Project2/model_analysis_final.ipynb)  
&nbsp;&nbsp;&nbsp;&nbsp;[model_analysis.ipynb](https://github.com/LaserLon/Project2/blob/main/Project2/model_analysis.ipynb)  
&nbsp;&nbsp;&nbsp;&nbsp;[Project-2-Presentation.pptx](https://github.com/LaserLon/Project2/blob/main/Project2/Project-2-Presentation.pptx)  
&nbsp;&nbsp;&nbsp;&nbsp;data:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  [online_gaming_behavior_dataset.csv](https://github.com/LaserLon/Project2/blob/main/Project2/data/online_gaming_behavior_dataset.csv)
# Conributors
Mike Saunders  
Lonnie Aldredge
