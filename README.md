# Cat Classifier

A TensorFlow/Keras image classification project that predicts whether an image is a **cat** or **not cat**.

## Overview

This project uses a Convolutional Neural Network (CNN) to learn visual patterns from labeled images and perform binary image classification. It was built as a computer vision practice project to strengthen skills in deep learning, image preprocessing, model training, validation, and prediction.

## Features

- Binary image classification: **cat** vs **not cat**
- Image preprocessing and loading
- CNN model training and validation
- Single-image prediction
- Clean GitHub structure without large dataset files

## Project Structure

```text
cat_classifier/
├── dataset/
├── model/
├── notebook/
│   └── cat_vs_not_cat.ipynb
├── .gitignore
└── README.md
```

## Folder Description

- `dataset/` — local dataset folder for training and validation images
- `model/` — local folder for saved model files
- `notebook/` — contains the Jupyter notebook used for training and testing
- `.gitignore` — excludes large or unnecessary files from GitHub
- `README.md` — project documentation

## Dataset

The dataset is not included in this repository because it is too large to upload to GitHub.

Dataset source:
- [Dog and Cat Classification Dataset on Kaggle](https://www.kaggle.com/datasets/bhavikjikadara/dog-and-cat-classification-dataset)

### How to set up the dataset

1. Download the dataset from Kaggle.
2. Extract the downloaded files.
3. Place the dataset inside the `dataset/` folder in this project.

## Model File

The trained model file is not included in this repository to keep the project lightweight and easier to clone.

If needed, you can retrain the model using the notebook and save your own `.keras` file locally inside the `model/` folder.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook

## Model Architecture

This project uses a **Convolutional Neural Network (CNN)** for binary image classification. The model learns features from training images and predicts whether a new image belongs to the **cat** or **not cat** class.

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/CapMorningStar/cat-classifier.git
   ```

2. Open the project folder:

   ```bash
   cd cat-classifier
   ```

3. Install the required libraries:

   ```bash
   pip install tensorflow numpy matplotlib jupyter
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open and run:

   ```text
   notebook/cat_vs_not_cat.ipynb
   ```

## Output

The model predicts one of the following classes:

- **Cat**
- **Not Cat**

## Notes

- The full dataset is excluded from this repository.
- The trained `.keras` model file is also excluded from this repository.
- You can test your own images by updating the image path inside the notebook.

## Future Improvements

- Improve model accuracy
- Add data augmentation
- Add evaluation metrics such as precision and recall
- Build a simple web app for prediction
- Deploy the model online

## Author

**Kyaw Soe Lwin**

## License

This project is for educational and portfolio purposes.
