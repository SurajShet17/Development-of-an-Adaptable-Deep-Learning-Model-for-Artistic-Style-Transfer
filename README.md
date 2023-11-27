
# Development of an Adaptable Deep Learning Model for Artistic Style Transfer

### Introduction
The exploration of "Development of an Adaptable Deep Learning Model for Artistic Style Transfer" represents a cutting-edge endeavor in the realm of artificial intelligence and creative expression. This research aims to construct a versatile deep learning model, leveraging advanced techniques like convolutional neural networks. By incorporating adaptability into the model, the goal is to refine the process of transferring artistic styles onto images, fostering a dynamic approach to content and style synthesis. This innovative pursuit holds the potential to revolutionize the field of digital artistry, offering a robust framework for creating visually captivating and personalized compositions through the fusion of content and diverse artistic styles.

### Important
I had previously attempted to use a simple CNN, but the results were not satisfactory. Therefore, I opted to utilize the VGG network in this case

### About Dataset
The Dataset has been taken from 
https://www.kaggle.com/karthikayanmailsamy/tamil-nst
which contain 12 content images and 12 style images based on Tamilnadu's Heritage

## Requirements

- Python 3.x
- all libraries contained in requirements.txt file

## Installation

1. Clone this repository to your local machine.
2. Install all the required Python packages (present in requirements.txt file) by running the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:
2. Run the ipynb file after installing all the dependencies in requirements.txt file.
3. Make sure to change the content and style location our your choice.

## Script Overview
The script consists of the following sections:

1. Import Resources
This section imports the required libraries and initializes the VGG19 model.

2. Load VGG19 (features)
Downloads the VGG19 model and extracts the features portion, freezing its weights.

3. Load Content and Style Images
Defines a function to load and preprocess images. Downloads sample content and style images and displays them.

4. VGG19 Layers
Prints out the structure of the VGG19 model to show the names and details of various layers.

5. Content and Style Features
Defines functions to extract content and style features from images.

6. Gram Matrix
Defines a function to calculate the Gram matrix of a given tensor.

7. Putting it all Together
Combines the previously defined functions to extract features, calculate Gram matrices, and initialize the target image.

8. Loss and Weights
Defines individual layer style weights, content and style weights, and sets up the optimization process.

9. Updating the Target & Calculating Losses
Performs the Neural Style Transfer by iteratively updating the target image based on content and style losses.

Happy styling!

## Contact

For any issues or questions, please contact surajshet5555@gmail.com.

## References
1. https://github.com/udacity/deep-learning-v2-pytorch
2. https://www.kaggle.com/datasets/karthikayanmailsamy/tamil-nst

---
