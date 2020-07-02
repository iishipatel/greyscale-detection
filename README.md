# Grayscale-Detection
## Pure Computer Vision Method

### Tools used:
- OpenCV
- Numpy
- Matplotlib

### Explaination:
I have divided image into 3 channels (r,g,b) and have taken the sum of the differences between each channel. If the given image belongs to the grayscale category, sum will be zero. If not, it contains some amount of colour. Next, we calculate percentage of grayscale. This is done by finding the ratio of the sum (calculated above) to the image size. This will give is the colour percentage, hence, for grayscale we subtract it from one. 

## Convolutional Neural Network Classification 

### Tools used:
- Keras
- Numpy

### Explanation
Here I have used a small custom dataset using google to simply classify if it's a coloured image or a grayscale image.  Here we ahve used a 3 layer convolutional neural network to train the model. Test cases are given below.
