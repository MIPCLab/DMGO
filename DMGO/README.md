# Dual-Branch Dynamic Modulation Network for Hyperspectral and LiDAR Data Classification

***Abstract:*** Deep learning algorithms that can effectively extract features from different modalities have achieved significant performance in multimodal remote sensing (RS) data classification. However, we actually found that the feature representation of one modality is likely to affect other modalities through parameter back-propagation. Even if multimodal models are superior to their uni-modal counterparts, they are likely to be underutilized. To solve the above issue, a dual-branch dynamic modulation network is proposed for hyperspectral (HS) and light detection and ranging (LiDAR) data classification. Firstly, a novel dynamic multimodal gradient optimization (DMGO) strategy is proposed to control the gradient modulation of each feature extraction branch adaptively. Then, a multimodal bi-directional enhancement (MBE) module is developed to integrate features of different modalities, which aims to enhance the complementarity of HS and LiDAR data. Furthermore, a feature distribution consistency (FDC) loss function is designed to quantify similarities between integrated features and dominant features, which can improve the consistency of features across modalities. Experimental evaluations on Houston2013 and Trento datasets demonstrate that our proposed network exceeds several state-of-the-art multimodal classification methods in terms of fusion classification performance.



## Datasets

- [Houston2013 (Hyperspectral and LiDAR Data)](https://hyperspectral.ee.uh.edu/?page_id=459): The processed .mat files can be obtained on [google drive](https://drive.google.com/file/d/1cyA7sKQlh2c7qrIb7gzexivoyXG8Vie2/view?usp=sharing).

- Trento Data (Hyperspectral and LiDAR Data): Trento dataset is provided by Professor  Prof. L. Bruzzone from the University of Trento.  


## Citation

If you find this work valuable or use our code in your own research, please consider citing us: 

> Z. Xu, W. Jiang and J. Geng, "Dual-Branch Dynamic Modulation Network for Hyperspectral and LiDAR Data Classification," in IEEE Transactions on Geoscience and Remote Sensing, vol. 61, pp. 1-13, 2023, Art no. 5514813, doi: 10.1109/TGRS.2023.3285097.

Bibtex format :

> @ARTICLE{10147800,
  author={Xu, Zhengyi and Jiang, Wen and Geng, Jie},
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  title={Dual-Branch Dynamic Modulation Network for Hyperspectral and LiDAR Data Classification}, 
  year={2023},
  volume={61},
  number={},
  pages={1-13},
  keywords={Feature extraction;Laser radar;Optimization;Hyperspectral imaging;Modulation;Training;Data mining;Feature fusion;hyperspectral image (HSI);imbalanced multimodal learning;land cover classification;multimodal remote sensing (RS)},
  doi={10.1109/TGRS.2023.3285097}}




