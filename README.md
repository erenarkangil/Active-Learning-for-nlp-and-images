# Interactive-Auto-Image-Labelling-with-Active-Learning

What does repository involve?

- Reading and pairing YOLO inputs as image objects-label pairs

- Denormalize YOLO cordinates for active leraning training

- Cropping each object in images, for my case it was tons of beers in freezer

- Resizing and reduction of dimensionality of images from rgb to grayscale

- Stacking resized image array from 200,50 to 10000 as MNIST dataset 

- Normalize the array values for better Accuracy


This is an ongoing project. Stream-based pooling is used. After 800 query-epoch the accuracy is converged at => 
Current Accuracy: 0.4428 for 48 beer classes.


![indir (3)](https://user-images.githubusercontent.com/47353633/105707665-58e81c00-5f24-11eb-89c0-76261b38d779.png)
