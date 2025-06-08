

# Mapping result display and comparison

- 0.6-meter MCAE-based land cover maps: [http://pubrs.com/](http://pubrs.com/)  or [http://pubrs.com/MCAE/](http://pubrs.com/MCAE/)

- 1-meter SinoLC-1 land cover maps: [http://pubrs.com/SinoLC-1/](http://pubrs.com/SinoLC-1/)

Note: The website bandwidth is limited, please be patient and wait for the loading time to arrive.

**MCAE**: 
![0.6-meter MCAE-based Land Cover Map](./fig/LC-MCAE.png "0.6-meter MCAE-based Land Cover Map")

**SinoLC-1**:
![1-meter SinoLC-1 Land Cover Map](./fig/LC-SinoLC-1.png "1-meter SinoLC-1 Land Cover Map")

Li Z, He W, Cheng M, et al. SinoLC-1: The first 1-meter resolution national-scale land-cover map of China created with the deep learning framework and open-access data[J]. Earth System Science Data Discussions, 2023, 2023: 1-38.

# 0.6-meter MCAE-based land cover maps

Download the MCAE-based land cover map and open it directly in QGIS. The color palette has already been embedded in the land cover map:

![Open the land cover map in QGIS](./fig/disp-in-qgis.png "Open the land cover map in QGIS")

Download link for the MCAE-based land cover map (continuously updated and expanded):

Baidu Netdisk: [https://pan.baidu.com/s/1xCuxAsA7jEZBnDnxU03Gjg?pwd=x87b](https://pan.baidu.com/s/1xCuxAsA7jEZBnDnxU03Gjg?pwd=x87b), Extraction Code: x87b

**Key Characteristics of the Land Cover Maps:**

- **High resolution and accuracy**: Overall accuracy > **85%** at **0.6-meter resolution**.  
- **Extensive geographic coverage**: Covers **five major cities in China** — **Beijing**, **Tianjin**, **Shanghai**, **Chengdu**, and **Guangzhou**.


# 0.6-meter dense+sparse mask annotations

Download link for the dense mask annotations (continuously updated):

Baidu Netdisk: [https://pan.baidu.com/s/1dluzGeUcMmJqqECeKgbipQ?pwd=rgft](https://pan.baidu.com/s/1dluzGeUcMmJqqECeKgbipQ?pwd=rgft), Extraction Code: rgft

**Key Characteristics of the Dataset:**

- **(1) Large-Scale Dense Annotations:**  
  The dataset contains **5,116 image-label pairs with dense mask annotations**, each with a resolution of 1024×1024 pixels at 0.6-meter spatial resolution, resulting in approximately **3.74 billion labeled pixels**.

- **(2) Large-Scale Sparse Annotations:**  
  It also includes **50,771 image-label pairs with sparse mask annotations**, each of the same size and resolution, totaling approximately **10.27 billion labeled pixels**.

- **(3) High Representativeness and Diversity:**  
  Collected using the MCAE framework, the dataset encompasses a broad range of urban scenes across **five major Chinese cities — Beijing, Tianjin, Shanghai, Chengdu, and Guangzhou** — ensuring strong **geographical diversity and representativeness** of complex urban environments.

**Dense annotations:**
![Dense ann](./fig/disp-dense-ann.png "Dense ann")

**Sparse annotations:**
![Sparse ann](./fig/disp-sparse-ann.png "Sparse ann")
