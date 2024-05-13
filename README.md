# CovidClassifier

**Data source** Unknown. 25 X-Ray COVID-19 images and 25 X-Ray non COVID-19 images

**Purpose**: The goal of this notebook is to build a covid classifier out of chest x-rays images and compare results using different models (Sklearn RandomForestClassifier and TensorFlow Keras API).

**Actions**:
1. We did a quick EDA and prepared the data for the model
2. Run RandomForestClassifier Model
3. Run 2x Multi Layer Perceptron models using TensorFlow Keras API
4. Run 1x Convolutional Neural Network using TensorFlow Keras API
5. Saving the model as .keras file

**Future work:**
- data augmentation to increase the size of the training set
- use pre-trained image classification models and mount a second model on top to achieve smoother convergence. 
- use hyperparameter fine-tuning to achieve better results.
- increase real dataset with this Kaggle repo: https://www.kaggle.com/datasets/prashant268/chest-xray-covid19-pneumonia

Libraries:
- !pip3 install imutils
- !pip3 install opencv-python
- !pip3 install scikit-image

Notebook made by: José Maria Trindade
