# Rubert Portfolio




1. [Data science and Machine Learning Projects](#data-science)
2. [Fluid dynamics](#fluids)
3. [Nuclear engineering](#nuclear)
4. [Physics projects](#physics)


## Data science and Machine Learning Projects <a name="data-science"></a>

### [Inbound tourism in Greece: 2010 - 2020](https://github.com/rgmartin/greece_tourism_project)
* collaboration with [FrankJKB](https://github.com/FrankJKB)
* Scrapped inbound tourism information from Government Greece Tourism website.
* Implemented interactive dashboard with Dash and Plotly to show relevant tourism statistics.
* Data cleaning and feature selection with pandas.
<img src="https://github.com/rgmartin/greece_tourism_project/blob/main/dashboard_Greece.png" width="800">


### [Time series forecasting](https://github.com/rgmartin/ECSE552-HW4/blob/main/Code.ipynb)
* collaboration with [dgsmith1988](https://github.com/dgsmith1988) and [jansont](https://github.com/jansont)
* Jointly developed three deep learning architechtures for timeforecsting: Fully connected dense network, LSTM REgressor, Transformer Encoder based model
* Multivariate prediction of weather forecast values. The following image shows the LSTM model prediction and true value for pressure measurements:
<img src="https://user-images.githubusercontent.com/14916680/164512766-2d1200ca-0d37-473f-ab51-b4de24c210cf.png" width = "600">
* Evaluated each of the proposed models in terms of relevant metrics: MAPE, wMAPE, MDRAE. Results shown in the following table show that the best prediction performance is attained by the Transformer Encoder model

![image](https://user-images.githubusercontent.com/14916680/164512476-151b0c2e-5c5d-4b7f-a6e6-02207eee574f.png)


### [Audio analysis and Spoken language classification](https://github.com/rgmartin/ECSE-552-Final-Project)
* collaboration with [dgsmith1988](https://github.com/dgsmith1988), [maxsolomonhenry](https://github.com/maxsolomonhenry), [emmanuelwilson](https://github.com/emmanuelwilson) and [Achaebe](https://github.com/Achaebe) for the Final Project of McGill Deep Learning Course ECSE-552
* AutoEncoder reconstrutction of spoken language samples:

![image](https://user-images.githubusercontent.com/14916680/164515075-8b337ca4-0488-485e-a42c-74e6b202377d.png)
* Voice samples extracted from [VoxForge](http://www.voxforge.org/) and procesed with the librosa library to obtain melSpectrograms.
* Language prediction with three deep learning models commonly utilized on image analysis: ResNet50 pretrained network, AutoEncoder based model and Prototypical Network.  
* Three languages (ENglish, ESpagnol and DEutsch) were utilized in the classification task. The following figure shows the obtained confussion matrix for the case of the Prototypical network:

![image](https://user-images.githubusercontent.com/14916680/164515374-e2184ae2-31f3-43c4-a595-ac1358a02d07.png)



### [Logistic Regression Classifier](https://github.com/rgmartin/1-logistic_regression_classifier)
A logistic regression classifier has been implemented in two versions: one based on the method of Loss Minimization through Gradient Descent; the other based on Likelihood Maximization through Gradient Ascent. The algorithms have been applied to two datasets: Hepatitis and Bankruptcy. Different techniques of data analysis have been applied to the data. Experiments have been conducted to determine the balance between accuracy and running time by changing the relative tolerance of the algorithms and the learning rate. Further feature engineering has been applied to the data in order to increase the obtained accuracy of the models

![image](https://media-exp1.licdn.com/dms/image/sync/C5627AQF5i639Ej6ICQ/articleshare-shrink_800/0/1650562125855?e=2147483647&v=beta&t=4lePlFZz756eq4z_Z1ENaCpw50MWJITtd1C-8irRokw)

### [Clothes price prediction](https://github.com/rgmartin/3-Clothes_price_prediction)
* This project shows an end-to-end implementation of image classification using Convolutional Neural Networks. The input data is a modified version of the FashionMNIST dataset where each image contains three articles and the sum of the prices is the label of the image. The VGG-16 structure was the most accurate amongst other types and was used to train a neural network. The learning rate, the momentum of the optimizer, the number of epochs and the batch sizes hyperparameters were tuned. The optimized values were lr = 10−2, momentum = 0:5, batch_size = 27 and n_epoch = 50 which achieved 96:7% of accuracy on the validation set.


![image](https://media-exp1.licdn.com/dms/image/sync/C5627AQGqTdYiNcmRfA/articleshare-shrink_800/0/1650562125759?e=2147483647&v=beta&t=YpFmN_vI9yXNTUtdiouHUVYnx1IAYDZgA-pLJxF_5rE)

### [subreddit posts classifier](https://github.com/rgmartin/2--Subreddit-posts-classifier)
* In this project, different Machine Learning Classifiers have been implemented to process text from Reddit and classify each post of the data. Two different Naive Bayes algorithms have been implemented from scratch. In addition, several SciKit-Learn based Machine Learning algorithms have also been used. All these implementations have been compared in terms of accuracy and running time by changing the principal hyperparameters of each one. It is concluded that the best algorithm is Logistic Regression for the given data.

* The following figure shows the confussion matrix obtained for the classification process:

![image](https://media-exp1.licdn.com/dms/image/sync/C5627AQEQvViUt0g1xw/articleshare-shrink_800/0/1650562125959?e=2147483647&v=beta&t=T_x5WpEEedZdhLcS6Uq3bu_Lvk_nvzeFRZTjbiuFnVQ)

## Fluid dynamics projects  <a name="fluids"></a>

### [Fluids: Multiple submerged obstacles](https://github.com/rgmartin/Multiple-Obstacle-Superposer)
* Surface waves vs Jetting on a Free surface with multiple obstacles submerged underneath.
* Classification phase map with decision boundary between two fluid regimes: Jetting and Gravity Waves.


![image](https://media-exp1.licdn.com/dms/image/sync/C5627AQGa97eubCnCAg/articleshare-shrink_800/0/1650562125756?e=2147483647&v=beta&t=YGhjueApKmz0hu9Vvd8Zng8TyVt_FVrx6gLfx4WSTYI)

## Nuclear engineering projects  <a name="nuclear"></a>

### [Neutronic - thermal coupling in a real-time nuclear reactor simulator. (2017)](https://github.com/rgmartin/real_time_coupling)

[Final report](https://github.com/rgmartin/real_time_coupling/blob/main/Documentaci%C3%B3n/ClassicThesis.pdf)

This work presents the characterization and analysis of calculation neutronic library PUMITA, aimed to model the neutronic behavior of nuclear reactor CAREM-25
core. This library will be coupled to the plant analysis code RELAP as the nuclear
reactor core model for the Graphical Interactive Simulator aimed at training the
future operators of CAREM-25. Thereby is essential for a thorough characterization of the library, to include studies and characterization of the abovementioned
coupling as well

Schematic of time stepping strategy for neutronic-thermal coupling

![image](https://user-images.githubusercontent.com/14916680/165780931-4c64b527-e192-4b19-9378-9605d6f947b8.png)


Hexagonal and triangular geometries of core mesh:

![image](https://user-images.githubusercontent.com/14916680/165781184-5290b701-8e00-492e-956b-dd837d55c451.png)



### [Coupling between  neutronic code CITVAP and thermal code RELAP for a nuclear reactor (2016)](https://github.com/rgmartin/neutronic-thermal-coupling)

[Final report](https://github.com/rgmartin/neutronic-thermal-coupling/blob/main/Tesis%20Acople%20Rubert.pdf)

A coupling method between neutronic code CITVAP and thermal code RELAP is developed for stationary states of the core of a nuclear reactor. Programs relap2citvap
y citvap2relap are developed to allow for the information flow between the two codes. The proper functioning of the coupling is validated against experimental data from Australian reactor OPAL. In particular the feedback coefficient is computed, and compared against the measured experimental value. A good agreement between the numerical and experimental values is observed.

Power distribution - OPAL reactor:

![](https://github.com/rgmartin/neutronic-thermal-coupling/blob/main/3_MOdeloArtisticoRELAP.jpg)


## Physics projects <a name="physics"></a>

###  [Electronic Turing Machine (2012)](https://github.com/rgmartin/Electronic-Turing-Machine)
<a href="https://github.com/rgmartin/Electronic-Turing-Machine/blob/main/La%20Maquina%20de%20Turing.pdf" target="_top">Final Report (in Spanish)</a>


Turing Machine is a mathematical model designed to study the limits of computability. This work discusses the physical principles on which this model is based and its viability. In particular, an implementation of an electronic circuit that simulates a Turing Machine is desrcibed in this work.
This work was submitted to the XXIX Students Scientific Workshop of the Faculty of Physics of the University of Havana, held on May 16 and 17, 2013.

Preview of the electronic circuit:

![](https://github.com/rgmartin/Electronic-Turing-Machine/blob/main/circuits/general.jpg)

### [Cluster Algorithms (2013)](https://github.com/rgmartin/cluster-algorithms)

Metropolis Algorithm (Monte Carlo) has a critical delay when used for simulating the Ising Model near Curie Temperatures (Tc = 2.23K). This work studies the causes of this delay and the main computational algorithms that have been developed to avoid it. Comparisons between different Cluster Algorithms are presented, and against the classical Metropolis Algorithm. Both Swendesn-Wang and Wolff algorithms prove to be more efficient near Tc temperatures than Metropolis.

