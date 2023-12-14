# Automatic Registration of Histopathological Image Pairs Using SimpleITK
This repository contains Jupyter Notebooks demonstrating the use of automatic registration using Python and SimpleITK.

**Please note** that in order for this code to work, the directory [wsi_processing_pipeline](https://github.com/FAU-DLM/wsi_processing_pipeline) must be located in the same directory as the Jupyter Notebook files.

The raw histopathological image data we used is not available to the public, but the code can be useful to researchers working with their own image data. The paper related to this work is yet to be published. Here's an excerpt of its Abstract:
## Background:
Comparable image data is indispensable in training neural networks for digital staining, and specialized image registration is required for harmonization of histopathological image pairs. However, an **open-source approach of registering and evaluating transformations automatically for a full database** has not yet been published.
## Methods:
We used our database of 616 whole slide image pairs of pituitary adenoma tissue. The tissues for each pair had been extracted from **closely collocated slices**, which had been differently stained during clinical routine, and then digitized.
## Results:
Despite **limited working memory and noticeable differences in whole slide image pairs**, we produced **satisfactory results** and found **reproducible ways to salvage tissue pairs that had initially not been registrable**.
