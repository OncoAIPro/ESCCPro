# ESCCPro for prognosis of esophageal cancer outcome

[![standard-readme compliant](https://img.shields.io/badge/Readme-standard-brightgreen.svg?style=flat-square)](https://github.com/JD910/ESLN/blob/main/README.md)
![](https://img.shields.io/badge/Pytorch-1.7.1-brightgreen.svg?style=flat-square)

ESCCPro provides surgery and postoperative adjuvant chemotherapy advice for patients with locally advanced esophageal squamous cell carcinoma to improve clinical management.

*main.py:* Includes the entry function of ESCCPro and the code for training and validation.  

  > input_dir_train: The path where your training dataset is stored.
  > 
  > input_dir_test: The path where your test dataset is stored.
  > 

*HDF5_read.py:* Defines the function of  PET/CT image reading.

  > train_data: The input for ESCCPro. Examples of the input images are presented in Fig. S1 below.
  > 
  > target_data: The label for training and test.
  > 
  > keys[index]: The name of each image.


*nets folder:* The definition of the ESCCPro network.

*utils folder:* Necessary functions used in the ESCCPro.

 
<div align=left><img width="1000" height="370" src="https://github.com/OncoAIPro/ESCCPro/blob/main/utils/Seg_Examples.jpg"/></div><br />

**Fig. S1. Examples of the input PET/CT images of ESCCPro. R1, R2, and R3 represent the manual segmentation from three radiologists.**<br />
