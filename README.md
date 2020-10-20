# FrModel
face recognition model
step1: datagathering.py will click the images and saves into a dataset folder
step2: training.py will make our model to train on images that we have provided in the datset and create a .yml file which has weights of images
step3: faceRecognition.py uses the .yml file created in the previous step 
  it takes two steps first detects whether there is a face or not once the face is detected
  it tries to match with the trained model weight and display the label which is nothing but the name of the person
