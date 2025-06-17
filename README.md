

# Mapping result display and comparison

- 0.6-meter MCAE-based land cover maps: [http://pubrs.com/MCAE/](http://pubrs.com/MCAE/) or [http://pubrs.com/](http://pubrs.com/) 

- 1-meter SinoLC-1 land cover maps: [http://pubrs.com/SinoLC-1/](http://pubrs.com/SinoLC-1/)

> The website bandwidth is limited. Please be patient and allow some time for the content to load.  
> Now supports both desktop and mobile browsers, and direct access via WeChat.

**MCAE**: 
![0.6-meter MCAE-based Land Cover Map](./fig/LC-MCAE.png "0.6-meter MCAE-based Land Cover Map")

**SinoLC-1**[1]:
![1-meter SinoLC-1 Land Cover Map](./fig/LC-SinoLC-1.png "1-meter SinoLC-1 Land Cover Map")

> [1] Li Z, He W, Cheng M, et al. SinoLC-1: The first 1-meter resolution national-scale land-cover map of China created with the deep learning framework and open-access data[J]. Earth System Science Data Discussions, 2023, 2023: 1-38.


# MCAE-based land cover maps with 0.6-meter resolution

Download the MCAE-based land cover map and open it directly in QGIS. The color palette has already been embedded in the land cover map:

![Open the land cover map in QGIS](./fig/disp-in-qgis.png "Open the land cover map in QGIS")

Download link for the MCAE-based land cover map (continuously updated and expanded):

Baidu Netdisk: [https://pan.baidu.com/s/1RgeegxBdV9o-NSSLaDnCDw?pwd=fjvp](https://pan.baidu.com/s/1RgeegxBdV9o-NSSLaDnCDw?pwd=fjvp), Extraction Code: fjvp

**Key Characteristics of the Land Cover Maps:**

- **High resolution and accuracy**: Overall accuracy > **85%** at **0.6-meter resolution**.  
- **Extensive geographic coverage**: Covers **five major cities in China** — **Beijing**, **Tianjin**, **Shanghai**, **Chengdu**, and **Guangzhou**.


# HiCity-LC: 0.6-meter dataset with dense+sparse mask annotations

Download link for the HiCity-LC (continuously updated):

Baidu Netdisk: [https://pan.baidu.com/s/1MgXymLIg3sYPhfC83So5IA](https://pan.baidu.com/s/1MgXymLIg3sYPhfC83So5IA)

**Key Characteristics of the Dataset:**

- **Dense Mask Annotations:**  
  The dataset contains **5,116 image-label pairs with dense mask annotations**, each with a resolution of 1024×1024 pixels at 0.6-meter spatial resolution, resulting in approximately **3.74 billion labeled pixels**.

- **Sparse Mask Annotations:**  
  It also includes **50,771 image-label pairs with sparse mask annotations**, each of the same size and resolution, totaling approximately **10.27 billion labeled pixels**.

- **Large Dataset Scale**: The combined dataset size of dense and sparse mask annotations is about **8 times** that of GID[2] and Five-Billion-Pixels[3].

- **High Representativeness and Diversity:**  
  Collected using the MCAE framework, the dataset encompasses a broad range of urban scenes across **five major Chinese cities — Beijing, Tianjin, Shanghai, Chengdu, and Guangzhou** — ensuring strong **geographical diversity and representativeness** of complex urban environments.

> [2] Tong X Y, Xia G S, Lu Q, et al. Land-cover classification with high-resolution remote sensing images using transferable deep models[J]. Remote Sensing of Environment, 2020, 237: 111322.

> [3] Tong X Y, Xia G S, Zhu X X. Enabling country-scale land cover mapping with meter-resolution satellite imagery[J]. ISPRS Journal of Photogrammetry and Remote Sensing, 2023, 196: 178-196.

**Dense annotations:**

<div align="center">
  <img src="./fig/disp-dense-ann.png" alt="Dense ann" width="80%">
</div>

**Sparse annotations:**

<div align="center">
  <img src="./fig/disp-sparse-ann.png" alt="Sparse ann" width="80%">
</div>


> ⚠️ **使用须知 / Usage Notice**  
> 如使用、引用、转载、转存以上任何数据，请标注出处。如有疑问请联系 chenhao20 [AT] whu.edu.cn。  
> Please acknowledge the source when using, citing, reproducing, or redistributing any of the above data. For inquiries, contact chenhao20 [AT] whu.edu.cn.

