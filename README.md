Binary Classification model for the prediction of inhibitors for the PDK1 using python script. 

*****

After installing the requirements in an Virtual Environment
or creating a new environment using conda by using "env.yml" file
just open the command prompt or Terminal in the above created virtual environment
run the command given below
### Using Random Forest Algorithm based prediction
python predict_rf_rdkit.py test.smi

### OR 
### Using MLP Algorithm based prediction
python predict_xgb_rdkit.py test.smi

similarly, for any unknown molecule when just use the command by specifying the path
of "*.smi" file.

python predict_name_of_algorithm.py [specify_path]*.smi


The result will be displayed in the terminal as Molecule to be active or Inactive


The image in repository indicate the ROC curve of the top model and the comparitive model accuracy histogram plot.




 
