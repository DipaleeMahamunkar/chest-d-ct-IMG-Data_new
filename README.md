# chest-d-ct-IMG-Data_new
import dagshub
dagshub.init(repo_owner='DipaleeMahamunkar', repo_name='Dagshub_Demo_2_1_26', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)


  302f0c696ce6d953775036c268e2b1bcf4bf0902
  https://dagshub.com/DipaleeMahamunkar/Dagshub_Demo_2_1_26.mlflow
  DipaleeMahamunkar


export MLFLOW_TRACKING_URI=https://dagshub.com/DipaleeMahamunkar/Dagshub_Demo_2_1_26.mlflow

export MLFLOW_TRACKING_USERNAME=DipaleeMahamunkar

export MLFLOW_TRACKING_PASSWORD=302f0c696ce6d953775036c268e2b1bcf4bf0902

# drive data link
https://drive.google.com/file/d/1ThZkYrB1I4SyDlccsiQAkSHBE7gDEETa/view?usp=sharing