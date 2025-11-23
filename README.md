# Applied Data Science Course 🚀

This repository contains my notes, practices, and solutions for the **Applied Data Science Course** offered by **Sharif University of Technology (EE-879)**. The content covers various data science concepts, hands-on exercises, and solutions to course assignments.

---

## Course Information
For more details about the course, visit the official course website:
[**Applied Data Science - Sharif University of Technology, Spring 2025**](https://saloot.github.io/ADS2025/) or
[**Saloot GitHub**](https://github.com/saloot/ADS2025)

## Course Topics
The course covers the following key topics:

1. 📚 **Introduction to Pandas**  
2. 🧹 **Data Cleaning and Preprocessing**  
3. 📊 **Data Visualization**  
4. ⚙️ **Feature Engineering and Dimensionality Reduction**  
5. 🎯 **Different Problem Types and Accuracy Measures**  
6. 📈 **Regression Methods**  
7. 🔍 **Classification Methods**  
8. 🌂 **Multiclass/Multilabel Classification and Boosting**  
9. 🧠 **Neural Networks**  
10. 🚀 **Deep Learning**  
11. 🖼️ **Deep Learning Application: Image Classification**  
12. 🤖 **Generative AI**  

## Datasets
The following datasets are utilized in this repository:
- 🚗 [Car Features and MSRP](https://www.kaggle.com/datasets/CooperUnion/cardataset)
- 🧠 [Stroke Prediction](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
- 🏠 [Ames Iowa Housing Data](https://www.kaggle.com/datasets/marcopale/housing)
- 🏨 [Hotel Booking Demand](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand/data)
- 🥑 [Avocado Prices](https://www.kaggle.com/datasets/neuromusic/avocado-prices)



## Assignments

### Assignment 1: Introduction to Pandas 🐼📊
- Complete Kaggle mini tutorial on Pandas:
  https://www.kaggle.com/learn/pandas
- Choose a dataset for future assignments.

---

### Assignment 2: Exploratory Analysis and Data Cleaning 🔍🧹
- Perform EDA, cleaning, and preprocessing on the Stroke Prediction dataset:
  https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset
- Complete Kaggle mini tutorial on Data Cleaning:
  https://www.kaggle.com/learn/data-cleaning

---

### Assignment 3: Data Visualization + Web Scraping 📈🎨🕸️
- Data visualization on the Hotel Booking Demand dataset:
  https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand/data
- Kaggle mini tutorial on Data Visualization:
  https://www.kaggle.com/learn/data-visualization
- Web-scrape 50 Samand cars from bama.ir (price, mileage, color, year, transmission, description)

---

### Assignment 4: Feature Engineering 🧱⚙️
- Create new features (ratio, binning, functional transforms, combining columns)
- Create date/time features
- Perform aggregation and counts
- Feature selection using Mutual Information
- PCA for dimensionality reduction
- Write explanation: When is feature engineering optional vs necessary?
- Optional: Kaggle mini tutorial on Feature Engineering

---

### Assignment 5: Accuracy Measures 🎯📏
- Compute regression metrics: MSE, MAE, MAPE, R2
- Compute binary classification metrics: Precision, Recall, F1
- Compute multi-class metrics: per-class Precision and Recall, macro/micro/weighted F1
- Answer question about multi-label metrics (football example)
- Use models or random predictions for metric evaluation

---

### Assignment 6: Regression Methods 📉🤖
- Train and evaluate:
  - Linear Regression
  - Kernel Regression
  - Logistic Regression
  - Ridge Regression
  - LASSO Regression
- Explain the kernel trick

---

### Assignment 7: Binary Classification Methods ⚡📘
- Train and evaluate:
  - Logistic Regression
  - SVM (linear + kernel)
  - KNN (implement + tune K)
  - Decision Trees (implement + tune depth)
  - Random Forest
- Explain three regularization techniques for decision trees
- Bonus: Achieve F1 > 0.9 on diabetes dataset

---

### Assignment 8: Multiclass Classification Methods 🎨🔢
- Implement and evaluate:
  - Multiclass SVM
  - Multiclass Logistic Regression (OVR, multinomial, log loss)
  - Multiclass KNN (implement + tune K)
  - Multiclass Decision Trees
  - Boosting methods: XGBoost, LightGBM, Adaboost/Catboost
- Perform grid search on one boosting method
- Explain how KNN and Decision Trees extend to multi-label classification
- Bonus: Achieve F1 > 0.6 on 12-class player-position dataset

---

### Assignment 9: Neural Networks 🧠💡
- Train and evaluate:
  - Scikit-Learn MLP (classification + regression)
  - Keras 4-layer sequential network (classification + regression)
  - PyTorch 4-layer network (classification + regression)
  - Keras 4-layer non-sequential network
- Explain why neural networks are powerful and difficult to design
- Bonus: RNN (3-layer) if dataset includes time-series

---

### Assignment 10: Deep Neural Network Tuning 🚀🔧
- Tune Keras network using at least 5 options:
  - Optimizer
  - Learning rate
  - Learning rate decay
  - Batch size
  - Activation functions
  - Weight initialization
  - Network depth and width
  - L1/L2 weight regularization
  - L1/L2 activity regularization
  - Dropout rate
- Explain why deeper networks are harder to train
- Use 4-fold cross validation for evaluation

---

### Assignment 11: CNNs, Transfer Learning, and Data Augmentation 🖼️📦🤝
- Build CNN with at least two convolutional layers
- Tune:
  - Convolution kernel size
  - Convolution stride
  - Pooling size
  - Pooling stride
- Perform data augmentation using ImageGenerator
- Perform transfer learning using two pretrained models (VGG19, ResNet, EfficientNet)
- Explain impact of receptive field size on performance

---

### Assignment 12: Autoencoders and Generative Models 🎛️✨🧬
- Build and train:
  - Dense autoencoder
  - Convolutional autoencoder
  - Denoising autoencoder
- Train a GAN on CIFAR-10 dataset
- Use OpenAI API to generate:
  - An image
  - An audio voice reading generated text
- Explain the adversarial learning process
- Bonus: Build a Variational Autoencoder on Fashion-MNIST
    
## Practices

- Practice 1: Explore pandas features on **[Car Features and MSRP](https://www.kaggle.com/datasets/CooperUnion/cardataset) dataset.**

Maybe I will practice more in the future :).

## Repository Structure
- **Notes** → Summarized lecture notes & key concepts
- **Practices** → Hands-on coding exercises & projects
- **Assignments** → Solutions to course assignments

---