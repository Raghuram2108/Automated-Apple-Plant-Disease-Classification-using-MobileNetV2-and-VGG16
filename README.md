# 🍎 Automated Apple Plant Disease Classification with MobileNetV2 and VGG16
This project implements a deep learning-based system to classify apple plant leaf diseases using MobileNetV2 and VGG16, two powerful pre-trained convolutional neural network architectures. The goal is to support early detection and management of crop diseases using AI-based solutions.

# 📁 Project Structure
Apple_Plant_Disease_with_MobileNetV2_and_VGG16 Final.ipynb: Main Jupyter Notebook containing the end-to-end implementation.

  Data Loading and Preprocessing
  Data Augmentation
  Model Building using MobileNetV2 and VGG16
  Model Evaluation and Accuracy Visualization

# 🔍 Dataset
The dataset used includes labeled images of:

  Apple Scab
  
  Black Rot
  
  Cedar Apple Rust
  
  Healthy Apple Leaves
  
Dataset Source: https://www.kaggle.com/datasets/emmarex/plantdisease

# 🧠 Models Used
✅ MobileNetV2
    Lightweight and efficient CNN designed for mobile and edge devices.
    Transfer learning with include_top=False and custom classifier layers.
    
✅ VGG16
    Deeper architecture with a series of convolution and max-pooling layers.
    Modified classifier layers appended for disease classification.

# 📊 Evaluation Metrics
  Accuracy
  
  Loss

# 🧰 Technologies Used 
  Python
  
  TensorFlow / Keras
  
  Numpy, Matplotlib, Seaborn
  
  Sklearn

# 🤖 Use Case
This model can serve as a prototype for real-world deployment in agricultural decision support systems, where farmers or agricultural officers can upload leaf images and get real-time disease predictions.
