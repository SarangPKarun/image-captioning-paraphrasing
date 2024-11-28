# A Multifaceted Approach to Image Captioning: Combining Paraphrasing and Deep Learning

## Overview

This repository presents a Jupyter notebook for a novel image captioning model that integrates paraphrasing techniques with deep learning architectures to improve the fluency, informativeness, and diversity of generated captions. The model leverages **EfficientNetB7** for image feature extraction and employs a **Hierarchical LSTM (Long Short-Term Memory)** decoder for caption generation. By incorporating paraphrasing into the training process, the model produces captions that are both linguistically expressive and contextually relevant.

This work has been accepted for publication at a conference. However, the official publication link is not yet available.

## Key Features
- **Image Feature Extraction**: **EfficientNetB7** is used for extracting rich image features.
- **Caption Generation**: Utilizes a **Hierarchical LSTM** to decode the features into meaningful natural language descriptions.
- **Paraphrasing Integration**: The paraphrasing tool 'Pageusus' is used to diversify and refine captions.
- **Evaluation**: The model is evaluated on the **Flickr8k dataset**, using various metrics such as BLEU, METEOR, and caption diversity.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/image-captioning-paraphrasing.git
   ```

Navigate to the project directory:

bash
Copy code
cd image-captioning-paraphrasing
Install the necessary dependencies:

bash
Copy code
pip install -r requirements.txt
Download the Flickr8k dataset (or another dataset of your choice) and place it in the data/ directory.

Usage
This project is implemented as a Jupyter notebook. To run the notebook:

Install Jupyter:

bash
Copy code
pip install notebook
Launch Jupyter:

bash
Copy code
jupyter notebook
Open the notebook image_captioning_paraphrasing.ipynb and follow the instructions to train and generate captions.

Model Architecture
The architecture consists of the following key components:

EfficientNetB7: Used for efficient and accurate image feature extraction.
Hierarchical LSTM: Used for generating captions from the extracted image features.
Pageusus Paraphraser: A paraphrasing tool to add diversity and refine the generated captions.
Evaluation Metrics
The performance of the model is evaluated using the following metrics:

BLEU score
METEOR score
Caption diversity
Acknowledgments
This work has been accepted for presentation at an upcoming conference (publication link pending).

License
This project is licensed under the MIT License - see the LICENSE.md file for details.
