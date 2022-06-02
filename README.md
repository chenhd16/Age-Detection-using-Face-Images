# Age-Detection-using-Face-Images

## Here is a brief introduction to the project.
The project implemented EDA and age detection through machine learning and deep learning methods on face images.

The source dataset (https://drive.google.com/drive/folders/1dZhJNGmdoO1La6MOJRfUYxDZwIa-hXNX) comes from UTKFace and contains 23708 images across from age 1 to 116 with distinct genders and ethnicities. Then the images were splited into relatively balanced 7 age groups, trained and tested on 3 models: XGBoost (traditional machine learning), CNN (deep learning) and VGGFace (transfer learning). CNN finally performed best with test accuracy of 49.9%. After redo the age group split, the accuracy increased to 56.9%.
