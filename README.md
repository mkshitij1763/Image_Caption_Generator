Here's the updated README file with the link to the dataset:

---

# Image Caption Generator

## Overview

This project aims to generate captions for images using deep learning techniques. It combines computer vision with natural language processing to understand the content of an image and generate human-like descriptions.

## Table of Contents

1. [Introduction](#introduction)
2. [Setup](#setup)
3. [Usage](#usage)
4. [Results](#results)
5. [Credits](#credits)
6. [License](#license)

## Introduction

Image captioning is the task of generating a textual description for an image. This project leverages a pre-trained VGG16 model for feature extraction from images and an LSTM-based neural network for generating captions. The model is trained on the Flickr8k dataset, which contains images paired with descriptive captions.

## Setup

### Prerequisites

- Python 3.x
- TensorFlow
- Keras
- NumPy
- NLTK

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/mkshitij1763/Image_Caption_Generator.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Data Preparation**: Ensure that the Flickr8k dataset is downloaded from [here](https://www.kaggle.com/datasets/adityajn105/flickr8k) and placed in the appropriate directory.

2. **Feature Extraction**: Use the VGG16 model to extract features from the images in the dataset.

3. **Text Preprocessing**: Clean and preprocess the captions associated with the images.

4. **Model Training**: Train the caption generation model using the preprocessed data.

5. **Evaluation**: Evaluate the model's performance using metrics like BLEU score.

6. **Generate Captions**: Use the trained model to generate captions for new images.

## Results

The model achieves promising results in generating descriptive captions for images. Evaluation metrics such as BLEU score indicate the quality of the generated captions. Examples of generated captions along with actual captions are provided in the notebook.

## Credits

- The project uses the Flickr8k dataset for training and evaluation. Dataset available [here](https://www.kaggle.com/datasets/adityajn105/flickr8k).
- TensorFlow and Keras libraries are utilized for deep learning tasks.
- NLTK is used for text preprocessing.

