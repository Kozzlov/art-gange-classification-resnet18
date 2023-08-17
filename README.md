# art-gange-classification-resnet18
Overview: 
The given model is a fine-tuned version of resnet18, intended to help in classification of paintings. The first model version can identify four major classes: Genre, Landscape, Portrait and Naturmort. 

Data:
The training data was scraped from louvre archive page - https://collections.louvre.fr/en/. 
Class split is based on article - http://www.visual-arts-cork.com/painting-genres.htm.

Repository description: 
1. Model training/inference code - image_classification_transfer_learning.ipynb
2. Train/Val dataset - painting_image_data (image_size - 500x500)
3. Test dataset - painting_image_test (image_size - 500x500)
4. Fine-tuned model checkpoint - ckpts/renaissance_v1.pt
