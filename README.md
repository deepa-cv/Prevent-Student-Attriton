# Team - Cygnus
<h2> Predicting Student Assessment Marks to PreventStudent Attrition in MOOCs </h2>
<h3> The dataset has been downloaded from Kaggle:<h3>
<a href = "https://www.kaggle.com/anlgrbz/student-demographics-online-education-dataoulad">Link to the dataset</a> 

<hr> 
    
    
<h3> Required Libraries </h3>
    <li>pandas</li>
    <li>numpy</li>
    <li>matplotlib</ul>
    <li>fastparquet</li>
    <li>mlxtend</li>
    <li>sklearn</li>
    
<br>
    <p> To download python libraries </p>

```bash
pip install pandas
pip install numpy 
pip install matplotlib
pip install fastparquet
pip install mlxtend
pip install sklearn
```
     
<h3>Directions to run </h3>
    <h4><i> Step 1 - </i></h4> <p> To obtain a merged version of the files, run Merging.ipynb. 'Shift' + 'Enter' on all cells. The given notebook produces merged_paraquet.</p>   
    <h4><i> Step 2 - </i></h4>  <p> In order for preprocessing of the data, we use Preprocessing.ipynb. The given notebook produces preprocessed_parquet.</p>   
    <h4><i> Step 3 - </i></h4>  <p> To plot the graphs and draw some graphical insights, run Visualising.ipynb similarly.</p> 
    <h4><i> Step 4 - </i></h4>  <p> Once preprocessed, we shall get to building the models. For building the models, we have to segregate the targets ie. score values to ten classes. We further label encode the classes. This is stored in classification_parquet. 
    <h4><i> Step 5 - </i></h4>  <p> Now we get to building our classifiers. <br>
                          To run the model on XGBoost, run Classification_models_XGBoost.ipynb <br>
                          To run the model the Adaboost, run adaboostmodel.ipynb <br>
                          To run the model the LightGBM model and Random Forests model, run LightGBM_and_Random_Forest.ipynb <br> </p>
         
     
         
  
