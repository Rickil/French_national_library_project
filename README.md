# Historical Document Segmentation Project

## Project Overview

This project is a collaborative effort with the French National Library, aiming to benchmark and establish a model for segmenting historical documents. The primary objective is to develop a robust segmentation model capable of accurately categorizing various elements within historical documents.

## Classes for Segmentation

The segmentation model distinguishes between different classes of elements present in historical documents. These classes include:

1. `tampon` (Stamp)
2. `écriture manuscrite` (Handwritten Text)
3. `écriture typographique` (Typewritten Text)
4. `photographie` (Photograph)
5. `estampe` (Print)

Additionally, there are other classes that contribute to the segmentation process. The goal is to accurately identify and categorize these elements within the historical documents.

## Benchmarking and Evaluation

To assess the performance of the segmentation models, we employ the COCO Panoptic Extension. This extension facilitates comprehensive evaluation by considering both stuff (e.g., background) and things (e.g., objects) in the segmentation process. The use of the COCO Panoptic Extension allows for a more nuanced and thorough benchmarking process, ensuring that the developed model meets the specific requirements of historical document segmentation.

