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
Improper disposal of solid wastes could lead to disruptive effects that impact daily human lives. Waste management serves a great importance especially to the health of human lives. 
</p>
<p style="text-align:justify">
To contribute to the effort in solid waste segregation, we created a machine learning model that could classify the trash images into two categories, namely: biodegradable and non-biodegradable. Trash images is inputted to the pre-trained Mask R-CNN where the output segmented images are categorized in a classification machine learning model. For the trash classification machine learning model, Xception model achieved the highest validation accuracy of <b>92.61%</b>. 
</p>
<p style="text-align:justify">  
The resulting classification is fed back to the pre-trained Mask R-CNN for it to output the bounding box of the object and its classification. This model was implemented on both input image and video which will serve a great help to industrial waste management facilities.
</p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/xdwPYAzhl7M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

References:
- The World Bank: Trends in Solid Waste Management. Online; accessed 20 January 2021.
https://datatopics.worldbank.org/what-a-waste/trends_in_solid_waste_management.html.
- Bharadwaj, A., Yadav, D., Varshney, S.: Non-biodegradable waste-its impact &safe disposal. Int. J. Adv. Technol. Eng. Sci 3(1) (2015).
- Fractal Machine-Vision Research Group: Mask R-CNN Unmasked. Online; accessed 24 January 2021.
https://medium.com/@fractaldle/mask-r-cnn-unmasked-c029aa2f1296.
