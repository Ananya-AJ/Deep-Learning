
Regularization_abcdfg : demonstrates a) l1 l2

b) dropout

c) earlystop

d) montecarlo dropout

f) batch norm

g) custsom dropout, custom regularization

Initialisations_e : demonstrates initialisations for regularisation techniques

j_keras_cv_dataaugmentation : demonstrates cv augmentation using keras

i - uses hyper parameter search space to select important features using keras tuner and trains model. The colab demonstrates the accuracy in predicting before and after keras tuner.

k_claasification_document uses newspaper20 dataset to test the accuracy in prediction on pre and post augmentation on dataset. uses nlpaug package for augmentation.

k_classification_audio uses dog and cat audio files and tests accuracy of classification on pre and post augmentation of data. data is augmented using augly package.

k_classification_video uses brush_hair videos and shoot_gun videos from hmdb51_org dataset and tests the accuracy of the model on pre and post data augmentation performed on videos using augly[video]

k_classification_timeseries consists of daily minimum temperatures in Melbourne, Australia from 1981 to 1990, uses tsaug to augment the timeseries data and evaluates the model accuracy pre and post augmentation, classification on forecasting low/high temperatures.

k_classification_image uses dog vs cat images for classification and uses ImageDataGenerator to augment the images.

k_classification_tabulardata uses credit card dataset to classify default or not default. Uses random noise injection for data augmentation.

k_classification_text uses nlpaug for data augmentation on imdb dataset , augments data by replacing words with their synonyms and trains the model.

l_fastai_dataaugmentations : demonstrates various data augmentations using fast ai capabilities
