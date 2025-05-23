# Cardio-Monitor (Heartmatters) Project Overview
This project is a heart disease prediction web application that uses machine learning models to assess a user's risk of developing heart disease with 92% accuracy.

## Project Purpose
Cardio-Monitor helps users determine their risk of developing heart disease through early detection and monitoring. The system processes user health data inputs and provides risk assessments using machine learning models.

## Tech Stack

Backend

Python - Core programming language
Flask - Web application framework
MongoDB - Database for storing patient data
Scikit-learn, XGBoost - Machine learning libraries for model development
Pandas, NumPy - Data manipulation and processing
Matplotlib, Seaborn - Data visualization

Frontend

HTML/CSS - Web interface
Bootstrap - Framework for responsive design

## Project Structure

Core Files
app.py: Main Flask application with routes and web server setup
modelbuild.py: Handles machine learning model building, data processing, and MongoDB connectivity
database.py: Likely manages database operations (not fully visible in snippets)
prediction.py: Contains prediction logic for the heart disease models
visualization.py: Creates data visualizations for the web interface

## Templates

home.html: Landing page with information about heart disease and likely input form
result.html: Shows prediction results to users with visualization
Research & Development
Jupyter Notebooks:
Heart_Disease_Prediction.ipynb
Heart Disease Detection Using Big Data Approach-best accuracy-git.ipynb
Contain exploratory data analysis, model development, and testing

## Data Source

The project uses heart disease datasets from the UCI Machine Learning Repository.

## How to Run

Based on the codebase structure, you would likely run this application as follows:

Ensure you have all dependencies installed:

Set up MongoDB (connection details are in the code)

Run the Flask application:

Access the web interface through a browser (likely http://localhost:5000)

Input health data through the interface to get heart disease risk prediction

The application appears to take user health parameters as input and returns a prediction about heart disease risk based on machine learning models trained with over 90% accuracy.

## Output

The system provides a prediction on whether a user is at risk of developing heart disease based on their input health metrics, displaying results on the result.html page with visualizations.