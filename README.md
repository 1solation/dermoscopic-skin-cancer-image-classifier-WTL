
# A Dermoscopic Skin Cancer Image Classifier WTL (With Transfer Learning)

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://choosealicense.com/licenses/mit/)

A dermoscopic skin cancer image classifier trained via transfer learning with MobileNet V1. This is for my BSc(Hons) Software Engineering dissertation titled “Creating A Multiclass Computer Aided Diagnosis System For Skin Cancer Using Deep Neural Networks”.

Please click the link to view the PDF version of the presentation I gave at university associated with this project: [View PDF](https://drive.google.com/file/d/1AE6dsPPpl3rtQlxJi4pyxJmrnQcDRsww/view?usp=sharing)

This repository contains a dermoscopic skin cancer image classifier - coded in Python and trained using Keras and the MobileNet V1 Convolutional Neural Network with the ImageNet dataset.

Along with the notebook of the model, there is also exploratory data analysis on the HAM10000 (Human Against Machine with 10, 000 training images) dataset located at [this repository](https://github.com/hasib-a/ham10000_exploratory_data_analysis).

The [notebook](https://github.com/hasib-a/dermoscopic-skin-cancer-image-classifier-WTL/blob/master/dermoscopic-skin-lesion-image-classifier-WTL.ipynb) walks through my steps from reading in and processing the data into Pandas Data Frames, to creating the CNN model with a learning rate annealer to finally fitting the model with final results.

The fully trained model is available (both as a h5 file and a pickle file) and has a validation accuracy of 70.57% on unseen data of dermatoscopic images of various skin cancers. The model can discern between 7 different types of skin cancers, including melanoma which is the deadliest.

The able below is for reference on the code -> skin lesion name which are on the graphs at the end of the [notebook](https://github.com/hasib-a/dermoscopic-skin-cancer-image-classifier-WTL/blob/master/dermoscopic-skin-lesion-image-classifier-WTL.ipynb).

| Lesion Name | Code |
|--|--|
|Actinic keratoses | 0 |
|Basal cell carcinoma | 1 |
|Benign keratosis | 2 |
|Dermatofibroma | 3 |
|Melanoma | 4 |
|Melanocytic nevi | 5 |
|Vascular lesion | 6 |
