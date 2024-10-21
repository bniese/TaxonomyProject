Cellpose_workflow.ipynb: takes in the raw tif files of the microscopy of the Human skin microbiome and outputs the cell masks
data_preprocessing: This takes in the cell masks and creates the Probability density functions from them. The PDFs are then linked with the taxonomy data and formated for the model creation program
model_creation.ipynb: This takes in the preprocessed data and creates the models to predict the Shannon Index and the bacteria class of the image. This script also includes the creation of the validation graphs
