==========================
Breast-Cancer-Histology-Classification-using-deep-learning-and-Fuzzy-Ensembling
==========================

Our solution for [ICIAR 2018 Grand Challenge dataset on BreAst Cancer Histology images](https://iciar2018-challenge.grand-challenge.org/)

In the present work, we have proposed an approach for breast cancer image classification,implemented using Tensorflow and Keras, which at first uses five fine-tuned, pre-trained deep learning models for classification breast cancer histology im-ages. Then a fuzzy ensemble approach is introduced where the confidencescores of the five models are fused using Choquet integral, Coalition game theory and Information theory. The dataset used for evaluating the proposed model is the ICIAR 2018 Grand Challenge on Breast Cancer Histology (popularly known as BACH) images.  We have considered both 2-class (Malignant and Benign) and 4-class (Benign, In-situ carcinoma,Invasive carcinoma, and Normal tissue). To the best of our knowledge,our experimental results outperform many state-of-the-art methods.


.. contents::
- Team members
- Reference Paper
- Overview
- Data
- Method
- Results
- Dependencies

## Team Members

- Subhankar Sen  [LinkedIn](https://www.linkedin.com/in/subhankar-sen-a62457190lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BP2gUaNhAT0uL2etYJDiGqw%3D%3D) 
- Pratik Bhowal  [LinkedIn](https://www.linkedin.com/in/pratik-bhowal-1066aa198?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B%2BqgwqwxJRIep5K454MTQ6w%3D%3D)
- Ram Sarkar  [LinkedIn](https://www.linkedin.com/in/ram-sarkar-0ba8a758?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BvwKX%2Frm5RNSySsSaIQTiVQ%3D%3D)    , [Google Scholar](https://scholar.google.com/citations?hl=en&user=bDj0BUEAAAAJ&view_op=list_works&citft=1&citft=2&citft=3&email_for_op=subhankarsen2001%40gmail.com&gmla=AJsN-F5CKj5MB0jIcLJssFUKVVcxdf5jt8CBMbzSZf6W9RJvYUYp61X3OC6sXa_lzg1FHW7A8BpuLWwkMtDLWxJje2eowsNWqllMazckf90f5PsxhFZ2D1PcmhyhjJ8OT5q2-3Pc3DcwNuIj4E0s2LfWgQVOZBVVGs76xTjTPWNSKVvqBhvA-u05tkPXamKiItj8RSd_vApWN6jtmvYA9JcJ4ObPprLRFPV10T5a0A4nmrQVxyniapy6XIgng1L8D1qTtb2oFAow)
