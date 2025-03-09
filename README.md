# ds-earth-observation
Project repository of Data Science in Earth Observation module offered by Chair of Data Science in Earth Observation of Technische Universität München School of Engineering and Design.

Task
Use Sentinel-2 multi-spectral imagery to derive the dominant tree species for forests in Germany. Dominant tree species shall be classified by a machine-learning approach trained through the provided reference data.

Abstract

Accurate tree species classification is essential for precision forestry and biodiversity conservation. To
address challenges such as cloud obstruction, limited spatiotemporal resolution, and data imbalance in
remote sensing imagery, this study proposes a hierarchical (leaf type–genus–species) classification
framework based on multi-temporal Sentinel-2 data. We first apply cloud masking and temporal
interpolation to the raw imagery, compute multiple vegetation indices (NDVI, EVI, SAVI, etc.), and
subsequently employ various machine learning and deep learning models, including XGBoost,
Convolutional Neural Networks (CNN), and Vision Transformer (ViT), for tiered training and prediction.
Experimental results on three taxonomic levels demonstrate that ViT achieves the best accuracy at the
species level (e.g., 65%, surpassing GNN and XGBoost by approximately 3% and 1%,), highlighting its
advantage in capturing subtle spectral and temporal features. Moreover, leveraging time-interpolated
multi-temporal data effectively mitigates the impact of cloud cover and enhances model robustness. The
hierarchical label structure further improves generalization in large-scale, fine-grained species
identification tasks. These findings offer valuable insights for forest resource assessment, ecosystem
monitoring, and precision forestry applications.

Keywords: Tree Species Classification; Multi-temporal Remote Sensing; Sentinel-2; Hierarchical
Learning; Deep Learning; Vision Transformer; XGboost; Convolutional Neural Network; Random
Forest; Graph Neural Network

Some relating links to the project: https://ml4earth.de/

References 

[1] Phiri, D., Simwanda, M., Salekin, S., Nyirenda, V. R., Murayama, Y., & Ranagalage, M. (2020). Sentinel-2 data for land cover/use 
mapping: A review. Remote Sensing, 12(14), 2291. 

[2]  Kwenda, C. G. M. F.-D. J. (2023). Forest Image Classification Based on Deep Learning and XGBoost Algorithm. 

[3]  Zhou, J., Cui, G., Hu, S., Zhang, Z., Yang, C., Liu, Z., Wang, L., Li, C., & Sun, M. (2020). Graph neural networks: A review of methods 
and applications. AI Open, 1, 57–81. https://doi.org/10.1016/j.aiopen.2021.01.001 

[4]  Marjani, M., Mohammadimanesh, F., Mahdianpari, M., & Gill, E. W. (2025). A novel spatio-temporal vision transformer model for 
improving wetland mapping using multi-seasonal Sentinel data. Remote Sensing Applications: Society and Environment, 37, 101401. 
https://doi.org/10.1016/j.rsase.2024.101401.

[5] Sharma, N., Jain, V., & Mishra, A. (2018). An analysis of convolutional neural networks for image classification. International 
Conference on Computational Intelligence and Data Science, 132(1), 377–381. 

[6] Demonstrates the spectral bands' resolution distances to wavelength distribution. Cited from: Lolli, S., Alparone, L., Arienzo, A., & 
Garzelli, A. (2024). Characterizing Dust and Biomass Burning Events from Sentinel-2 Imagery. Atmosphere, 15(6), 672. 
https://doi.org/10.3390/atmos15060672
