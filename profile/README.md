# FreshMate - Capstone Project Bangkit Team C242-PS007

## Overview

This project intends to help users determine fruit quality by creating a machine-learning model that can classify fruit ripeness into three categories: "unripe," "ripe," and "rotten." The classification procedure uses a Convolutional Neural Network (CNN) architecture with a pre-trained ResNet50 model implemented with TensorFlow and other related libraries.

![Mockups](https://github.com/FreshMate-Fruit-Ripeness-Detection/.github/blob/46529c97d572c11ea9b7334fdb3d4e434c187158/mockup.png)


## Motivation

Fruit waste is frequently caused by incorrectly classifying fruit ripeness during the sorting and grading process. Incorrect evaluations can result in the premature dumping of underripe or overripe fruits, amounting to significant food waste. Using visual analysis of image, our model is intended to assist users in determining the ripeness category of fruits, such as unripe, ripe, or rotten.

## Project Scope

The primary objective of this project is to develop a fruit ripeness classification system with the following features:
- The model is designed to classify fruit ripeness in images uploaded by users into three categories: unripe, ripe, or rotten.
- Provide users with detailed nutritional information for each identified fruit, such as vitamins and minerals.
- Integrate a user-friendly interface where users can upload a fruit photo and instantly receive ripeness status.

## Technology Stack

### Machine Learning
- Framework: TensorFlow
- Architecture: Convolutional Neural Networks (CNN), using a pre-trained ResNet50 model
- Programming Language: Python
- Development Environment: Google Colab & Jupyter Notebook

### Android Development
- Design Tool: Figma
- Programming Language: Kotlin
- Networking: Retrofit
- Architecture Application : MVVM (Model - View - View Model).
- Development Tools : Android Studio
- Layouting : XML

### Cloud
- Cloud Provider: Google Cloud
- Programming Language: PHP With Framework Laravel And Python For Machine Learning Services
- Backend Support: Server We Use a Compute Engine for deploy a laravel and building a API, For the python services we use a cloud run to running a uvicorn server, For the database we using mysql in compute engine same with a laravel server, for the save a photo, we using a cloud storage bucket
- To deploy our Machine Learning model, we use Cloud Run and FastAPI for the model API.
- This is the link project https://github.com/FreshMate-Fruit-Ripeness-Detection/api"

## Download APK
[FreshMate Apk]..()


## Dataset

The dataset used to train the model was obtained through image scraping, uploaded to Kaggle, and then downloaded from a public Kaggle URL. [Dataset](https://www.kaggle.com/datasets/dudinurdiyansah/fruit-ripeness-classifier). 

## Implementation

The system aims to create technology that can capture photos of fruit, process them with a trained CNN model, and then predict whether the fruit is unripe, ripe, or rotten. An Android app with a Google Cloud backend will deliver real-time predictions and updates.

## Future Enhancements

Future enhancements may include:
- Dataset Addition with Fruit Types: Adding multiple types of fruits to the dataset enhances data diversity while also assuring that the model can recognize more categories of fruits with greater accuracy.
- Fruit Health Analysis: Besides recognizing ripeness and spoiling levels, the model can detect fruit health issues such as illness or damage.
- Action Recommendation Feature: Included features that offer specific advice for each fruit group, such as:
  - Unripe: Storage guidance until the fruit reaches the optimal ripeness level.
  - Ripe: Recommendations on the best time to consume or sell.
  - Rotten: Advice on recycling options or proper disposal methods.

## Team Members

| ID           | Name                            | Institution                              | Role                                 | Status  |
|--------------|---------------------------------|------------------------------------------|--------------------------------------|---------|
| A133B4KY2273 | Lilo Puji Pratama               | Politeknik Negeri Samarinda              | Project Manager & Mobile Development | Active  |
| A420B4KY3398 | Nouval Zaki                     | STMIK Widya Cipta Dharma                 | Mobile Development                   | Active  |
| M271B4KY1187 | Dudi Nurdiyansah                | Universitas Multimedia Nusantara Jakarta | Machine Learning                     | Active  |
| M271B4KY3981 | Ryan Ferdinand Andyson          | Universitas Multimedia Nusantara Jakarta | Machine Learning                     | Active  |
| M322B4KY2442 | Maulida Kiatuddin               | Universitas Syiah Kuala                  | Machine Learning                     | Active  |
| C420B4KY3069 | Muhammad Rizky Wijaya           | STMIK Widya Cipta Dharma                 | Cloud Computing                      | Active  |
| C137B4KY3092 | Muhammad Surya Wijaya           | Politeknik Pertanian Negeri Samarinda    | Cloud Computing                      | Active  |

## Conclusion

This project is a strategic step toward using machine learning to address food waste within the agriculture sector, specifically in the fruit supply chain. Our goal is to minimize food waste by providing precise predictions of fruit ripeness, eliminating the uncertainty that often comes with assessing whether fruit is ripe or not.
