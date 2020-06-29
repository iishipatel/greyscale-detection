# Greyscale-Detection
### Tools used:
- OpenCV
- Numpy
- Matplotlib

### Explaination:
I have divided image into 3 channels (r,g,b) and have taken the sum of the differences between each channel. If the given image belongs to the grayscale category, sum will be zero. If not, it contains some amount of colour. Next, we calculate percentage of grayscale. This is done by finding the ratio of the sum (calculated above) to the image size. This will give is the colour percentage, hence, for grayscale we subtract it from one. 
