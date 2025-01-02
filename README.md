# Lego Minifigure Classification

## Objective
This [dataset](https://www.kaggle.com/datasets/ihelon/lego-minifigures-classification/data) from Kaggle contains images of Lego Minifigures from different Lego series and collaborations (ie. Marvel, Star Wars, etc.). We will use this data to find the most optimal classification model to accurately predict the name of the Minifigures from images of the figures.

**Note:** We used this [Kaggle notebook](https://www.kaggle.com/code/danielbeltran/learning-deep-learning-tensorflow-with-lego#CNN---Convolutional-Neural-Network) as a loose guide and tutorial for this analysis.

## Business Problem
This analysis is great for Lego customers who want to identify Lego Minifigures for collection or display. This model can also be used for Lego retailers to manage their inventory.

## Data Understanding
There are 3 datasets we will explore. `index.csv` which has the images of the training data, `metadata.csv` which holds the metadata of the different minifigures, and `test.csv`, which has the testing data for our model.


**NOTE:** Because this is a dataset of images, we may not be able to perform a full EDA on it.

## Summary
- **Modeling:**
    - The dataset consists of images, so a proper EDA was not relevant here.
    - We used this dataset on a basic MLP and also tried two approaches of CNNs, and although the model accuracy of the training data improved, the accuracy of the testing data did not. Further research and debugging is required.
- **Next Steps:**
    - Debug the issue of why the model cannot accurately predict on the testing data.
    - Export the model and deploy it for customers and retailers to use.

## For More Information
Original data source: https://www.kaggle.com/datasets/ihelon/lego-minifigures-classification/data

## Repository Structure
```bash
├── data
├── images
├── notebooks
├── .gitignore
├── README.md
```