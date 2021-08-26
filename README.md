
# Fuzzy-Ensemble-of-Deep-Learning-Models-for-Breast-Cancer-Histology-Classification


<img src="https://github.com/subhankar01/Breast-Cancer-Histology-Classification-using-deep-learning-and-Fuzzy-Ensembling/blob/main/assets/cover.png" width="1000">


Our solution for [ICIAR 2018 Grand Challenge dataset on BreAst Cancer Histology images](https://iciar2018-challenge.grand-challenge.org/)

In the present work, we have proposed an approach for breast cancer image classification,implemented using Tensorflow and Keras, which at first uses five fine-tuned, pre-trained deep learning models for classification breast cancer histology im-ages. Then a fuzzy ensemble approach is introduced where the confidencescores of the five models are fused using Choquet integral, Coalition game theory and Information theory. The dataset used for evaluating the proposed model is the ICIAR 2018 Grand Challenge on Breast Cancer Histology (popularly known as BACH) images.  We have considered both 2-class (Malignant and Benign) and 4-class (Benign, In-situ carcinoma,Invasive carcinoma, and Normal tissue). To the best of our knowledge,our experimental results outperform many state-of-the-art methods.


## Table of Contents

- [Team Members](#1)
- [Reference Paper](#2)
- [Method Overview](#3)
- [Dataset](#4)
- [Results](#5)
- [Dependencies](#6)
- [Contact](#7)



## Team Members<a name="1"></a>
- Subhankar Sen  [LinkedIn](https://www.linkedin.com/in/subhankar-sen-a62457190lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BP2gUaNhAT0uL2etYJDiGqw%3D%3D) 
- Pratik Bhowal  [LinkedIn](https://www.linkedin.com/in/pratik-bhowal-1066aa198?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B%2BqgwqwxJRIep5K454MTQ6w%3D%3D)
- Prof. Juan D. Velasquez Silva,University of Chile [LinkedIn](https://www.linkedin.com/in/jdvsilva/) ,[Google Scholar](https://scholar.google.com/citations?user=2xSehG8AAAAJ&hl=es)
- Associate Prof. Ram Sarkar,Jadavpur University,Kolkata [LinkedIn](https://www.linkedin.com/in/ram-sarkar-0ba8a758?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BvwKX%2Frm5RNSySsSaIQTiVQ%3D%3D)    , [Google Scholar](https://scholar.google.com/citations?hl=en&user=bDj0BUEAAAAJ&view_op=list_works&citft=1&citft=2&citft=3&email_for_op=subhankarsen2001%40gmail.com&gmla=AJsN-F5CKj5MB0jIcLJssFUKVVcxdf5jt8CBMbzSZf6W9RJvYUYp61X3OC6sXa_lzg1FHW7A8BpuLWwkMtDLWxJje2eowsNWqllMazckf90f5PsxhFZ2D1PcmhyhjJ8OT5q2-3Pc3DcwNuIj4E0s2LfWgQVOZBVVGs76xTjTPWNSKVvqBhvA-u05tkPXamKiItj8RSd_vApWN6jtmvYA9JcJ4ObPprLRFPV10T5a0A4nmrQVxyniapy6XIgng1L8D1qTtb2oFAow)


## Reference Paper<a name="2"></a>
If you find this work useful for your publications, please consider citing:
```
```
## Method Overview<a name="3"></a>

## Fig 1:<a name="8"></a>

<img src="https://github.com/subhankar01/Breast-Cancer-Histology-Classification-using-deep-learning-and-Fuzzy-Ensembling/blob/main/assets/VGG19.png" width="750">

## Fig 2:Flowchart of the proposed method<a name="9"></a>

<img src="https://github.com/subhankar01/Breast-Cancer-Histology-Classification-using-deep-learning-and-Fuzzy-Ensembling/blob/main/assets/Method%20Flowchart.png" width="500">

## Dataset<a name="4"></a>
Click to access the [BACH dataset](https://iciar2018-challenge.grand-challenge.org/Dataset/)
<img src="https://github.com/subhankar01/Breast-Cancer-Histology-Classification-using-deep-learning-and-Fuzzy-Ensembling/blob/main/assets/images.PNG" width="750">
Examples of microscopic biopsy images in the dataset: (A) normal; (B) benign; (C) in situ carcinoma; and (D) invasive carcinoma

### Table 1: Dataset Overview<a name="10"></a>
<img src="https://github.com/subhankar01/Breast-Cancer-Histology-Classification-using-deep-learning-and-Fuzzy-Ensembling/blob/main/assets/dataset.png" width="500">


## Results<a name="5"></a>

### Table 2: Results of 2-class classification<a name="11"></a>
| Classifier/Ensemble | Validation Accuracy |Test Accuracy |
| ------------- | ------------- | ------------- | 
| VGG16  | 100  |89|
| VGG19  | 99.8  |94|
| Xception| 100 | 95|
| Inception V3|100|94|
| InceptionResnetV2| 99.7| 93|
|**Ensemble**|**-**|**96**|


### Table 3: Results of 4-class classification<a name="12"></a>
| Classifier/Ensemble | Validation Accuracy |Test Accuracy |
| ------------- | ------------- | ------------- | 
| VGG16  | 97  |86|
| VGG19  | 98  |83|
| Xception| 99 | 91|
| Inception V3|99|90|
| InceptionResnetV2| 99| 91|
|**Ensemble**|**-**|**95**|

## Dependencies<a name="6"></a>
- [Python3](https://www.python.org/)
- [Tensorflow](https://www.tensorflow.org/)
- [Keras](https://keras.io/)
- [OpenCV](https://opencv-python-tutroals.readthedocs.io/en/latest/index.html#)

## Contact<a name="7"></a>

In case of doubt or further collaboration, feel free to email us ! 😊
- [Subhankar Sen (subhankarsen2001@gmail.com) ](mailto:subhankarsen2001@gmail.com)
- [Pratik Bhowal (pratikbhowal1999@gmail.com)](mailto:pratikbhowal1999@gmail.com)



