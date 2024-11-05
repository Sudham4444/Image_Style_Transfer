# Neural Style Transfer

This repository contains a simple implementation of Image Style Transfer using neural networks. It combines the content from one image with the artistic style of another. This project was developed as a learning exercise and is based on the **[TensorFlow Neural Style Transfer](https://www.tensorflow.org/tutorials/generative/style_transfer)** and other deep learning concepts.

## Overview
This project showcases:

- Content Image: The main image whose structure and features remain prominent.
- Style Image: An artwork whose color scheme and textures will be blended into the content image.
- Output Image: The final result, which combines the style of the artwork with the details of the content image.

## Features

- Blend content and style from different images
- Adjustable weights for content and style loss
- Visualize the training process and final output
- Easy to customize for various artistic styles

## Example Results
1. Content Image
   
      ![content_image](https://github.com/Sudham4444/Image_Style_Transfer/blob/main/output/content_image.png)

2. Style Image
   
      ![style_image](https://github.com/Sudham4444/Image_Style_Transfer/blob/main/output/style_image.png)

3. Output Image
   
      ![style_image](https://github.com/Sudham4444/Image_Style_Transfer/blob/main/output/iteration_1000.png)

## Objective
The purpose of this project is to understand how style transfer models use deep learning to blend visual styles. 
> Note: This implementation is intended for educational purposes, as it utilizes a simple approach based on feature extraction from pre-trained networks.

## Requirements
Run this code in **[Google Colab](https://colab.research.google.com)**, as it includes GPU support, which is beneficial for faster image processing.

- Python 3.x
- TensorFlow
- Pillow
- NumPy
- Matplotlib

## Installation

To run the neural style transfer code, install the necessary libraries. You can do this easily with the following commands:

1. **TensorFlow** - for neural style transfer:

       !pip install tensorflow

2. Other Dependencies:

    - `pillow` for image handling
    
    - `numpy` for numerical computations
    
    - `matplotlib` for visualization
  
    Install all of these with:
        
       !pip install pillow numpy matplotlib

3. Running on Google Colab
   
      If you’re running this project on Google Colab, TensorFlow is typically pre-installed. You may only need to install additional packages like Pillow, NumPy, and Matplotlib as needed.

You can clone the repository and follow along:

    git clone https://github.com/Sudham4444/Image_Style_Transfer.git

## Steps
1. Loading and Preprocessing Images: Load the content and style images and resize them as needed.
2. Feature Extraction: Use a pre-trained VGG19 model to extract style and content features.
3. Loss Calculation: Calculate content and style losses to guide the optimization.
4. Optimization: Run an optimization loop to generate an image that minimizes the loss.
5. Display Result: Show the final stylized image.

## Running the Code
1. Open the notebook on Google Colab.
2. Upload your images or use the provided ones.
3. Follow the instructions to load images, process them, and perform style transfer.
4. The final output image will display at the end of the notebook.

## What I Learned
Throughout this project, I gained valuable insights into:

1. Using a Pre-trained Model: Leveraged VGG19 to extract content and style features.
2. Implementing Style Transfer: Applied content and style loss functions to guide the image transformation.
3. Optimizing Images: Ran iterative optimization to generate the final output.
4. Utilizing Google Colab: Worked with GPU resources to speed up processing.

## Acknowledgments
This project was inspired by:

- **[TensorFlow Neural Style Transfer Tutorial](https://www.tensorflow.org/tutorials/generative/style_transfer)**
- VGG19 model pretrained on ImageNet.
  
This tutorial served as a foundation for understanding the key principles of neural style transfer.

## License
This project is shared for learning and non-commercial purposes only.
