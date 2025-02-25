# Facial Keypoints Detection

This project focuses on detecting facial keypoints (landmarks) in images using deep learning techniques. Accurate detection of these keypoints is essential for various applications, including facial recognition, emotion detection, and augmented reality.

## Project Overview

The goal of this project is to build a model that can predict the location of 68 facial keypoints on a given image. The dataset used contains images of faces along with their corresponding keypoint annotations.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.6 or higher
- pip (Python package installer)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ryan8614/Facial-Keypoints-Detection.git
   cd Facial-Keypoints-Detection

	2.	Install required packages:

pip install -r requirements.txt


	3.	Download the dataset:
The dataset can be obtained from the Kaggle Facial Keypoints Detection competition. Place the downloaded files (training.csv, test.csv, IdLookupTable.csv) into the data/ directory.

Usage

Training the Model

To train the model, run:

python src/train.py

This script will load the training data, preprocess it, define the neural network architecture, and train the model. The best model will be saved in the models/ directory as best_model.h5.

Making Predictions

To make predictions on the test set, run:

python src/test.py

This script will load the test data and the trained model, then output the predicted keypoints for each image in the test set.

Acknowledgements

This project is inspired by the Kaggle competition on Facial Keypoints Detection. Special thanks to the contributors of the original dataset and the community for their valuable resources and discussions.

License

This project is licensed under the MIT License. See the LICENSE file for details. 
