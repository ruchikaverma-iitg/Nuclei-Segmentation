# Nuclei-Segmentation
This repository contains an implementation of Mask-RCNN algorithm using [Matterport library](https://github.com/matterport/Mask_RCNN)
for nuclei segmentation from whole slide images of tissue sections. 

Description: Nuclei segmentation using Mask-RCNN based on the ResNet 50 backbone.

This model was trained using data from our IEEE TMI paper and [MoNuSeg challenge] (https://monuseg.grand-challenge.org/).

Please cite the following paper and our MoNuSeg (https://monuseg.grand-challenge.org/) challenge if you use this code-

N. Kumar, R. Verma, S. Sharma, S. Bhargava, A. Vahadane and A. Sethi, "A Dataset and a Technique for Generalized Nuclear Segmentation for Computational Pathology," in IEEE Transactions on Medical Imaging, vol. 36, no. 7, pp. 1550-1560, July 2017

Feel free to use weights of my trained model from [here](https://drive.google.com/open?id=16oPaebQnZCMzEsEGvhSVPMvEhbKJPATQ) and segmentation of nuclei from WSI could be done using [my testing code](https://github.com/ruchikaverma-iitg/Nuclei-Segmentation/blob/master/ru_nuc_seg.ipynb)
