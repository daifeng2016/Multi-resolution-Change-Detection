
# Multi-Resolution-Change-Detection
This is a reporitory for releasing our published work [RACDNet: Resolution- and Alignment-Aware Change Detection Network for Optical Remote Sensing Imagery](https://www.mdpi.com/2072-4292/14/18/4527#cite)

## Introduction
Change detection (CD) methods work on the basis of co-registered multi-temporal images with equivalent resolutions. Due to the limitation of sensor imaging conditions and revisit period, it is difficult to acquire the desired images, especially in emergency situations. In addition, accurate multi-temporal images co-registration is largely limited by vast object changes and matching algorithms. To this end, a resolution- and alignment-aware change detection network (RACDNet) is proposed for multi-resolution optical remote-sensing imagery CD. In the first stage, to generate high-quality bi-temporal images, a light-weighted super-resolution network is proposed by fully considering the construction difficulty of different regions, which facilitates to detailed information recovery. Adversarial loss and perceptual loss are further adopted to improve the visual quality. In the second stage, deformable convolution units are embedded in a novel Siamese&ndash;UNet architecture for bi-temporal deep features alignment; thus, robust difference features can be generated for change information extraction. We further use an atrous convolution module to enlarge the receptive field, and an attention module to bridge the semantic gap between the encoder and decoder. To verify the effectiveness of our RACDNet, a novel multi-resolution change detection dataset (MRCDD) is created by using Google Earth. The quantitative and qualitative experimental results demonstrate that our RACDNet is capable of enhancing the details of the reconstructed images significantly, and the performance of CD surpasses other state-of-the-art methods by a large margin.

## Flowchart

<img width="2830" alt="Graphical abstract" src="https://user-images.githubusercontent.com/20106991/189487580-eb100662-69e5-4fbb-a152-58cffd9b47ab.png">

## Results
![image](https://user-images.githubusercontent.com/20106991/189487806-1bafd89b-077c-4b7f-8189-4146f537809e.png)


## Datasets
The datastes have been uploaded onto Baidu Netdisk, which are available at [MRCDD](https://pan.baidu.com/s/1g0KyuHQZ7FQzVDSuUMKPXQ)  Password：cnx8

## Citation
Please cite our paper if you find it is useful for your research.
```
@Article{rs14184527,
AUTHOR = {Tian, Juan and Peng, Daifeng and Guan, Haiyan and Ding, Haiyong},
TITLE = {RACDNet: Resolution- and Alignment-Aware Change Detection Network for Optical Remote Sensing Imagery},
JOURNAL = {Remote Sensing},
VOLUME = {14},
YEAR = {2022},
NUMBER = {18},
ARTICLE-NUMBER = {4527},
URL = {https://www.mdpi.com/2072-4292/14/18/4527},
ISSN = {2072-4292},
DOI = {10.3390/rs14184527}
}
```
