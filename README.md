<h1 align='center'> Mobile Price Range Prediction</h1>
<img align='right' height ='300' src='https://media.giphy.com/media/63I6FXZTXks2A/giphy.gif'>
<h2>📱 Problem Statement</h2>
In the competitive mobile phone market
companies want to understand sales data of
mobile phones and factors which drive the
prices. The objective is to find out some
relation between features of a mobile phone
(e.g.:- RAM, Internal Memory, etc) and its
selling price. In this problem, we do not
have to predict the actual price but a price
range indicating how high the price is. <br>
<br>
The main objective of this project is to build a model which will classify the price range of mobile phones based on the specifications of
mobile phones.
<h2>📱 Data Description</h2>
Total Rows= 2000<br>
Total features=21<br>

* Battery_power - Total energy a
battery can store in one time
measured in mAh.
* Blue - Has bluetooth or not.
* Clock_speed - speed at which
microprocessor executes
instructions.
* Dual_sim - Has dual SIM support or
not.
* Fc - Front Camera mega pixels.
* Four_g - Has 4G or not.
* Int_memory - Internal Memory in
Gigabytes.
* M_dep - Mobile Depth in cm.
* Mobile_wt - Weight of mobile
phone.
* N_cores - Number of cores of
processor.
* Pc - Primary Camera mega pixels.
* Px_height and Px_width - Pixel
Resolution Height and width.
* Ram - Random Access Memory in
Mega Bytes.
* Sc_h and Sc_w - Screen Height and
width of mobile in cm.
* Talk_time - longest time that a
single battery charge will last when
you are.
Three_g - Has 3G or not.
* Touch_screen - Has touch screen or
not.
* Wifi - Has wifi or not.
* Price_range - This is the target
variable with value of 0(low
cost),1(medium cost),2(high cost)
and3(very high cost)

<h2>📱 Algorithms Used</h2>

We experimented with various models
such as

* Decision Tree Classifier
* SVM
* Random Forest Classifier
* Gradient Boosting Classifier
* XGBoost Classifier
* KNN
<h2>📱 Conclusion</h2>
Implemented various classification
algorithms,out of which the SVM (Support
vector machine) algorithm gave the best
performance after hyper-parameter tuning
with 98.3% train accuracy and 97 % test
accuracy. <br>
<br>
In all of these models our accuracy revolves
in the range of 70 to 74%.
<br>
<br>
KNN gave very worst model performance.
We checked for the feature importances of
each model. RAM, Battery Power,
Px_height and px_widthcontributed the most
while predicting the price range.
