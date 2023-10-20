# Weak Segmentation-Guided GAN for Realistic Color Edition

![Alt text](https://github.com/VincentAuriau/wsg-gan-color-edition/blob/main/illustrations/header.jpg)
Paper presented at ICIAP 2023

## Abstract
Editing the color of images in a realistic way finds many applications such as changing the perception of an image, data augmentation or film post processing. The design of an automatic tool is a complex and long addressed challenge. In particular, two properties are difficult to meet altogether: generating realistic results without artifacts and the possibility to precisely choose the future color. Conventional methods using segmentation and histogram matching maximize the controllability but also introduce a lack of realism or are complex to automate. On the contrary, GANs that specialize in realism are difficult to control. To overcome these challenges, we propose a novel GAN architecture leveraging any differentiable segmentation model. We demonstrate the genericness of our framework that presents state of the art results on different use cases. It generates images that look realistic while offering a precise color control.

## Appendix

Appendix file can be found at [here](https://github.com/VincentAuriau/wsg-gan-color-edition/blob/main/pdf_files/appendix.pdf) and paper full version [here](https://www.researchgate.net/publication/373664662_Weak_Segmentation-Guided_GAN_for_Realistic_Color_Edition).


## Citation 

If you find this work useful, please cite our [paper](https://link.springer.com/chapter/10.1007/978-3-031-43148-7_41):

```
@InProceedings{10.1007/978-3-031-43148-7_41,
author="Auriau, Vincent and Malherbe, Emmanuel and Perrot, Matthieu",
editor="Foresti, Gian Luca and Fusiello, Andrea and Hancock, Edwin",
title="Weak Segmentation-Guided GAN for Realistic Color Edition",
booktitle="Image Analysis and Processing -- ICIAP 2023",
year="2023",
publisher="Springer Nature Switzerland",
address="Cham",
pages="487--499",
}

```
