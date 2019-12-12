# AIMI: Artifial Intelligence Melanoma Identifier
AIMI aims to classify skin lesions in seven classes.

This project was undertaken as part of the AI Saturdays sessions on machine learning & deep learning that took place in Madrid in 2019.

The goal of this project is to learn about different frameworks and models of deep learning, in particular CNN (Convolutional Neural Networks) for image classification.


## Dataset

Cases include a representative collection of all important diagnostic categories in the realm of pigmented lesions: 
* actinic keratoses and intraepithelial carcinoma Bowen's disease (akiec)
* basal cell carcinoma (bcc)
* benign keratosis-like lesions (solar lentigines seborrheic keratoses and lichen-planus like keratoses, bkl)
* dermatofibroma (df)
* melanoma (mel)
* melanocytic nevi (nv) 
* vascular lesions (angiomas, angiokeratomas, pyogenic granulomas and hemorrhage, vasc)

This dataset was obtained from a large collection of multi-source dermatoscopic images of pigmented lesions:

[Skin Cancer MNIST: HAM10000](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000) - Kaggle dataset


## Methodology

We have used different frameworks and models in order to compare the efficiency of the predictions.

Using CNN we have been able to predict between 7 classes of skin lesions thanks to the transfer learning method, combining this technique with data augmentation we have trained our models and get some metrics that help us to evaluate these models.

### Frameworks

* **Tensorflow/Keras**: high-level API for building and training deep learning models
* **Fast.ai**: deep learning library to provide a single consistent interface to all the most commonly used deep learning applications for vision, text, tabular data, time series, and collaborative filtering

### Models

* MobileNet
* ResNet18
* ResNet34
* ResNet50

### Files

* **Model_CNN:** Tensorflow/Keras approach
* **fastai-model-noTest:** first approach to the fastai model with ImageDataBunch and no test set
* **fastai-model:** fastai model with DataBunch created from ImageList and test set

## Next Steps

- Create a dataframe to check test prediction accuracy
- Improve the model so we can get better predictions (mainly on melanomas)
- Data equalization
- Web App for uploading images and get predictions


## Authors

* [Alberto Cuesta Parejo](https://www.linkedin.com/in/alberto-cuesta-parejo/)
* [Claudia Pérez Casas](https://www.linkedin.com/in/claudia-p%C3%A9rez-casas/) 
* [Javier Cruz del Valle](https://www.youtube.com/watch?v=oHg5SJYRHA0) 
* [Mercedes Riveira Martín](https://www.linkedin.com/in/mercedes-riveira-martin/)




