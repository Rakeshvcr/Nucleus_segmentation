# Nucleus Segmentation

The nucleus is an organelle found in most eukaryotic cells, The primary functions of the nucleus are to store the cell’s DNA, maintain its integrity, and facilitate its transcription and replication. The researcher found a connection between the shape of the nucleus and human disease states such as cancer. The size and shape of the nucleus of a cancer cell are often abnormal. Typically, the nucleus of a cancer cell is larger and darker than that of a normal cell and its size can vary greatly. Methods for assessing nuclear size and shape typically involve identifying the nucleus via traditional image segmentation approaches. Here we demonstrate a deep learning approach for the identification and segmentation of nuclei from images of cells.

## U-Net Model 

In U-Net there are a large number of feature channels in the upsampling part, which allow the network to propagate context information to higher resolution layers. As a consequence, the expansive path is more or less symmetric to the contracting part, and yields a u-shaped architecture.

<img src="https://github.com/Rakeshvcr/Nucleus_segmentation/blob/master/images/u-net-architecture.png" width="700">

## Data
Get Nucleus data [Here](https://drive.google.com/file/d/1BdIovcY9NzwXhP146u98xcXRp_ZqO-zv) 

## Result

<img src="https://github.com/Rakeshvcr/Nucleus_segmentation/blob/master/images/Image.png" width="550" height="200"> 

## Reference

1. To know more about U-Net model. [Here](https://arxiv.org/pdf/1505.04597.pdf)
2. To know more about Nucleus [Refere](https://www.cancer.org/treatment/understanding-your-diagnosis/tests/testing-biopsy-and-cytology-specimens-for-cancer/what-doctors-look-for.html)
3. Keras implementation. <https://www.kaggle.com/keegil/keras-u-net-starter-lb-0-277>
