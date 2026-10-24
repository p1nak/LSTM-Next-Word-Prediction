
# 🧠 LSTM Next Word Prediction

A Deep Learning project that predicts the next word in a sentence using an LSTM (Long Short-Term Memory) neural network. The application is built with Python and Streamlit.

## 📌 Project Overview

This project uses a trained LSTM model to predict the next word based on user-provided text. It uses a tokenizer to convert text into numerical sequences and TensorFlow/Keras to generate predictions.

## ✨ Features

- Next-word prediction using an LSTM model
- Interactive web interface built with Streamlit
- Text preprocessing using a saved tokenizer
- Sequence padding using the saved maximum sequence length
- Pre-trained model for inference

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Streamlit
- Jupyter Notebook
- Pickle

## 📂 Project Structure

```text
LSTM-Next-Word-Prediction/
├── app.py
├── codefile.ipynb
├── lstm_model.h5
├── tokenizer.pkl
├── max_len.pkl
├── qoute_dataset.csv
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/LSTM-Next-Word-Prediction.git
cd LSTM-Next-Word-Prediction
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
streamlit run app.py
```

The application will open in your browser. Enter a sentence and click **Predict Next Word** to see the prediction.

## 🧠 Model Information

The application loads the following saved resources:

- `lstm_model.h5` — trained LSTM model
- `tokenizer.pkl` — fitted text tokenizer
- `max_len.pkl` — maximum sequence length used for prediction

These files are required for the current application to run.

## 📊 Dataset

The project includes `qoute_dataset.csv`, the dataset associated with the project.

## 🚀 Future Improvements

- Improve prediction accuracy
- Support multiple-word prediction
- Add model evaluation metrics
- Improve the user interface
- Deploy the application online
