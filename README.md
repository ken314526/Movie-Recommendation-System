# Movie Recommendation System

1. [Overview](#overview)
1. [Requirements](#requirements)
1. [Usage](#usage)
    - [Clone the repository](#usage)
    - [Extract the dataset files](#usage)
    - [Run the Jupyter Notebook](#usage)
    - [Run the Streamlit app](#usage)
1. [Files and Directory Structure](#files-and-directory-structure)

## Overview

This project is a movie recommendation system developed using Python and Machine Learning. It utilizes the power of various libraries such as NumPy, Pandas, NLTK, Scikit-learn, and more. The recommendation system is built on a dataset available in the "dataset" folder. Users are required to extract the files from the dataset folder and follow the instructions to run the system.

## Requirements
Make sure you have the following dependencies installed:

- NumPy
- Pandas
- NLTK
- Scikit-learn
- Requests
- Streamlit
- dotenv

You can install these dependencies using the following command:

```bash
pip install numpy pandas nltk scikit-learn requests streamlit python-dotenv
```

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/ken314526/Movie-Recommendation-System.git
    cd movie-recommendation-system
    ```

1. Extract the dataset files:
    Extract the contents of the `dataset` folder and place them in the root directory.

1. Run the Jupyter Notebook:
    ```bash
    jupyter notebook movie-recommendation.ipynb
    ```
    This notebook contains the machine learning model and data processing steps. Follow the instructions in the notebook to train the model.

1. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```
Access the movie recommendation system through your browser at http://localhost:8501.

## Files and Directory Structure
- `dataset/:` Contains the dataset files.
- `movie-recommendation.ipynb:` Jupyter Notebook with the machine learning model.
- `app.py:` Streamlit app for the movie recommendation system.
