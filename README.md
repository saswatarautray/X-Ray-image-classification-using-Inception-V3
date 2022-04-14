# X-Ray-image-classification-using-Inception-V3

- The dataset can be found here: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia 
- According to the World Health Organization (WHO), pneumonia kills about 2 million children under 5 years old every year and is consistently estimated as the single leading cause of childhood mortality , killing more children than HIV/AIDS, malaria, and measles combined. 
- The WHO reports that nearly all cases (95%) of new-onset childhood clinical pneumonia occur in developing countries, particularly in Southeast Asia and Africa. - ---- Bacterial and viral pathogens are the two leading causes of pneumonia but require very different forms of management. Bacterial pneumonia requires urgent referral for immediate antibiotic treatment, while viral pneumonia is treated with supportive care. Therefore, accurate and timely diagnosis is imperative. 
- One key element of diagnosis is radiographic data, since chest X-rays are routinely obtained as standard of care and can help differentiate between different types of pneumonia. However, rapid radiologic interpretation of images is not always available, particularly in the low-resource settings where childhood pneumonia has the highest incidence and highest rates of mortality. To this end, it is beneficial to investigate the effectiveness of a transfer-learning-based image classification framework in classifying pediatric chest X-rays to detect pneumonia.

---
Read more about such deep learning based medical diagnosis applications in this paper: 
- [Identifying Medical Diagnoses and Treatable Diseases by Image-Based Deep Learning - https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5 
- Transfer learning with Inception-V3 model - Inception V3 was the 1st Runner Up for image classification in ILSVRC ([ImageNet Large Scale Visual Recognition Competition] (http://www.image-net.org/challenges/LSVRC/)) 2015.

---


- The Inception deep convolutional architecture was introduced as GoogLeNet in ([Szegedy et al. 2015a] (https://www.cs.unc.edu/~wliu/papers/GoogLeNet.pdf)), here named Inception-V1. Later the Inception architecture was refined in various ways, first by the introduction of batch normalization ([Ioffe and Szegedy 2015] (http://proceedings.mlr.press/v37/ioffe15.pdf)) (Inception-V2). Later by additional factorization ideas in the third iteration ([Szegedy et al. 2015b] (https://www.cv-
foundation.org/openaccess/content_cvpr_2016/papers/Szegedy_Rethinking_the_Inception_CVPR_2016_paper.pdf)) which will be referred to as Inception-V3.

Read this article to know more about this model.https://medium.com/@sh.tsang/review-inception-v3-1st-runner-up-image-classification-in-ilsvrc-2015-17915421f77c 
---


Tasks:
1) How many samples are present? Print number of images for NORMAL & PNEUMONIA in 
training, validation and test images (1 pt)
2) Can you tell the difference between normal and pathological examples? Visualize them by 
considering 4-5 samples each (1 pt)
3) Load Imagenet pretrained InceptionV3 model (1 pt) 
4) Add Pooling and densely connected layers to InceptionV3 and print the model summary (2 pt)
5) Train the model and display the loss/accuracy plot (3 pt)
6) Check the accuracy on the test images (2 pt)
