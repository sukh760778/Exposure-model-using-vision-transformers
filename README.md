# Exposure-model-using-Transformers
This repository contains the code to process the images and train models for building a classification using Google Street View images and Vision Transformers.
## Repository Content

**Data/:** Contains representative GSV image data for each class used to train the models.

**Code/:** Jupyter notebooks for data processing and Model training.

## Different classes of buildings which the present model classifies:

| <img src="https://raw.githubusercontent.com/sukh760778/Exposure-model-using-vision-transformers/main/Data/AD_H1/31.17974255_76.98402971__5162-3.jpg " width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/Metal_Sheet/102.jpg" width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/Assam_Type/121.jpg" width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/Vacant/103.jpg" width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/RCC/103.jpg" width="200"> |
|--------------------------------|--------------------------------|--------------------------------|--------------------------------|--------------------------------|
| **AD_H1** | **AD_H2** | **METAL_H1** | **MR_H1 flat roof** | **MR_H1 gable roof** |
| <img src="https://raw.githubusercontent.com/sukh760778/Exposure_model_using_vision_transformers/main/Data/AD_H1/31.17974255_76.98402971__5162-3.jpg" width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/Assam_Type/121.jpg" width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/Vacant/103.jpg" width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/RCC/103.jpg" width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/Metal_Sheet/102.jpg" width="200"> |
| **MR_H2 flat roof** | **MR_H2 gable roof** | **MR_H3** | **NON_Building** | **RCC_H1 flat roof** |
| <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/Assam_Type/121.jpg" width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/Vacant/103.jpg" width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/RCC/103.jpg" width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/Metal_Sheet/102.jpg" width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/Assam_Type/121.jpg" width="200"> |
| **RCC_H1 gable roof** | **RCC_H2 flat roof** | **RCC_H2 gable roof** | **RCC_H3 flat roof** | **RCC_H3 gable roof** |
| <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/Vacant/103.jpg" width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/RCC/103.jpg" width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/Metal_Sheet/102.jpg" width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/Assam_Type/121.jpg" width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/Vacant/103.jpg" width="200"> |
| **RCC_H4 flat roof** | **RCC_H4 gable roof** | **RCC_H5** | **RCC_H6** | **RCC_OS_H1** |
| <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/RCC/103.jpg" width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/Metal_Sheet/102.jpg" width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/Assam_Type/121.jpg" width="200"> | <img src="https://raw.githubusercontent.com/sukh760778/Building_classification_NE_India/main/Data/Vacant/103.jpg" width="200"> | 
| **RCC_OS_H2** | **RCC_OS_H3** | **RCC_OS_H4** | **Timber** | 




#### Note: This repository shares the data for the study "Machine Learning-based Rapid Building Classification Using Street View Images and Subsequent Risk Assessment" (Under Review).

### Authors
1. Sukh Sagar Shukla
2. Amit Bhatiya
3. J Dhanya
4. Saman Ghaffarian
5. Roberto Gentile
