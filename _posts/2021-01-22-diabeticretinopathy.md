---
title: "Wall-E Upgrade: A Trash Classifier using Convolutional Neural Networks"
date: 2021-01-22
tags: [data science, machine Learning, neural networks, computer vision, waste segregation]
header:
excerpt: "by Kisko Apeles, Abel Cruzada, Leonard Limkaichong, and Queenie Mendez"
mathjax: "true"
---
by Kisko Apeles, Abel Cruzada, Leonard Limkaichong, and Queenie Mendez

![png](/images/trash_classifier.png)

<p style="text-align:justify">
Improper disposal of solid wastes could lead to disruptive effects that impact daily human lives. Waste management serves a great importance especially to the health of human lives. To contribute to the effort in solid waste segregation, we created a machine learning model that could classify the trash images into two categories, namely: biodegradable and non-biodegradable. Trash images is inputted to the pre-trained Mask R-CNN where the output segmented images are categorized in a classification machine learning model. For the trash classification machine learning model, Xception model achieved the highest validation accuracy of 92.61%. The resulting classification is fed back to the pre-trained Mask R-CNN for it to output the bounding box of the object and its classification. This model was implemented on both input image and video which will serve a great help to industrial waste management facilities. However, the trash should be properly spread out to reveal more information to the object detector and further improve the model’s chances of classifying the garbage correctly.

References:
- Retina International. (n.d.). _Diabetes-related Retinopathy and Diabetes-related Macular Edema Prevalence – Retina International's Diabetic Eye Disease Toolkit_. Retrieved 12 January 2021, from http://retina-ded.org/diabetic-retinopathy-and-diabetic-macular-edema/prevalence/#aboutretinainternational.
- National Eye Institute. (2019). _Diabetic Retinopathy_ Retrieved from 12 January 2021, from https://www.nei.nih.gov/learn-about-eye-health/eye-conditions-and-diseases/diabetic-retinopathy.
- W. Arevalo. (2020). _retinopathy_btgraham300_. Available at https://www.kaggle.com/willarevalo/retinopathy-btgraham300.
