<h1> Titanic - Logistic Regression  </h1>

<h2>Description</h2>
The goal of this Dataset prediction, from Titanic, is to build a model that can accurately classify new passengers as either 'survivors' or 'non-survivors' based on their attributes.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python Libraries(see first photo ref)</b> 
- <b>Titanic Dataset</b>

<h2>Platform </h2>

- <b>Jupiter notebook</b> (21H2)

<h2>Titanic project walk-through(See files attached):</h2>

<p align="center">
Importing Libraries : <br/>
<img src="https://github.com/fa-laurena/Logistic-Regression-ML/blob/d5845caef74b4bdeaaf0a3cb1b2f71182f3d7a4a/Libraries.png"  height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Data Evaluation and Cleaning : <br/>
<img src="https://github.com/fa-laurena/Logistic-Regression-ML/blob/d5845caef74b4bdeaaf0a3cb1b2f71182f3d7a4a/Data%20Evaluation%20and%20cleaning.png"80%" alt="Disk Sanitization Steps"/>
<br />
countplot -Survived- Graphic Information: <br/>
<img src="https://github.com/fa-laurena/Logistic-Regression-ML/blob/d5845caef74b4bdeaaf0a3cb1b2f71182f3d7a4a/Countplot%20Survived.png"  height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Heatmap Graphic  : <br/>
<img src="https://github.com/fa-laurena/Logistic-Regression-ML/blob/d5845caef74b4bdeaaf0a3cb1b2f71182f3d7a4a/Heatmap%20Base.png"80%" alt="Disk Sanitization Steps"/>
<br />
Heatmap Cleaning Fill Avg : <br/>
 <img src="https://github.com/fa-laurena/Logistic-Regression-ML/blob/d5845caef74b4bdeaaf0a3cb1b2f71182f3d7a4a/Avg%20age.png"80%" alt="Disk Sanitization Steps"/>
<br />
Heatmap Cleaning Fill Avg : <br/>
<img src="https://github.com/fa-laurena/Logistic-Regression-ML/blob/d5845caef74b4bdeaaf0a3cb1b2f71182f3d7a4a/Cleaning%20Avg%20age%20fill.png"  height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Heatmap Cleaning Drop Cabin : <br/>
 <img src="https://github.com/fa-laurena/Logistic-Regression-ML/blob/d5845caef74b4bdeaaf0a3cb1b2f71182f3d7a4a/Data%20Evaluation%20and%20cleaning%20cabindrop.png"80%" alt="Disk Sanitization Steps"/>
<br />
Heatmap Cleaning Drop Cabin : <br/>
 <img src="https://github.com/fa-laurena/Logistic-Regression-ML/blob/d5845caef74b4bdeaaf0a3cb1b2f71182f3d7a4a/Cleaning%20drop.png"80%" alt="Disk Sanitization Steps"/>
<br />
 <br/>
 Initiating and Training : <br/>
<img src="https://github.com/fa-laurena/Logistic-Regression-ML/blob/d5845caef74b4bdeaaf0a3cb1b2f71182f3d7a4a/initiating%20and%20training.png"  height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Model Initiation  : <br/>
<img src="https://github.com/fa-laurena/Logistic-Regression-ML/blob/d5845caef74b4bdeaaf0a3cb1b2f71182f3d7a4a/model%20selection.png"80%" alt="Disk Sanitization Steps"/>
<br />
Predictions : <br/>
<img src="https://github.com/fa-laurena/Logistic-Regression-ML/blob/d5845caef74b4bdeaaf0a3cb1b2f71182f3d7a4a/Prediction.png"80%" alt="Disk Sanitization Steps"/>
<br />
 Predictions: <br/>
<img src="https://github.com/fa-laurena/Logistic-Regression-ML/blob/d5845caef74b4bdeaaf0a3cb1b2f71182f3d7a4a/Predictions.png"  height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Model Evauation : <br/>
<img src="https://github.com/fa-laurena/Logistic-Regression-ML/blob/d5845caef74b4bdeaaf0a3cb1b2f71182f3d7a4a/Model%20evaluation.png"80%" alt="Disk Sanitization Steps"/>
<br />

 <h2>Summary</h2>
Interpretation of the Model's Performance(Logistic Regression) -GREAT-

The model is fairly accurate (81%), meaning it correctly predicts survival in most cases.
It correctly identifies non-survivors (TN = 146) but still misses 21 actual survivors (FN).
When it predicts "survivor", it is correct 70% of the time (precision for class 1).
The model could be improved by reducing false negatives (FN) to better detect survivors.
Optimisation possible with advanced modelssuch as Random Forest, XGBoost, or an ensemble of models for better performance.
Type 0 = Non-Survivors
Type 1 = Survivors
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
