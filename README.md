# Identifying-Dog-Breed
Creates Convolution Neural Networks (CNN) to classify different dog breeds. The image dataset comes from Stanford University's Dogs dataset, found here: http://vision.stanford.edu/aditya86/ImageNetDogs/
The images and their associated annotations were utilized to ensure that the most clean version of the images was utiized in the analysis. 

Image Pre-Processing & EDA : Python notebook crops all the images data using the bounding box information found from the annoations. In cases where multiple dogs are in a single image, the images are cropped so that each dog is a separate image. Additional information about the number of images in each class is also provided. Further, the dataset is split into training/validation datasets with an 80/20 split. 

Model_Scratch : Python notebook that contains the first CNN model run where the model was trained from scratch only using the training dataset created. 

Model_InceptionV3 : Python notebook that contains the CNN model that was trained using the InceptionV3 pre-trained model (transfer learning), includes the resulting model performance metrics. 

Model_Xception-Initial : Python notebook that contains the CNN model that was trained using the Xception pre-trained model (transfer learning), include the resulting model performance metrics. 

Model_Xception-Final : Python notebook that contains the CNN model that was trained using the Xception pre-trained model (transfer learning) along with dropout normalization, include the resulting model performance metrics. 
