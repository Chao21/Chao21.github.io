---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

--------------------------------------------------
Summary: 
——————————

Starting from my Ph.D. career (2020-present), my research covers land use/cover classification, quantifying climatic effects of land use/cover change, and evaluation and validation of existing cropland datasets. Detailed work include three parts: remote sensing-based mapping of irrigated croplands in China, quantification of irrigation cooling effects on land surface temperature, and evaluation of existing high-resolution cropland datasets across China

**1. Remote Sensing-based Mapping of Irrigated Croplands in China**
------
Keywords: Irrigation, remote sensing, China, two-step strategy, Google Earth Engine

Agricultural irrigation, as an important practice to protect crops from drought and promote grain yield, has a long history in China. A timely and precise dataset about the extent and dynamics of irrigated areas is necessary for water allocation and agricultural management but is scarce in China. We produced the irrigation distribution dataset in China from 2000 to 2019 combining remote sensing and census data. 

We constructed a "two-step" strategy: 
(1) Get preliminary irrigation data set (IrriMap_Syn) using a spatial downscaling method on existing irrigation datasets and statistical data (synergy mapping);
(2) Produce the improved 500-m irrigated cropland data set (IrriMap_CN) using machine learning with the vast sample retrieved from IrriMap_Syn on Google Earth Engine. 

![](https://Chao21.github.io/images/1_Irrigation_mapping_01.png){:height="800px" width="600px"}

Conclusions: 

(1) The overall accuracy of IrriMap_CN is 0.811, with an omission error of 0.150 and commission error of 0.157, outperforming existing irrigation products.

(2) The irrigation distribution dataset shows that about 40% of the irrigated croplands spread over the North China Plain, followed by the northeast Sanjiang-Songnen-Liaohe Plain (15%) and the middle and lower reaches of the Yangtze River Plain (9%). 

(3) In the past 20 years, the irrigated area of China shows a pattern of "increasing in the north and decreasing in the south", and the irrigation area in northern China, especially the northeast, northwest, and central Inner Mongolia, expanded rapidly.

(4) The expansion and contraction of irrigated farmland have correspondingly led to the increase and decrease of agricultural water use, respectively. The increase in population and arable land and continued investment in water conservancy facilities are the main drivers of irrigation expansion.


Reference:

[1]	**Chao Zhang**, Jinwei Dong, Lijun Zuo, Quansheng Ge\*. (2022). [Tracking spatiotemporal dynamics of irrigated croplands in China from 2000 to 2019 through the synergy of remote sensing, statistics, and historical irrigation datasets.](https://doi.org/10.1016/j.agwat.2022.107458){:target="_blank"} *Agricultural Water Management* 263, 107458-107470. [Full text link](https://drive.google.com/file/d/1TIOMLW1CHXYC7GDKbNFMlfDjx--myWdP/view?usp=sharing){:target="_blank"}

[2]	**Chao Zhang**, Jinwei Dong, Quansheng Ge\*. (2022). [Mapping 20 years of irrigated croplands in China using MODIS and statistics and existing irrigation products.](https://doi.org/10.1038/s41597-022-01522-z){:target="_blank"} *Scientific Data* 9, 407-418. [Full text link](https://drive.google.com/file/d/1x3W9wo76UtWtL0n6nWClDD3cuB8maXTb/view?usp=sharing){:target="_blank"}

[3]	**Chao Zhang**, Jinwei Dong\*, Yanhua Xie, Xuezhen Zhang, Quansheng Ge\*. (2022). [Mapping irrigated croplands in China using a synergetic training sample generating method, machine learning classifier, and Google Earth Engine.](https://doi.org/10.1016/j.jag.2022.102888){:target="_blank"} *International Journal of Applied Earth Observation and Geoinformation* 112, 102888-102900. [Full text link](https://drive.google.com/file/d/1n7oDLvpawcBd2PfEeZVqfrmYvX0xFAJl/view?usp=sharing){:target="_blank"}

[4]	**Chao Zhang**, Jinwei Dong\*, Quansheng Ge\*. (2022). [IrriMap_CN: Annual irrigation maps across China in 2000–2019 based on satellite observations, environmental variables, and machine learning.](https://doi.org/10.1016/j.rse.2022.113184){:target="_blank"} *Remote Sensing of Environment* 280, 113184-113197. [Full text link](https://drive.google.com/file/d/1zdF7AY7e4va0cOEvv67R547daq-ht28t/view?usp=sharing){:target="_blank"}



**2. Quantifying irrigation cooling effects on land surface temperature**
------
In the last two decades, agricultural irrigation areas evolved rapidly in China and altered local and regional climates. However, the increasing irrigation’s climatic effects with underlying biophysical mechanisms have rarely been investigated. 

Taking the irrigated croplands from the IrriMap_CN product as the object, we analyzed the spatial, seasonal, and diurnal patterns of irrigation effect on land surface temperature (LST) with the biophysical mechanisms, using the pairwise comparison method, energy balance equation, and statistical analyses based on remote sensing derived LST, albedo and the evapotranspiration dataset. Finally, the effect of the rapid expansion of water-saving irrigation areas since the 21st century in China on the irrigation cooling effect was investigated.

![](https://Chao21.github.io/images/2_Irrigation_cooling_effect_01.png){:height="800px" width="600px"}

Conclusions:

(1) Irrigation in China’s croplands decreased daytime temperatures by 0.34 ± 0.02 K and nighttime temperatures by 0.19 ± 0.02 K, with the strongest cooling observed in arid regions, particularly during summer.

(2) Irrigation increased latent heat flux by 3.81 ± 0.22 W/m² and decreased sensible heat flux by 2.86 ± 0.26 W/m², with the cooling effect diminishing under wetter and warmer conditions.

(3) Over the past two decades, the cooling effect of irrigation weakened overall, showing a diurnal asymmetry with reduced daytime cooling (0.236 K/decade) and increased nighttime cooling (0.168 K/decade), especially in arid regions.

(4) In Xinjiang, a key region for water-saving irrigation, daytime cooling weakened by 0.21 K/decade and nighttime cooling strengthened by 0.12 K/decade, with the most pronounced changes in southern Xinjiang and late summer to early spring.



Reference: 

[1]	**Chao Zhang**, Quansheng Ge\*, Jinwei Dong, Xuezhen Zhang, Yan Li, Songjun Han. (2023). [Characterizing spatial, diurnal, and seasonal patterns of agricultural irrigation expansion-induced cooling in Northwest China from 2000 to 2020.](https://doi.org/10.1016/j.agrformet.2022.109304){:target="_blank"} *Agricultural and Forest Meteorology* 330, 109304-109317. [Full text link](https://drive.google.com/file/d/1Ope4CtJTim_FG8eqLDU-k-oW9z0HM9e6/view?usp=sharing){:target="_blank"}

[2]	**Chao Zhang**, Jinwei Dong\*, Guoyong Leng, Russell Doughty, Kun Zhang, Songjun Han, Geli Zhang, Xuezhen Zhang, Quansheng Ge\*. (2023). [Attenuated cooling effects with increasing water-saving irrigation: Satellite evidence from Xinjiang, China.](https://doi.org/10.1016/j.agrformet.2023.109397){:target="_blank"} *Agricultural and Forest Meteorology* 333, 109397-109409. [Full text link](https://drive.google.com/file/d/19VtUwVqugybOplLDFyyoOxfLVHeZk9He/view?usp=sharing){:target="_blank"}

[3]	**Chao Zhang**, Quansheng Ge\*, ..., Jinwei Dong\*. (2025). Divergent weakened cooling effects and biophysical mechanisms of water-saving irrigation in varied climate zones. (In prepare)


**3. Evaluation of six 30-m cropland datasets in China**
------

With the development of remote sensing technology, more and more fine-resolution cropland datasets have emerged as powerful tools for agriculture planning and food security evaluation. But questions about their accuracy and reliability must be answered before using them, making evaluations necessary. So far, little attention has been paid to the performance of fine-resolution (e.g., 30 m) and cropland-specific products at continental or regional scales. 

Here we implemented a comparison analysis and accuracy assessment for six cropland products with a 30-m resolution in China circa 2015, including FROM-GLC, GLC_FCS, CLCD, AGLC, GFSAD, GLAD. Their similarities and disparities were delineated at national, provincial, meridional, and zonal scales. 

![](https://Chao21.github.io/images/3_Cropland_Evaluation.png){:height="800px" width="800px"}

Conclusions:

(1) High spatial consistency among the six products was observed in the North China Plain and Northeast China, while low consistency occurred in Southern, Southwest, and Northwest China, influenced by topography such as elevation and slope.

(2) Provincially, CLCD and AGLC showed the strongest correlation with statistical data (r² > 0.9), while FROM-GLC had the lowest (r² = 0.37), with CLCD demonstrating the best area accuracy and GLC_FCS and FROM-GLC showing severe over- and underestimations, respectively.

(3) Pixel-wise validation revealed that CLCD and GLAD had the highest overall accuracy (0.88), followed by AGLC (0.85) and GFSAD (0.84), with FROM-GLC and GLC_FCS performing the worst (OAs < 0.70).




Reference:

[1] **Chao Zhang**, Jinwei Dong\*, Quansheng Ge. [Quantifying the accuracies of six 30-m cropland datasets over China: A comparison and evaluation analysis.](https://doi.org/10.1016/j.compag.2022.106946){:target="_blank"} *Computers and Electronics in Agriculture* 197, 106946-106959.

[2]	Yifeng Cui, Ronggao Liu, Zhichao Li, **Chao Zhang**, Xiao-Peng Song, Jilin Yang, Le Yu, Mengxi Chen, Jinwei Dong\*. (2024). [Decoding the inconsistency of six cropland maps in China.](https://doi.org/10.1016/j.cj.2023.11.011){:target="_blank"}. *The Crop Journal* 12, 281-294. [Full text link](https://drive.google.com/file/d/1yf7dppdTa6z9BgAub9ExQPxehCjg-MS9/view?usp=sharing){:target="_blank"}
 
[3]	Yifeng Cui, Jinwei Dong\*, **Chao Zhang**, Jilin Yang, Na Chen, Peng Guo, Yuanyuan Di, Mengxi Chen, Aiwen Li, Ronggao Liu. (2024). [Validation and refinement of cropland map in southwestern China by harnessing ten contemporary datasets.](https://doi.org/10.1038/s41597-024-03508-5){:target="_blank"}. *Scientific Data* 11, 671. [Full text link](https://drive.google.com/file/d/1xbyXRU89rwU5e47jyz6L92DXodRQooI9/view?usp=sharing){:target="_blank"}





More updates soon
------ 
