# Week1 & Week 2
***********************************************************************

week 1:
project:Plant disease detection system for sustainable agriculture

This project builds a CNN-based model to identify diseases in plant leaves using images. It classifies leaves from crops like apple 🍎, cherry 🍒, grape 🍇, and corn 🌽 as healthy or infected. The system helps 👨‍🌾 farmers detect diseases early, enabling faster action and sustainable farming.

#Week 2

In this module of the Plant Disease Detection System, I mounted Google Drive to access a zipped dataset of plant disease images. The dataset was successfully extracted using Python’s zipfile module.

Next, I utilized TensorFlow's ImageDataGenerator to preprocess the image data from the training directory. Images were resized to 224x224 pixels, normalized (rescaled), and augmented with random rotations. A 10% validation split was applied.

Finally, I visualized a batch of 16 sample images along with their corresponding class labels to confirm successful data loading and label mapping.

