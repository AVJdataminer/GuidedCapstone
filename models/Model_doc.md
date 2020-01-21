Developed as part of step 6. of the [Data Science Method](http://bit.ly/2T6Hpp5) by [Aiden v. Johnson](breakthroughdatascience.com)

# Data Science Model Report Template
A report to provide details on a specific data science model.  

<div id="problem-identification" class="section level2">
<h2>Problem Identification</h2> 
<div id="define-the-questiongenerate-a-working-hypothesis." class="section level3">
<h3>Define the question specific to modeling activities</h3>
<div id="identify-the-modeling-project-goal." class="section level4">
<h4>Identify the modeling project Goal.</h4>
<p>e.g Predict device failures.</p>
</div>
<div id="identify-the-data-needed-and-or-available." class="section level4">
<h4>Identify the data needed and or available.</h4>
<p>e.g Daily aggregated telemetry device failure data.</p>
</div>
<div id="define-the-data-timeframe" class="section level4">
<h4>Define the data Timeframe:</h4>
<p>e.g. 01/01/2015-11/02/2015</p>
</div>
<div id="describe-the-modeling-response" class="section level4">
<h4>Describe the Modeling Response:</h4>
<p>e.g. Binary, 0 or 1, non-failure = 0, failure = 1</p>
</div>
<div id="classification-or-regression-model" class="section level4">
<h4>Classification or Regression Model:</h4>
<p>e.g. Classification</p>
</div>
<div id="what-deliverables-will-be-generated" class="section level4">
<h4>What Deliverables will be generated:</h4>
<p>e.g.PDF outlining modeling process from data exploration to best model results.</p> . 
   
## Data Preprocessing steps of note  
    * e.g. dropped duplicate rows
    * e.g. created PCA for dimension reduction

## Model Description
* Input data size and features
* Model Algorthim and Parameters
    * Model iterations can be discussed here if they are not saved out seperately


## Model Performance
* R^2, RMSE, Confusion Matrix, Percision & Recall, AUC/ROC

## Model Understanding

* Feature Importances

## Next Steps

*  Ready for production?
*  Identify additional data sources
*  Test new hyperparameters or different modeling methods
