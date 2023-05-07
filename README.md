# URFD-Dataset
Dataset for Slender Urban Road Facility Extraction in Oblique Aerial Images.


### 1. Introduction
We construct URFD dataset for slender urban road facility extraction in Oblique aerial images. Specifically, we first use the Shuangyu data collection platform carried on a DJI M600 UAV to collect oblique aerial images with a size of $7952\times5304$ pixels. Then, we crop them into a size of $512\times512$ pixels and select 1075 images containing urban road facilities with different types and shooting angles. At last, we manually annotated the bounding box and binary mask of targets using Labelme, a graphical image annotation tool.


In general, URFD is a complement of the real-world oblique aerial imagery dataset and consists of $1075$ oblique aerial imagery with a grand sample distance of 2-6 cm and an image size of $512\times512$ pixels. URFD has a more refined classification containing eight categories, including four types of street lamps, two types of monitors, and two types of traffic lights.

Examples of URFD are shown as the figure below.

<img src="https://github.com/zmaomia/URFD-Dataset/blob/main/URFD%20examples.png" width="900px">

Specifically, we divide each category based on its intended use, appearance, and shape features. Street lamp A is the double-arm street lamp that stands on high streets. Street lamp B is the single-arm street lamp that is built on the main road in cities. Street lamp C has multiple light sources and is usually used on high-speed roads, taller than Street lamp B. Street lamp D is comparably short and built on the pavements for pedestrians. Monitor A, shorter than Monitor B, is mainly used for public security monitoring, while Monitor B is built along the road and is mainly used for traffic monitoring. Traffic light A is used for motor vehicles, while Traffic light B is used for pedestrians crossing the road.

### 2. Dataset Download
(1) Via Google drive
 To be updated.


### 3. Paper
URFD is introduced by Mao et al. in "Improved Instance Segmentation for Slender Urban Road Facility Extraction Using Oblique Aerial Images" 

