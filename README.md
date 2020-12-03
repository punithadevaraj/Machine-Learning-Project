# Machine-Learning-Project

This project is done as part of CS7313 Machine learning and Pattern Recognition Course.

## Abstract

The catastrophic outbreak of Severe Acute Respiratory Syndrome - Coronavirus (SARS-CoV-2) also known as COVID-2019 has brought the worldwide threat to the living society. It first appeared in Wuhan City of China in December 2019, spread rapidly around the world and evolved into a pandemic. The artificial intelligence researchers are focusing their expertise knowledge to develop mathematical models for analyzing this epidemic situation using nationwide shared data. Application of Artificial Intelligence coupled with radiology imaging can be helpful for the accurate detection of the disease and also to invaluable to overcome the problem of lack of physicians in remote areas. In this study, we propose a deep learning model to identify COVID-19 using the patient’s chest X-ray images. We used transfer learning to tune the pre-trained ResNet-50 model, to maximize the overall **accuracy to 91.95%** whereas the **existing DarkCovidNet-17 multiclassification model has 87.02%**. This shows the potential for transfer learning and deep neural networks to distinguish amongst normal, pneumonia, and COVID-19 using chest X-rays. This helps to ease the pressure off traditional PCR diagnostic tests, while the further implementation could use deep learning for diagnostic radiology.

The reference paper is cited here https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7187882/

## DATASET

In this study, dataset consisting of  X-ray images obtained from two different sources were used for the diagnosis of COVID-19. 

- First is from (Cohen JP (2020) COVID-19 image data collection. A COVID-19 X-ray image database was developed by Cohen JP(https://github.com/ieee8023/covid-chestxray-dataset) using images from various open access sources. This database is constantly updated with images shared by researchers from different regions. At present, there are 127 X-ray images diagnosed with COVID-19 in the database. Below figure shows a few COVID-19 cases obtained from the database and the findings of the experts.

<div align="center">
    <img src="Picture1.png" width="400px"</img> 
</div>

- Second dataset for pneumonia and normal chest X-rays were gathered from the NIH Clinical Center (X. Wang et al., 2017)(https://openaccess.thecvf.com/content_cvpr_2017/papers/Wang_ChestX-ray8_Hospital-Scale_Chest_CVPR_2017_paper.pdf). We focused on pneumonia X-rays from the NIH dataset based on prior research that suggests that many COVID-19 patients develop pneumonia (CDC, 2020). The NIH dataset consists of 16,756 images, but due to computational limitations when training our model, we have randomly chosen 1360 normal and 1360 pneumonia images. The existing reference paper of Dark Net has only 500 normal and 500 pneumonia cases. We preferred choosing more images to train the model efficiently as well as with more data.

## INSTALLATION

* Anaconda Navigator - Then launch Jupyter Notebook to code
* We have trained the model using GPU from google colab. So the uploaded file is colab file.
* Create your own virtual environment. Follow the below link for set up
``` https://docs.anaconda.com/anaconda/navigator/getting-started/ ```
* Install the libraries.
    - Python version 3.6 and above
    - Keras
    - Tensorflow 2.0.0 and above
    - Numpy
    - Pandas
    - Seaborn
    - sklearn
    - Matplotlib
    - OpenCV
    - pickle



