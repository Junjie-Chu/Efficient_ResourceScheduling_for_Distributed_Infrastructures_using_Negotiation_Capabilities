# Efficient_ResourceScheduling_for_Distributed_Infrastructures_using_Negotiation_Capabilities

## Description of folders in the repository

### code
- **Generate Original requirements**  
Generate the original requirements (input of negotiation systems). There are 2 versions in the folder. They use different strategy to select the data.
- **Negotiation System**  
Different versions of negotiation systems. Also training dataset is generated and saved here.
- **ML Model Train**  
Train different ML models and save the corresponding predictions.
- **Experiments Visualization**  
Generate the plots used in the paper for better visualization.

### data
- offer_ML 
The outputs of ML models used in the folder are the final offers. Train, test and predictions are all saved here.
- score_ML  
The outputs of ML models used in the folder are the scores of final offers. Train, test and predictions are all saved here.

### models
The trained models are stored here. The names of the models are specified in the file 'v\*_ML_train.ipynb' in ***code*** folder.

### pdf
Appendix.pdf: contains all related plots which are not included in the paper.

## Insturctions of running .ipynb files
All the dependencies are included or installed in the .ipynb files. Thus there is no need to change other environment settings. To keep your system clean, it is better to create a virtual python env first. These files are easy to reproduce the results in the paper. The only thing need to do is to modify the paths of models/data/.....
