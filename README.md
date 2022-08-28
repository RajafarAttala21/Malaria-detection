# **Image Processing** Malaria in Red Blood Cells

_by Mohammad Attala Rajafar_

<img title="img" src="Images/ImageProcessing.jpg">

<p align="justify">This project contains about how malaria can be detected in red blood cells using 4 methods, namely:</p>

1. Matching templates
2. Multiple Matching Templates
3. Thresholding
4. Total Red Blood Cells (in the picture)

**The dataset i used**

<img src="Images/Template_Matching/dataset.PNG"> </br>

<br>

### Multiple Template Matching

<p align="justify">Multi-Template-Matching is a python package used to perform object-detection on a given image. It makes use of the list of templates as a reference to detect objects similar to the present in the given image. This package is capable of detecting multiple similar/different objects in the image as long as the templates for all the required objects to be identified are provided beforehand.</p>

Using libraries:

- numpy
- matplotlib
- cv2/opencv

<img src="Images/Multiple_Template_Matching/results.png">

</br>

### Template Matching

<p align="justify">Template matching refers to the image processing where we find similar templates in a source image by giving a base template to compared on. The process of template matching is done by comparing each of the pixel values of the source image one at a time to the template image. The output would be an array of similarity values when compared to the template image.</p>

Using libraries:

- numpy
- matplotlib
- skimage

<img src="Images/Template_Matching/results.png"> </br>

### Thresholding

<p align="justify">The simplest thresholding methods replace each pixel in an image with a black pixel if the image intensity is less than a fixed value called the threshold, or a white pixel if the pixel intensity is greater than that threshold. In the example image on the right, this results in the dark tree becoming completely black, and the bright snow becoming completely white.</p>

Using libraries:

- skimage
- matplotlib

<img src="Images/Thresholding/results.png"> </br>

### Total Red Blood Cells

<p align="justify">Trying to find out how many red blood cells can be recognized through an image</p>

Using libraries:

- cv2
- matplotlib

<img src="Images/Total_Redblood_Cells/result.png"> </br>

<img src="Images/Total_Redblood_Cells/final result.png"> </br>
