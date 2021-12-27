# Satellite-Image-Analysis
## Introduction
Many government programs are taking enormous efforts to make satellite images free and open sourced in order to bring in innovation and entrepreneurship. 

This is being used by many domains and are coming up with good results. In order to get great insights and knowledge from this satellite data we have to segment and understand it for further studies. Such type of a task is Landcover classification which come up and automate the process of identifying how the land area is used. 

A satellite scans the Earth to acquire images of it. Patches extracted out of these images are used for classification. The aim is to automatically provide labels describing the represented physical land type or how the land is used. For this purpose, an image patch is feed into a classifier, in this illustration a neural network, and the classifier outputs the class shown on the image patch.

## Dataset Description
We use the redesigned Multi-label UC Merced dataset with 17 land cover classes. UC Merced Land use dataset was initially introduced as one of the earliest satellite datasets for computer vision. The UC Merced dataset is considered as the MNIST of satellite image dataset. The original dataset consisted of 21 classes of single-label classification.
The authors were able to sort out some common issues that come up with studying satellite data and were able to sort it out for land use and land cover classification.
-	Cloud Appearance
-	Color casting due to atmospheric effects
-	Dead/Pixels
-	Ice or Snow

## References

EuroSAT: A Novel Dataset and Deep Learning Benchmark for Land Use and Land Cover Classification
https://docs.fast.ai/tutorial.vision.html
https://github.com/phelber/eurosat
https://www.dropbox.com/s/u83ae1efaah2w9o/UCMercedLanduse.zip
