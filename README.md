# Plant pathology classification


## General info
The project concerns recognition diseases on apple leaves based on their images by using Convolutional Neural Networks (CNN) algorithms. The analysis includes data analysis, data preparation and build model CNN with data augmentation and transfer learning (MobileNet V2) to recognition of leaves diseases.

The dataset comes from Kaggle competition (Plant Pathology 2020 - FGVC7) and can be found [here](https://www.kaggle.com/c/plant-pathology-2020-fgvc7/data).

## Motivation
The aim of thr project is recognition diseases of apple leaves. Based on apple leaf photos we have tried accurately assess its health. We have four types of categories corresponding to different leaves like  healthy, those which are infected with apple rust, apple scab and with more than one disease. In our analysis we have build model to distinguish between leaves which are healthy from those with diseases and we used Convolutional Neural Networks algorithm to get more accurate predictions. In the second approach we have used transfer learning with MobileNet V2 model. 

## Project includes:
- plant classification with CNN model - **Plant_pathology_classification.ipynb**
- plant classification with transfer learning - **plant_tf.ipynb**

## Technologies

The project is created with:

- Python 3.8
- libraries: tensorflow, keras, scikit-learn, pandas, numpy, seaborn, pillow, OpenCV, imbalanced-learn.

**Running the project:**
 
To run this project use Jupyter Notebook or Google Colab.

### References:
- [Image Classification Model using Python and Keras](https://www.analyticsvidhya.com/blog/2020/10/create-image-classification-model-python-keras/)
- [How to Train MobileNetV2 On a Custom Dataset](https://blog.roboflow.com/how-to-train-mobilenetv2-on-a-custom-dataset/)
