# Cat Classifier

This project is a deep learning image classification project that classifies images as **cat** or **not cat** using TensorFlow/Keras.

## Project Overview

The goal of this project is to build a convolutional neural network (CNN) model that can learn image patterns and predict whether a given image contains a cat or not. This project is useful for practicing computer vision, image preprocessing, model training, validation, and single-image prediction.

## Features

- Binary image classification: **cat** vs **not cat**
- Image preprocessing and dataset loading
- CNN-based deep learning model
- Model training and validation
- Single image prediction
- Saved trained model for later use

## Project Structure

```text
cat_classifier/
├── dataset/
├── model/
├── notebook/
├── .gitignore
└── README.md
```

### Folder Description

- `dataset/` — contains the training and validation images  
- `model/` — contains saved model files  
- `notebook/` — contains the Jupyter notebook used for training and testing  
- `.gitignore` — excludes large or unnecessary files from GitHub  
- `README.md` — project documentation  

## Dataset

The dataset is not included in this repository because it is too large to upload to GitHub.

You can download the dataset from Kaggle:

- [Dog and Cat Classification Dataset](https://www.kaggle.com/datasets/bhavikjikadara/dog-and-cat-classification-dataset)

### How to use the dataset

1. Download the dataset from Kaggle.
2. Extract the files.
3. Place the dataset inside the `dataset/` folder in this project.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook

## Model

This project uses a **Convolutional Neural Network (CNN)** for image classification. The model is trained on labeled images and learns to distinguish cat images from non-cat images.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/cat-classifier.git
   ```

2. Open the project folder:
   ```bash
   cd cat-classifier
   ```

3. Install the required libraries:
   ```bash
   pip install tensorflow numpy matplotlib jupyter
   ```

4. Open the notebook:
   ```bash
   jupyter notebook
   ```

5. Run the notebook inside the `notebook/` folder.

## Output

The model predicts whether an input image is:

- **Cat**
- **Not Cat**

## Notes

- The full dataset is excluded from this repository to keep it lightweight.
- Trained model files such as `.keras` are also excluded if needed.
- You can use your own test image by updating the image path in the notebook.

## Future Improvements

- Improve model accuracy
- Add data augmentation
- Add more evaluation metrics
- Build a simple web app for prediction
- Deploy the model online

## Author

**Kyaw Soe Lwin**

## License

This project is for educational and portfolio purposes.
