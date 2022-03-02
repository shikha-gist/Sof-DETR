# Sof-DETR
This repository contains PyTorch implemetation of the paper "Improving Small Objects Detection using Transformer" \
If you find our paper or provided codes helpful in your research, then please do not forget to cite our paper. Thank you! \
The following architecture represents our proposed model Sof-DETR for Object Detection. 

![alt text](https://github.com/shikha-gist/Sof-DETR/blob/main/model/sof-detr-model.JPG)

## Requirements
<pre>
-python 3.8.8  
-pytorch 1.8.1
-torchvision  0.9.1
-numpy 1.18.5
-cudatoolkit 11.1.74
-scipy 1.4.1
-tensorboard 2.4.0
-tensorflow-gpu 2.3.0
-requests 2.24.0
</pre>

## Testing
We have provided the Jupyter Notebooks for better visualization of the predicted class and bounding boxes and classes.\ 
Our jupyter notebooks also display the self-attention maps and decoder feature maps.\
Two Jupyter Notebooks are provided :
1. test_sof-detr.ipynb
2. sof-detr_attention.ipynb




## Sof-DETR Evaluation on MSCOCO Detection Dataset 2017  (val set)
Model |AP-all | AP-50| AP-75 | AP-Small | AP-Medium | AP-Large 
--- | --- | --- | --- |--- |--- |--- 
SOF-DETR (Resnet-50) | 42.7 | 61.8 | 45.4 | 21.7 | 45.9 | 61.5

## Sof-DETR Online Evaluation on MSCOCO Detection Dataset 2017  (test-dev set)
Model |AP-all | AP-50| AP-75 | AP-Small | AP-Medium | AP-Large | AR-max=1 | AR-max=10| AR-max=100 | AR-Small | AR-Medium | AR-Large 
--- | --- | --- | --- |--- |--- |--- | --- | --- | --- | --- |--- |--- 
SOF-DETR (Resnet-50) | 43.0 | 62.0 | 46.0 | 21.0 | 46.0 | 59.0  | 34.0 | 55.0 | 59.0  | 32.0 | 64.0  | 81.0 



## Citation
Please cite the following BibTex: 

If you find the paper and this repository helpful, please consider citing our paper [Sof-DETR](https://www.techrxiv.org/articles/preprint/Improving_Small_Objects_Detection_using_Transformer/16921000). Thank you!


## License
This project is licensed under Machine Learning & Vision Laboratory (MLV Lab), GIST. 


## Acknowledgments
We would like to thanks [facebookresearch](https://github.com/facebookresearch/detr) team.

