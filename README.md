# Solafune_Finding_Mining_Sites
### Competition hosted on [Solafune]()
### Overview
Mineral resources are used in various fields, from daily necessities to cutting-edge technology, and have become an indispensable element for the development of modern society. Particularly in Africa and Southeast Asia, these mineral resources are abundant and contribute to economic growth and trade expansion as major exports in many African and Southeast Asian countries. On the other hand, these countries face issues, such as the inability to properly monitor mine development, often resulting from a lack of their resources.

In response to this situation, the competition aims to develop a technology for detecting mining sites using images from the optical satellite Sentinel-2. Specifically, it involves classifying images that contain mining sites and those that do not.
We expect all participants to take on this challenge and develop new technologies that not only detect mining sites but also contribute to the mineral industry.

### Data Overview
#### Sentinel-2 images

The Sentinel-2 image contains information on 12 bands and includes the following bands 'B1', 'B2', 'B3', 'B4', 'B5', 'B6', 'B7', 'B8', 'B8A', 'B9', 'B11', 'B12'

For more information, please visit [this site](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S2_SR_HARMONIZED#bands)

The images have been processed to mask clouds for Sentinel-2 images from 2022/1/1 to 2023/12/31, and the median of all images is used as the image for that location.

### My Approach
### Exploratory Data Analysis
  * Target class distribution analysis.
  * Visualize a sample image with 12 bands by target class.
  * Histogram analysis for each band by target class
  * Visualize Sentinel-2 popular RGB composites by target class
  * Visualize remote sensing indices by target class
    * NDVI - Normalized Difference Vegetation Index
    * NDWI - Normalized Difference Water Index
    * FMI - Ferrous Mineral Index
    * MSI - Moisture Stress Index
    * BSI - Bare Soil Index
    * NBR - Normalized Burn Ratio
  * Basic image-level information analysis
    * Entropy
    * Contrast
    * Blur
  * Image duplication analysis
    * Find duplication images using the perceptual hashing technique.
      
The notebook for exploratory data analysis is available on Kaggle.[![Open in Kaggle](https://img.shields.io/static/v1?label=&message=Open%20in%20Kaggle&labelColor=grey&color=blue&logo=kaggle)](https://www.kaggle.com/code/hari141v/solafune-finding-mining-sites-eda)

      
