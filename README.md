# SMS Spam Detection System

## Project Overview

The **SMS Spam Detection System** is a machine learning-based project that classifies SMS messages as spam or ham (non-spam). It aims to provide an efficient way to filter out spam messages, improving user experience and security.

## Features

- **Data Cleaning**: Removes special characters, stop words, and other irrelevant data from messages.
- **Exploratory Data Analysis (EDA)**: Visualizations to understand data distributions and patterns.
- **Data Preprocessing**: Converts text into numerical features using techniques like TF-IDF.
- **Machine Learning Models**: Implements various classification algorithms to achieve high accuracy.
- **Streamlit Web Interface**: Provides a user-friendly web interface for real-time SMS classification.

## Dataset

The dataset used in this project is sourced from Kaggle:

- Dataset: [SMS Spam Collection](https://www.kaggle.com/uciml/sms-spam-collection-dataset)
- It contains 5,574 SMS messages labeled as "spam" or "ham."

## Technologies Used

- **Programming Languages**: Python
- **Libraries**:
  - `numpy`, `pandas`: Data manipulation and analysis
  - `nltk`: Natural language processing
  - `matplotlib`, `seaborn`: Data visualization
  - `sklearn`: Machine learning model building and evaluation
  - `streamlit`: Web application framework
- **Model Persistence**: `pickle`

## How to Run the Project

### Prerequisites

- Python
- Required libraries

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/anuragkrishna14/SMS-Spam-Detection-System.git
   cd SMS-Spam-Detection-System
   ```
2. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```
3. Access the web application at `http://localhost:8501`.

## Acknowledgments

Special thanks to Kaggle for the dataset and to the open-source community for providing robust machine learning tools and frameworks.

