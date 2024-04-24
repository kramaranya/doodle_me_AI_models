# Doodle Recognition System (DRS) AI Models

This repository contains machine learning notebook `DRS_model.ipynb` dedicated to the development and evaluation of AI models for the Doodle Recognition System (DRS).

## About `DRS_model.ipynb`

The `DRS_model.ipynb` is a Jupyter notebook that includes the following components:

### Data Loading and Preprocessing
- **Data Loading**: The notebook begins by loading a dataset comprising 345 classes of doodles.
- **Preprocessing**: It includes preprocessing steps that are crucial for preparing the doodle data for training the models.

### Model Development
- **CNN Model**: Development of a Convolutional Neural Network (CNN) for recognizing and classifying doodle images.
- **RNN Model**: Development of a Recurrent Neural Network (RNN) that focuses on the sequential nature of drawing data.

### Training
- Both models are trained on the dataset to learn the classification of doodles into one of the 345 categories.

### Performance Evaluation
- **Accuracy**: Calculation of how often the models correctly predict the class of the doodles.
- **F1 Score (Macro)**: A measure that balances the precision and recall of the models across all classes.
- **AUC (Area Under the Curve)**: From the Receiver Operating Characteristic (ROC) curve, assessing the models' ability to discriminate between classes.
