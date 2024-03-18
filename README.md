# Deep Learning Project 
In this repository, I share my codes for the DL Course of the SUT EE department. The Project goal is to get familiar with Multi-Modal Dataset Classification. The dataset samples are movie scenes, their corresponding dialogues and emotion tags as output. Our work includes 4 phases described below:  
Phase 0 is data pre-processing and face extraction from images.  
Phase 1 is classifying based on faces and CNN models.  
Phase 2 is classifying based on dialogue using NLP tools.  
Phase 3 is to mix the results of image and text processing.
## Datasets
In this project, the MSCTD dataset is used, You can find extra information in their [Paper](https://arxiv.org/abs/2202.13645) and download the dataset from [Github](https://github.com/XL2248/MSCTD).


## Requirement
- `python==3.10.0`
- `torch==1.13.0`
- `torchvision==0.14.0`
- `torchtext==0.14.0`
- `pycm==4.0.0`
- `scipy==1.9.3`
- `sklearn==1.1.3`
- `opencv==4.6.0.`
- `nltk==3.8.1`
