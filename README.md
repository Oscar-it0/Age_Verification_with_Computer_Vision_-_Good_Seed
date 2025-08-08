# Sprint 17 - Project: Age Verification with Computer Vision - Good Seed

## Project Description

The **Good Seed** supermarket chain seeks to comply with alcohol sales laws by preventing sales to minors. To this end, it proposes to build a computer vision model that estimates a person's age from a photograph taken at the checkout area.

---

### Objective

Develop and evaluate a machine learning model that can estimate a person's age from images using computer vision techniques.

---

## Data

- **Labels**: `labels.csv`
- **Images**: `final_files/`

---

## Exploratory Data Analysis

### Dataset size
- Total number of images
- Age range

### Age distribution
- Age histogram
- Mean, median, and standard deviation

### Sample images
Between 10 and 15 representative images of different ages are shown to give a general impression of the dataset.

### Observations
- Variability in image quality
- Uneven age distribution
- Possible biases in the dataset

---

## Model Training

### Architecture
**ResNet50** with pre-trained weights in **ImageNet** was used.


### Implemented functions
- `load_data(path)`
- `create_model(input_shape)`
- `train_model(model, train_data, test_data, batch_size=None, epochs=20, steps_per_epoch=None, validation_steps=None)`

### Evaluation metric
- **Mean Absolute Error (MAE)**

---

## Checklist

- Exploratory analysis
- Data preparation
- Model training and evaluation
- Clear and structured documentation
- Clean and organized code

---

## Tools

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Tensorflow
