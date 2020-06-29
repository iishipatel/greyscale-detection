# Greyscale-Detection
### Tools used:
- OpenCV
- Numpy
- Matplotlib

### Explaination:
I have divided image into 3 channels (r,g,b) and taken the sum of  difference between each channel. If given image belongs to the grayscale category, sum will be zero. If not it, contains some amount of colour. Next, we calculate percentage of grayscale. This is done by finding the ratio of the sum (calculated above) to the image size. This will give is the colour percentage, hence, for grayscale we subtract it from one. 
