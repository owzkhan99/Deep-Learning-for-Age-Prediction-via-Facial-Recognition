# Deep-Learning-for-Age-Prediction-via-Facial-Recognition
This project is intended to train a deep learning model on images of faces to determine whether customers at a retail location are old enough to purchase alcohol.

The project files are intentionally left out of the repository due the large size of the JPG Faces file.

The overview of the project results can be found in the Jupyter Notebook file.

The requirements.txt file displays the necessary library and package versions needed for pushing the code to github.

The following libraries and packages are used in this project:

pandas as pd
numpy as np
tensorflow as tf
seaborn as sns
matplotlib.pyplot as plt
tensorflow.keras.preprocessing.image import ImageDataGenerator
tensorflow.keras.applications.resnet import ResNet50
tensorflow.keras.models import Sequential
tensorflow.keras.layers import GlobalAveragePooling2D, Dense
tensorflow.keras.optimizers import Adam
tensorflow.keras.callbacks import ReduceLROnPlateau, EarlyStopping
This Jupyter notebook works on web based applications and locally. Simply open the "ComputerVision.ipynb" file.

EDA and file exploration using ImageDataGen:
![image](https://github.com/user-attachments/assets/ffb1f5b3-daa0-461d-884e-4a9ac1e278cd)


Conclusions
This model was successful in achieving a Mean Absolute Error (MAE) lower than our target threshold of 8. Specifically, the model achieved a test MAE of 6.6419. This impressive result highlights the model's accuracy and reliability in predicting outcomes with minimal error.

The MAE indicates that the model's predictions are consistently close to the actual values, showcasing its ability to effectively capture the underlying patterns in the data.

Overall, achieving a test MAE of 6.5182 was impressive considering the size of the dataset and techniques used to limit the computational usage in model training.
