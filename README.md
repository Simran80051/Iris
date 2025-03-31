# Iris

# Iris Flower Prediction App

This is a machine learning-based web app built with Streamlit that predicts the species of an Iris flower based on its features. It uses a pre-trained Random Forest Classifier to make predictions. The app is interactive and allows users to input values for four features: sepal length, sepal width, petal length, and petal width. The app will then predict the species of the Iris flower.

## Demo

You can access the live demo of the app here: [Iris Flower Prediction Demo](https://iris-dashboard1.streamlit.app/)

## Project Overview

This project is a Streamlit web app that uses a **Random Forest Classifier** model to predict the species of an Iris flower based on its measurements. The model is pre-trained using the famous **Iris dataset** available in the scikit-learn library.

### Features:
- Input four flower measurements (sepal length, sepal width, petal length, petal width) via sliders.
- Predict the species of the flower (Setosa, Versicolor, or Virginica) based on these measurements.
- Display the prediction probability for each species.

## Technologies Used

- **Streamlit**: A framework for creating web applications for data science projects.
- **Scikit-learn**: A Python library used for machine learning, used here to create and train the Random Forest Classifier.
- **Pandas & Numpy**: Used for data manipulation and processing.
- **Joblib**: Used to save and load the pre-trained machine learning model.

## Getting Started

To run this project on your local machine or deploy it, follow the instructions below.

### Prerequisites

Ensure you have Python 3.x installed on your machine.

You also need to install the following Python packages:

- `streamlit`
- `scikit-learn`
- `joblib`
- `pandas`
- `numpy`

You can install all dependencies by running the following command:

```bash
pip install streamlit scikit-learn joblib pandas numpy

### Running the App Locally
Once the required dependencies are installed, run the app locally using:
streamlit run app.py

### Deployment
To share the app publicly, we use localtunnel or other deployment platforms like Streamlit Community Cloud, AWS, or Google Cloud.

Install Localtunnel:
npm install -g localtunnel
Run the app in the background:

streamlit run app.py &>/content/logs.txt & curl ipv4.icanhazip.com
Expose the port with Localtunnel:

npx localtunnel --port 8501
Once the app is running, you’ll receive a public URL from localtunnel, like https://your-url.loca.lt.

For a more professional deployment, consider using Streamlit Community Cloud or cloud services like AWS, Google Cloud, or Azure.

Creating requirements.txt
You can generate the requirements.txt file using the following command:

pip freeze > requirements.txt
Alternatively, you can use pipreqs to auto-generate the file:


pip install pipreqs
pipreqs /path/to/your/project
Deployment on Streamlit Community Cloud
Push your code to a GitHub repository.

Visit Streamlit Community Cloud.

Sign in with your GitHub account and link your repository.

Streamlit will automatically detect and deploy your app.
