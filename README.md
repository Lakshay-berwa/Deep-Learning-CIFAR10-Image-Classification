# Deep-Learning-CIFAR10-Image-Classification
Deep Learning project using CNNs for CIFAR-10 image classification, with experiments on convolution, pooling, data augmentation, and MobileNetV2 transfer learning.
# Deep Learning – CIFAR-10 Image Classification

A Deep Learning project that explores Convolutional Neural Networks (CNNs) for image classification using the CIFAR-10 dataset.

This project implements CNN architectures from scratch, experiments with data augmentation, and applies transfer learning using MobileNetV2 to compare different approaches for image classification.

## 🚀 Project Objectives

- Load and preprocess the CIFAR-10 dataset.
- Perform exploratory data analysis and image visualization.
- Understand convolution operations, padding, and strides.
- Implement pooling and CNN architectures.
- Train CNN models using backpropagation.
- Apply data augmentation to improve generalization.
- Perform transfer learning using MobileNetV2.
- Compare model performance using accuracy and training time.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Programming language |
| TensorFlow / Keras | Deep learning and CNN implementation |
| NumPy | Numerical computations |
| Pandas | Data manipulation |
| Matplotlib | Image visualization |
| Seaborn | Data visualization |
| Scikit-learn | Model evaluation |
| Jupyter Notebook | Interactive development |

## 📊 Dataset

The project uses the CIFAR-10 dataset, which contains 60,000 color images of size 32×32 pixels across 10 classes.

- 50,000 training images
- 10,000 test images
- 10 object categories

The dataset includes airplanes, automobiles, birds, cats, deer, dogs, frogs, horses, ships, and trucks.

## 📂 Project Structure

```text
Deep-Learning-CIFAR10/
│
├── DL_PR4A.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

## 🔬 Experiments Performed

### 1. Data Loading, EDA & Preprocessing

- Load CIFAR-10 images and labels.
- Visualize sample images using a 5×10 image grid.
- Inspect pixel distributions using histograms.
- Normalize pixel values.
- Apply one-hot encoding to labels.

### 2. Convolution, Padding & Strides

- Perform manual convolution operations.
- Compare VALID and SAME padding.
- Understand the effect of strides on output dimensions.
- Visualize convolutional feature maps.

### 3. Pooling & CNN Architectures

- Compare MaxPooling and AveragePooling.
- Understand Flatten and GlobalAveragePooling.
- Implement LeNet-5.
- Build a custom CNN architecture.
- Analyze model parameters and architecture summaries.

### 4. CNN Training & Backpropagation

- Train CNN models using backpropagation.
- Visualize training and validation accuracy.
- Analyze training and validation loss.
- Apply EarlyStopping and ReduceLROnPlateau.
- Evaluate models using a confusion matrix and classification report.
- Visualize misclassified images.

### 5. Data Augmentation

- Apply random image transformations.
- Experiment with shifts, rotations, zooms, and flips.
- Train CNN models using ImageDataGenerator.
- Compare augmentation layers with traditional augmentation.
- Analyze the impact of augmentation on model generalization.

### 6. Transfer Learning

- Use pretrained MobileNetV2 with ImageNet weights.
- Perform feature extraction by freezing the pretrained base.
- Fine-tune the top 30 layers using a low learning rate.
- Compare transfer learning results with CNN models trained from scratch.

### 7. Model Comparison

Compare the performance of six model configurations:

- LeNet-5
- Custom CNN
- CNN with data augmentation
- CNN with Keras augmentation layers
- MobileNetV2 feature extraction
- MobileNetV2 fine-tuning

Evaluate test accuracy, parameter count, and training time.

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Deep-Learning-CIFAR10.git
cd Deep-Learning-CIFAR10
```

### 2. Create a Virtual Environment

```bash
python -m venv env
```

Activate the environment:

**Windows:**

```bash
env\Scripts\activate
```

**Mac/Linux:**

```bash
source env/bin/activate
```

### 3. Install Dependencies

Create a `requirements.txt` file:

```text
tensorflow
numpy
pandas
matplotlib
seaborn
scikit-learn
scipy
jupyter
```

Install the packages:

```bash
pip install -r requirements.txt
```

### 4. Run the Notebook

```bash
jupyter notebook DL_PR4A.ipynb
```

Execute the notebook cells sequentially.

## 📈 Model Evaluation

The project evaluates models using:

- Test Accuracy
- Training and Validation Loss
- Training and Validation Accuracy
- Confusion Matrix
- Classification Report
- Parameter Count
- Training Time

The final comparison helps understand the impact of model architecture, augmentation, and transfer learning on image classification performance.

## 🎯 Key Learnings

- How CNNs extract spatial features from images.
- How convolution, padding, and pooling work.
- How backpropagation trains neural networks.
- How data augmentation can reduce overfitting.
- How transfer learning reuses pretrained visual features.
- How fine-tuning adapts pretrained models to new datasets.
- How to compare deep learning models using evaluation metrics.

## 🔮 Future Improvements

- Build a Streamlit interface for image classification.
- Deploy the trained model as a web application.
- Experiment with deeper CNN architectures such as ResNet.
- Apply hyperparameter tuning.
- Improve model performance using learning-rate scheduling.
- Add prediction confidence scores and class-wise analysis.

## 👨‍💻 Author

Lakshay

## 📄 License

This project is created for educational and learning purposes.
