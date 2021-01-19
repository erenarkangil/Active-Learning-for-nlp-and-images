# Interactive-Auto-Image-Labelling-with-Active-Learning

What does repository involve?

- Reading and pairing YOLO inputs as image objects-label pairs

- Denormalize YOLO cordinates for active leraning training

- Cropping each object in images, for my case it was tons of beers in freezer

- Resizing and reduction of dimensionality of images from rgb to grayscale

- Stacking resized image array from 200,50 to 10000 as MNIST dataset 

- Normalize the array values for better Accuracy

Accuracy: 0.34 for 48 beer classes.
