# Grapevine Leaf Disease Classification (CNN from Scratch)

This project implements a Deep Convolutional Neural Network (CNN) using Keras/TensorFlow to classify grapevine leaves into four categories:

- Black Rot
- ESCA
- Healthy
- Leaf Blight

## 📁 Dataset

The dataset contains images captured under both field and laboratory conditions.
The classes represent common diseases and healthy grapevine leaves.

## 🧠 Model

- 5 Convolutional layers, 3 MaxPooling layers
- Regularization with Dropout and BatchNormalization
- Real-time data augmentation (rotation, zoom, shift, shear, flip)
- Trained using Adam optimizer and categorical crossentropy loss

## 🧪 Results

- EarlyStopping and ModelCheckpoint callbacks were used
- Accuracy and loss curves were plotted for training and validation
- Classification report and confusion matrix were generated

## 💡 Reflection

- Training from scratch provided full control but needed strong regularization
- Data augmentation improved generalization ability
- Future improvements may involve transfer learning with pretrained models

## 🚀 How to Run

```bash
# Install dependencies
pip install tensorflow matplotlib seaborn scikit-learn pillow

# Run the Jupyter Notebook
jupyter notebook grapevine_disease_classification.ipynb
```
