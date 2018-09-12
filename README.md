# Preprocessed ABIDE Dataset

## ABIDE Dataset Description

ABIDE(Autism Brain Imaging Data Exchange) Dataset 1 contains 1112 dataset, including 539 from individuals with ASD and 573 from typical controls (ages 7-64 years, median 14.7 years across groups).

### Acquisition protocol
- Resting state fMRI (R-fMRI)
- Anatomical dataset
- phenotypic dataset

### Scanning Location
- involving 17 international sites

### Dataset Reference
For more detailed information and download, please refer to [the official website of ABIDE project](http://fcon_1000.projects.nitrc.org/indi/abide/)

## Preprocessing
The T1 MRI data were used and preprocessed to generate normalised brain volume maps. The grey matter (GM) and white matter (WM) images were analyzed together.

### Steps

1. AC-PC Realignment
2. GM, WM Tissue Segmentation
3. Non-linear registration to MNI152 space
4. Normalization
5. Resampling
6. modulation
7. 4mm Smoothing

### Results
The result, normalized brain volume map, has shape of 121x145x121. Each voxel in the volume map represent regional volume of tissue.
 
### Software Environment
All images were pre-processed using [SPM12](https://www.fil.ion.ucl.ac.uk/spm/software/spm12/) in the MATLAB R2018a environment. [DARTEL](http://www.neurometrika.org/node/34) which is one of the SPM extension was used for normalization, non-linear registeration, resampling, modulation and smoothing step.

### Preprocessing Reference
We followed the protocol from the paper ["Predicting brain age with deep learning from raw imaging data results in a reliable and heritable biomarker"](https://scholar.google.co.kr/scholar?hl=en&as_sdt=0%2C5&q=Predicting+brain+age+with+deep+learning+from+raw+imaging+data+results+in+a+reliable+and+heritable+biomarker&btnG=) by James H. Cole et al. For the very detailed preprocessing tutorial of Voxel-based Morphometry(VBM), see [here](https://www.fil.ion.ucl.ac.uk/~john/misc/VBMclass15.pdf)

## Download
Before we upload the preprocessed data to the Server of XAI Center, we can access to the dataset through this [temporary link](http://gofile.me/3UYTa/4ws1AWG4z)

## Acknowledgement

<img src="http://xai.unist.ac.kr/static/img/logos/XAIC_logo.png" width="300" height="100">

### **Project Name**
> A machine learning and statistical inference framework for explainable artificial intelligence(의사결정 이유를 설명할 수 있는 인간 수준의 학습·추론 프레임워크 개발)

### **Managed by**
> Ministry of Science and ICT/XAIC

### **Participated Affiliation**
> UNIST, Korea Univ., Yonsei Univ., KAIST., AItrics

### **Web Site**
> <http://openXai.org>
