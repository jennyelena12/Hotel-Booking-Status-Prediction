# Hotel Booking Status Prediction

## Overview

Hotel Booking Status Prediction is a machine learning web application built using Streamlit. The application predicts whether a hotel booking will be canceled or not based on booking details provided by the user.

The application uses a pre-trained Random Forest classification model. Users can enter information such as the number of guests, room type, meal plan, lead time, market segment, previous booking history, and special requests to receive a cancellation prediction and probability.

## Features

* Predict whether a hotel booking will be canceled or not
* Interactive booking input form using Streamlit
* Random Forest classification model
* Automatic model download from Google Drive
* Input preprocessing for categorical features
* Prediction probability display
* Booking information validation
* Responsive wide-layout interface

## Tech Stack

* Python
* Streamlit
* Pandas
* NumPy
* Scikit-learn
* Google Drive / gdown
* Pickle

## Project Structure

```text
.
├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
