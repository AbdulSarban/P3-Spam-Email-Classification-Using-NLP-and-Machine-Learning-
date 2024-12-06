# Email Spam Classification Using NLP and Machine Learning

This project is a **Machine Learning application** developed using Natural Language Processing (NLP) and Machine Learning techniques to classify emails as **Spam** or **Not Spam (Ham)**. The application provides an interactive web interface using **Streamlit** for real-time email classification.

## Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Setup and Installation](#setup-and-installation)
- [How to Use](#how-to-use)
- [Project Demo](#project-demo)
- [Directory Structure](#directory-structure)
- [Future Enhancements](#future-enhancements)
- [License](#license)

---

## Overview

This project demonstrates how NLP techniques such as **text vectorization** (using `CountVectorizer`) and **machine learning models** can be used to classify emails as spam or ham. The application is deployed locally using **Streamlit**, allowing users to input email text and classify it on the fly.

---

## Technologies Used

- **Programming Language:** Python 3.8+
- **Libraries:**
  - [`Streamlit`](https://streamlit.io/): For creating the web interface.
  - [`scikit-learn`](https://scikit-learn.org/): For text vectorization and machine learning model.
  - [`pickle`](https://docs.python.org/3/library/pickle.html): For saving and loading pre-trained models and vectorizers.
  - [`pandas`](https://pandas.pydata.org/): For data manipulation and analysis.
- **Machine Learning Model:** Trained using `CountVectorizer` and `Multinomial Naive Bayes`.

---

## Features

- **Email Classification:** Enter email text to check whether it is spam or ham.
- **Interactive Web Interface:** Built using **Streamlit** for user-friendly interaction.
- **Pre-trained Model:** Leverages a pre-trained model for fast predictions.
- **Real-time Feedback:** Displays results instantly.

---

## Setup and Installation

Follow these steps to run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/AbdulSarban/P3-Spam-Email-Classification-Using-NLP-and-Machine-Learning.git
cd P3-Spam-Email-Classification-Using-NLP-and-Machine-Learning
