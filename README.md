# Vehicle-Number-Plate-Recognition-Using-Machine-Learning

#  This is era of automation and this should be done automatically. That’s why “Vehicle Number Plate Recognition Using Machine Learning”. This project will help to recognize number plate of vehicle by recognizing characters and number present on number plate of vehicle. 

# There are three stages in recognizing number plate
## 1. License Plate Detection: This is the first and probably the most important stage of the system. It is at this stage that the position of the license plate is determined. The input at this stage is an image of the vehicle and the output is the license plate.

## 2. Character Segmentation: It’s at this stage the characters on the license plate are mapped out and segmented into individual images.

## 3. Character Recognition: This is where we wrap things up. The characters earlier segmented are identified here. We’ll be using machine learning for this.

# License Plate Detection (Plate localization)
## This is the first stage and at the end of this stage, we should be able to identify the license plate’s position on the car. In order to do this, we need to read the image and convert it to grayscale. In a grayscale image, each pixel is between 0 & 255. We now need to convert it to a binary image in which a pixel is either complete black or white.

# Character Segmentation
## This is second stage in which characters of number plate segmented and each character was resized to 20px by 20px. This was done because of the next stage that has to do with recognition of the character.

# Character Recognition
## This is going to be the last stage, it’s at this stage we introduce the concept of machine learning. Machine learning can simply be defined as the branch of AI that deals with data and processes it to discover pattern that can be used for future predictions. The major categories of machine learning are supervised learning, unsupervised learning and reinforcement learning. Supervised learning makes use of a known dataset (called the training dataset) to make predictions. We’ll be taking the path of supervised learning because we already have an idea of how As, Bs and all the letters look like. Supervised learning can be divided into two categories; classification and regression. Character recognition belongs to the classification category.
