# Pytorch implementation of X-vectors embedding

This repository is using [https://github.com/SiddGururani/Pytorch-TDNN](https://github.com/SiddGururani/Pytorch-TDNN) repo with few adaptation, including one that allows to stack few TDNN layers sequentially 


# Files

[TDNN_gpu.py](https://github.com/Dannynis/xvector_pytorch/blob/master/TDNN_gpu.py "TDNN_gpu.py")
##TDNN layers implementation, Stats pooling and final layers implementation ##
[total_model](https://github.com/Dannynis/xvector_pytorch/blob/master/total_model "total_model")
The pretrained network that was trained on speechs of Trump, Lady Gaga, Macron and Hillary Clinton##
[xvector - gpu.ipynb](https://github.com/Dannynis/xvector_pytorch/blob/master/xvector%20-%20gpu.ipynb "xvector - gpu.ipynb")
Jupyter notebook for the network training ##
[xvector_ext_and_lda_scatter.ipynb](https://github.com/Dannynis/xvector_pytorch/blob/master/xvector_ext_and_lda_scatter.ipynb "xvector_ext_and_lda_scatter.ipynb")
Notebook that extracts X-vectors on new utterances and via LDA reduces thier dimensions and plots them in 2D and 3D

Xvectors 3d scatter of the trained speakers and new unseen speaker - Andrew_ng
![lda-3dim-with-andrew.png](https://github.com/Dannynis/xvector_pytorch/blob/master/lda-3dim-with-andrew.png?raw=true) 

