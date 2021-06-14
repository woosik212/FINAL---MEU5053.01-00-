# FINAL-MEU5053.01-00
Final Project - Machine Learning and Programming (MEU5053.01-00)


# Project Title
Detecting the changes of Land cover based on machine learning algorithms using Landsat Satellite Images

# Research Motivation and Background
Rapid urbanization across many regions in the world is altering the existing land use/land cover (LULC), which is significantly affecting the environment in cities; such as land surface temperature, air pollution, ecological environment, etc.
Data related to land covers are built manually based on fact-findings surveys and manmade map, so the period of data production is long.
This study aims to classify the land cover using machine learning algorithms and estimate the change of LULC in one of the fastest-growing megacities and the capital of Korea, named as Seoul

## Study Area
![image](https://user-images.githubusercontent.com/68691092/121843798-e682a780-cd1d-11eb-8325-ac20133055a5.png)

# Data and Tools for Analysis
MODIS – Landsat 8 OLI/TRS (resolution of 30m), 30m pixels with (rows: 1698, columns: 1500)
2013 Satellite Image – (2013. 09. 16) / 2020 Satellite Image – (2020. 04. 28)
Cloud cover: Less than 1%
Land cover of Korea (Environmental Geographical Information Service, 환경공간정보서비스, resolution of 30m)
QGIS (GIS program for assigning and generating the training & testing sample), GRASS, GDAL
Machine learning algorithms on scikit-learn
![image](https://user-images.githubusercontent.com/68691092/121843928-1f228100-cd1e-11eb-939c-f9aa7d4ac5d6.png)


## Get Satellite Imagery from the links below (Google Drive)
1) https://drive.google.com/file/d/1j-tCjUY2QR2MmBmpvHfVjYHtB7RXAmcM/view?usp=sharing
2) https://drive.google.com/file/d/1vimOAa93f7AkMtlgRGJptWk6U5OIdgCA/view?usp=sharing

There are two Landsat Images which are,
1) L8_Seoul_20130916.tif (Raster file, Landsat 8 image of Seoul on 16th Sep, 2013)
2) L8_Seoul_20200428.tif (Raster file, Landsat 8 image of Seoul on 28th April, 2020)

and we are going to use thess two raster files to calssifying the Land cover of Seoul and outskirts of Seoul
* The size of file is pretty big
* Be sure to assign the right path where you download two satellite image raster files (.tif).

## Get Train and Test Dataset (Github, Code -> Zip download).
