# Dog Detection using Convolutional Neural Networks
The repository must have a README.md file that communicates the libraries used, the motivation for the project,
the files in the repository with a small description of each, a summary of the results of the analysis, and necessary acknowledgements.

## Motivation for the Project
Dog Detection is a popular starter Computer Vision problem. This project aims to use some of the most common methods for Dog Detection in images.

## Libraries Used
- OpenCV for Python
- Keras
- Scikit-Learn
- Matplotlib
- Numpy

## Files

- haarcascades
<br> -- haarcascade_frontalface_alt.xml : Features for HaarCascadeClassifier
- images
<br> -- h1.jpg
<br> -- h2.jpg
<br> -- h3.jpg
<br> -- d1.jpg
<br> -- d2.jpg
<br> -- d3.jpg
- saved_models
<br> -- weights.best.resnet50.hdf5 : Saved Weights for ResNet50 model
- dog_app.ipynb: IPython Notebook containing code for Dog Detection
- extract_bottleneck_features.py: Script to extract bottleneck features for transfer learning