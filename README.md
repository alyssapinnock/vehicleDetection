# AVIDNet: Attribute-aware Vehicle Inference Detector Network
A vehicle-detection deep learning network based on the ResNet50 model, modified to classify and predict various vehicle features.

##**Model Training**
Training for the second version of the AVIDNet model will be in the "Eval-2-Version" branch, in the "ProjectTheta.ipynb" notebook.

Conduct training by running the "Model training" section of the notebook. This will run new training for the model.

**Testing AVIDNet**
In order to test the model, run the model in Jupyter Notebook and make sure to test the images included in the project files. 

**Script Explanation**
(description of what each source code does)

**Model Architecture Summary**
The model architecture is based on the ResNet50 model, with the final fully connected (FC) layer altered to output vehicle type, subtype, and color.
It includes 13 layers, with 5 linear layers, 4 ReLU activation functions, and 4 dropout layers.
