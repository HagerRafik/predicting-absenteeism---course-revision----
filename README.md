# predicting_absenteeism
predecting the absenteeism rate for employees using collected employees' features
![features](https://user-images.githubusercontent.com/77872656/203224277-04370863-fa28-4052-8f74-49d4167d878e.PNG)

## steps:
### 1- preprocessing 
- starting with 'preprocessing.ipynb' notebook :
> 1- uploaded the "Absenteeism_data.csv" file <br>
> 2- investigating the data <br>
> 3- working with one column at a time. <br>
> 4- fixing errors noticed in the column and preprocessing it to the next phase ML <br>
> 5- creating dummy variables <br>
> 4- storing the final result in 'df_preprocessed_2.csv' <br>

### 2- ML
- starting with 'ML.ipynb' notebook :
> 1- uploading the 'df_preprocessed_2.csv' file <br>
> 2- preparing the target column <br>
> 3- standardizing the data<br>
> 4- Splitting and shuffling<br>
> 5- performing logistic regression <br>
> 6- training the model <br>
> 7- interpreting results <br>
> 8- testing the model accuracy <br> 
> 9- creating a model file and scale file <br>

### 3- predicting new data, connecting Jupiter to MySQL
-  starting with 'absenteeism_predicted_outputs.ipynb' notebook :
> 1- uploading the 'Absenteeism_new_data.csv' file <br>
> 2- importing the module, and using it to predict the Absenteeism ratio for the new data <br>
> 3- connecting to MySQL <br>
> 4- storing the predicted data in a MySQL database <br>

### 4- visualizing the findings using Tableau
> https://public.tableau.com/views/absenteeism_predictions_1/Story1?:language=en-US&:display_count=n&:origin=viz_share_link
