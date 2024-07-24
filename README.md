## Introduction

This repository contains a Flask web application for crop recommendation based on machine learning. The app uses a RandomForestClassifier to suggest the best crops to grow based on various input features.

## Dependencies

To run the Jupyter Notebook and the Flask web application, you need the following dependencies:

- Python 3.12
- Jupyter Notebook
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- Flask

You can install these dependencies using pip:

```
pip install jupyter pandas numpy seaborn matplotlib scikit-learn flask
```

## Dataset
The dataset used for training the model should contain the following columns:

* N: Nitrogen content in the soil
* P: Phosphorous content in the soil
* K: Potassium content in the soil
* temperature: Average temperature
* humidity: Average humidity
* ph: pH value of the soil
* rainfall: Average rainfall
* label: Crop name

## Usage

1. Clone the repository:

```
git clone https://github.com/Harsh-1306/Crop_Recommendation_Project.git
cd crop_app
```

2. Run the Jupyter Notebook:

```
jupyter notebook crop_recommendation.ipynb
```

3. Follow the instructions in the notebook for data preprocessing, model training, and evaluation.

4. Run the Flask web application:

```
python app.py
```

## Model Evaluation

The notebook includes evaluations of following machine learning models:

- Bernoulli Naive Bayes
- Gaussian Naive Bayes
- LogisticRegression
- DecisionTreeClassifier
- KNeighborsClassifier
- SVM
- AdaBoostClassifier
- ExtraTreesClassifier
- RandomForestClassifier

## Features

- User-friendly web interface built with Flask
- Predicts the best crop to grow based on soil and weather conditions
- Uses RandomForestClassifier for high accuracy predictions
- Clean and modular code for easy maintenance and updates

## Screenshots

![image](https://github.com/Harsh-1306/Crop_Recommendation_Project/blob/main/Screenshots/image1.png)
![image](https://github.com/Harsh-1306/Crop_Recommendation_Project/blob/main/Screenshots/image2.png)
![image](https://github.com/Harsh-1306/Crop_Recommendation_Project/blob/main/Screenshots/image3.png)

## Technology
<div align="center">
	<code><img width="50" src="https://user-images.githubusercontent.com/25181517/183914128-3fc88b4a-4ac1-40e6-9443-9a30182379b7.png" alt="Jupyter Notebook" title="Jupyter Notebook"/></code>
	<code><img width="50" src="https://user-images.githubusercontent.com/25181517/183423507-c056a6f9-1ba8-4312-a350-19bcbc5a8697.png" alt="Python" title="Python"/></code>
	<code><img width="50" src="https://user-images.githubusercontent.com/25181517/183423775-2276e25d-d43d-4e58-890b-edbc88e915f7.png" alt="Flask" title="Flask"/></code>
	<code><img width="50" src="https://github.com/marwin1991/profile-technology-icons/assets/76012086/4ec200c2-acdf-4c42-b419-cd49cba3d09f" alt="NumPy" title="NumPy"/></code>
	<code><img width="50" src="https://github.com/marwin1991/profile-technology-icons/assets/76012086/24b02d77-2f28-43c7-b5d6-e15e3395851b" alt="Pandas" title="Pandas"/></code>
</div>


## Contributing
Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.










