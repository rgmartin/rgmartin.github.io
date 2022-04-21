# Rubert Portfolio

## [Inbound tourism in Greece: 2010 - 2020](https://github.com/rgmartin/greece_tourism_project)
* collaboration with [FrankJKB](https://github.com/FrankJKB)
* Scrapped inbound tourism information from Government Greece Tourism website.
* Implemented interactive dashboard with Dash and Plotly to show relevant tourism statistics.
* Data cleaning and feature selection with pandas.
<img src="https://github.com/rgmartin/greece_tourism_project/blob/main/dashboard_Greece.png" width="800">


## [Time series forecasting](https://github.com/rgmartin/ECSE552-HW4/blob/main/Code.ipynb)
* collaboration with [dgsmith1988](https://github.com/dgsmith1988) and [jansont](https://github.com/jansont)
* Jointly developed three deep learning architechtures for timeforecsting: Fully connected dense network, LSTM REgressor, Transformer Encoder based model
* Multivariate prediction of weather forecast values. The following image shows the LSTM model prediction and true value for pressure measurements:
<img src="https://user-images.githubusercontent.com/14916680/164512766-2d1200ca-0d37-473f-ab51-b4de24c210cf.png" width = "600">
* Evaluated each of the proposed models in terms of relevant metrics: MAPE, wMAPE, MDRAE. Results shown in the following table show that the best prediction performance is attained by the Transformer Encoder model

![image](https://user-images.githubusercontent.com/14916680/164512476-151b0c2e-5c5d-4b7f-a6e6-02207eee574f.png)


## [Audio analysis and Spoken language classification](https://github.com/rgmartin/ECSE-552-Final-Project)
* collaboration with [dgsmith1988](https://github.com/dgsmith1988), [maxsolomonhenry](https://github.com/maxsolomonhenry), [emmanuelwilson](https://github.com/emmanuelwilson) and [Achaebe](https://github.com/Achaebe) for the Final Project of McGill Deep Learning Course ECSE-552
* AutoEncoder reconstrutction of spoken language samples:

![image](https://user-images.githubusercontent.com/14916680/164515075-8b337ca4-0488-485e-a42c-74e6b202377d.png)
* Voice samples extracted from [VoxForge](http://www.voxforge.org/) and procesed with the librosa library to obtain melSpectrograms.
* Language prediction with three deep learning models commonly utilized on image analysis: ResNet50 pretrained network, AutoEncoder based model and Prototypical Network.  
* Three languages (ENglish, ESpagnol and DEutsch) were utilized in the classification task. The following figure shows the obtained confussion matrix for the case of the Prototypical network:

![image](https://user-images.githubusercontent.com/14916680/164515374-e2184ae2-31f3-43c4-a595-ac1358a02d07.png)

## [Fluids: Multiple submerged obstacles](https://github.com/rgmartin/Multiple-Obstacle-Superposer)
* Surface waves vs Jetting on a Free surface with multiple obstacles submerged underneath.
* 
![image](https://media-exp1.licdn.com/dms/image/sync/C5627AQGa97eubCnCAg/articleshare-shrink_800/0/1650562125756?e=2147483647&v=beta&t=YGhjueApKmz0hu9Vvd8Zng8TyVt_FVrx6gLfx4WSTYI)

## [Logistic Regression Classifier](https://github.com/rgmartin/1-logistic_regression_classifier)
A logistic regression classifier has been implemented in two versions: one based on the method of Loss Minimization through Gradient Descent; the other based on Likelihood Maximization through Gradient Ascent. The algorithms have been applied to two datasets: Hepatitis and Bankruptcy. Different techniques of data analysis have been applied to the data. Experiments have been conducted to determine the balance between accuracy and running time by changing the relative tolerance of the algorithms and the learning rate. Further feature engineering has been applied to the data in order to increase the obtained accuracy of the models

![image](https://media-exp1.licdn.com/dms/image/sync/C5627AQF5i639Ej6ICQ/articleshare-shrink_800/0/1650562125855?e=2147483647&v=beta&t=4lePlFZz756eq4z_Z1ENaCpw50MWJITtd1C-8irRokw)

## [Clothes price prediction](https://github.com/rgmartin/3-Clothes_price_prediction)
* This project shows an end-to-end implementation of image classification using Convolutional Neural Networks. The input data is a modified version of the FashionMNIST dataset where each image contains three articles and the sum of the prices is the label of the image. The VGG-16 structure was the most accurate amongst other types and was used to train a neural network. The learning rate, the momentum of the optimizer, the number of epochs and the batch sizes hyperparameters were tuned. The optimized values were lr = 10−2, momentum = 0:5, batch_size = 27 and n_epoch = 50 which achieved 96:7% of accuracy on the validation set.

![image](https://media-exp1.licdn.com/dms/image/sync/C5627AQGqTdYiNcmRfA/articleshare-shrink_800/0/1650562125759?e=2147483647&v=beta&t=YpFmN_vI9yXNTUtdiouHUVYnx1IAYDZgA-pLJxF_5rE)

## [subreddit posts classifier](https://github.com/rgmartin/2--Subreddit-posts-classifier)
* In this project, different Machine Learning Classifiers have been implemented to process text from Reddit and classify each post of the data. Two different Naive Bayes algorithms have been implemented from scratch. In addition, several SciKit-Learn based Machine Learning algorithms have also been used. All these implementations have been compared in terms of accuracy and running time by changing the principal hyperparameters of each one. It is concluded that the best algorithm is Logistic Regression for the given data.

![image](https://media-exp1.licdn.com/dms/image/sync/C5627AQEQvViUt0g1xw/articleshare-shrink_800/0/1650562125959?e=2147483647&v=beta&t=T_x5WpEEedZdhLcS6Uq3bu_Lvk_nvzeFRZTjbiuFnVQ)
