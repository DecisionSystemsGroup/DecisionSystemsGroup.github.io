---
layout: project
type: dsg_project
title: Vehicles Plate Recognition
members: [stavros_tsourlidakis, philip_dinenis]
thumb:
repo:
website:
---
A collection of image processing algorithms that aim to extract the license plate from a car's photograph taken at parking lots/tolls etc.

The whole process is consisted by 3 parts:
1. Locate the plate inside the photograph
2. Extract each character as a separate part of the photograph
3. Transform the characters to text using OCR

### 1. Locating the plate inside the photograph
* Convert the image to grayscale
* Apply a [sobel](https://en.wikipedia.org/wiki/Sobel_operator) mask for later edge detection
* Convert the image to binary by [Thresholding](https://en.wikipedia.org/wiki/Thresholding_%28image_processing%29)
* Calculate [edges](https://en.wikipedia.org/wiki/Edge_detection) 
* Use the edge to locate the plate
<center>
<img src="http://i.imgur.com/Vw6icVFm.png" alt="image edge detection">
</center>

### 2. Extracting each character as a separate part of the photograph
* Convert the plate image to binary by [Thresholding](https://en.wikipedia.org/wiki/Thresholding_%28image_processing%29)
* Calculate [edges](https://en.wikipedia.org/wiki/Edge_detection)
* Use the edges and extract the characters
<center>
<img src="http://i.imgur.com/qCaUNOFm.jpg"  alt="plate binary">
<img src="http://i.imgur.com/GhLfb0Mm.jpg" alt="plate characters edge detection">
</center>
### 3. Transform the characters to text using OCR
Not implemented
