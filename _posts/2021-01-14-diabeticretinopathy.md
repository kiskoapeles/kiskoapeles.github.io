---
title: "A. EYE.: Detecting Diabetic Retinopathy using Neural Networks on Patient Eye Images"
date: 2021-01-14
tags: [data science, big data, cloud computing, machine Learning, neural networks, medicine, computer vision]
header:
excerpt: "by Kisko Apeles, Abel Cruzada, Leonard Limkaichong, and Queenie Mendez"
mathjax: "true"
---
by Kisko Apeles, Abel Cruzada, Leonard Limkaichong, and Queenie Mendez

![png](/images/diabetic_retinopathy.png)

Diabetic Retinopathy is one of the leading causes of blindness globally. It is a complication of diabetes that causes the retina to swell and when left untreated could cause blindness and visual loss. According to Retina International, over 400 million people are living with diabetes and roughly 10% of these are at risk of blindness due to Diabetic Retinopathy. However, regular screening and early detection of diabetic retinopathy can save millions of lives from blindness. Hence, **this project aims to help detect diabetic retinopathy with the help of big data and cloud computing**.

Using over 88,000 patient eye images from Kaggle which amounted to over 90 GB of data and utilizing cloud computing using Amazon Web Services to train a classifier neural network, the following methodology was implemented:

1. Data Extraction - Various convolutional bases were used to extract image vectors from the raw images. Exploratory Data Analysis was also performed on the images.
2. Data Preprocessing - Data were split into train, validation, and test and underwent further sampling to balance data.
3. Model Selection - Base model with the highest performing convolutional base was selected for the classifier neural network.
4. Fine Tuning - Further fine tuning was done in order to increase classifier neural network model performance.
5. Analysis of Results - Evaluation of the highest performing model using different metrics was done.

The final classifier neural network model achieved a **78.89%** test accuracy on unseen data which exceeded the 71.33% heuristic chance accuracy criteria. Overall, this model can help increase the efficiency of diabetic retinopathy diagnostis. More specifically, it can help:

1. Patients and doctors in saving time and costs.
2. Save patients from blindness through early detection of diabetic retinopathy.
3. Allow doctors to focus more on treatment than diagnosis.

References:
- Retina International. (n.d.). _Diabetes-related Retinopathy and Diabetes-related Macular Edema Prevalence – Retina International's Diabetic Eye Disease Toolkit_. Retrieved 12 January 2021, from http://retina-ded.org/diabetic-retinopathy-and-diabetic-macular-edema/prevalence/#aboutretinainternational.
- National Eye Institute. (2019). _Diabetic Retinopathy_ Retrieved from 12 January 2021, from https://www.nei.nih.gov/learn-about-eye-health/eye-conditions-and-diseases/diabetic-retinopathy.
- W. Arevalo. (2020). _retinopathy_btgraham300_. Available at https://www.kaggle.com/willarevalo/retinopathy-btgraham300.
