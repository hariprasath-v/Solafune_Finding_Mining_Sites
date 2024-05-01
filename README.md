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
