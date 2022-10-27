>> ### Potato_Dieases_Classification


In this project, I created a convolutional neural network that can predict whether a plant is infected with a disease. I built, trained, and tested this classification model using various layers and other hyperparameters. For this project, I will be utilising Tensorflow and Keras. I began by uploading the dataset to Google Colab using Google Drive and then viewing the photos. When working with any form of dataset, normalisation is a critical step. Following that, I constructed a CNN model, which is then used to predict plant illnesses using the image supplied to the model. This model is extremely useful since it can be used by various agricultural enterprises and farmers to boost production and reduce crop waste due to illness.

Sample image data for predicting plant disease can be found in a zip file. Regarding this project, the volume plant disease is restricted to:- ['Potato_Early_blight', 'Potato_healthy', 'Potato_Late_blight']


### Create conda environment
- conda create --name  python=3.7 

###  activate the conda env and install libraries 
- conda activate deployment
- pip install -r requirements.txt 

### deactivate the enviroment
- conda deactivate 

For transfer learning, a .h5 file is produced after running the ipynb file. and then run app.py file. 
Then the following commands are entered into the terminal:
- streamlit run app.py

### output:
![1666792477297](https://user-images.githubusercontent.com/91587120/198214854-a83b4439-719c-4b77-9cd9-88490d0e588a.png)
