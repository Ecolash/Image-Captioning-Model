# Image Captioning with Occlusion Analysis

This project implemets a ViT-GPT2-based image captioning model, with experiments analyzing model robustness under different levels of image occlusion (10%, 50%, 80%).

## Contents

The repository includes the following notebooks:

- **1. Training Notebook**: Used to train the custom ViT-GPT2 captioning model.
- **2. Caption Generation**: Generates captions for test images using the trained model.
- **3. Occlusion Analysis**: Applies varying levels of occlusion to images and generates captions to evaluate performance.

## Running Instructions

There are no specific dependencies beyond standard Python libraries and Hugging Face Transformers. All experiments were run in [Kaggle Notebooks](https://www.kaggle.com/code).

To reproduce results:
1. Open any notebook in Kaggle.
2. Ensure GPU is enabled.
3. Run all cells top to bottom.

The trained model file (`best_captioning_model.pt`) is loaded directly from a Kaggle dataset in the captioning and evaluation notebooks.

## Team Members

- **Gayathri Anant**  
  Email: gayathrianant05@gmail.com
  Roll No: 22CS30026

- **Tuhin Mondal**  
  Email: email2tuhin04@gmail.com
  Roll No: 22CS10087

- **Diganta Mandal**  
  Email: digantamindia@gmail.com  
  Roll No: 22CS30062

## Thanks and Acknowledgements

We sincerely thank our Deep Learning course instructor and TAs for their support and feedback throughout the course.

We also acknowledge the open-source community and tools that made this work possible:
- Hugging Face Transformers
- PyTorch
- Kaggle Datasets and Notebooks


