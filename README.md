# Next Word Predictor Using LSTM

## Project Overview

The **Next Word Predictor** is a Deep Learning-based application that predicts the next possible word based on the text entered by the user.

This project uses a Recurrent Neural Network (RNN), specifically an **LSTM (Long Short-Term Memory)** model, to understand sequential patterns in text and generate context-based word predictions.

The model processes input text using a trained tokenizer and predicts the next word based on previously learned language patterns.

## Features

- Predicts the next word based on user input.
- Uses an LSTM-based deep learning model.
- Text preprocessing using Tokenization.
- Sequence padding for consistent input length.
- Uses a pre-trained model for predictions.
- Simple and user-friendly interface.

## Technologies Used

- Python
- TensorFlow / Keras
- LSTM (Long Short-Term Memory)
- NumPy
- Pickle
- Streamlit (if used for the application interface)

## Project Structure

```text
Next_word_pred/
│
├── app.py
├── lstm_model.h5
├── tokenizer.pkl
├── max_len.pkl
├── requirements.txt
├── README.md
└── .gitignore
```

## How It Works

1. User enters a sentence or text.
2. The tokenizer converts the text into numerical sequences.
3. The input sequence is padded to the required length.
4. The trained LSTM model processes the sequence.
5. The model predicts the next word.
6. The predicted word is displayed to the user.

## Installation and Setup

**1. Clone the repository**

```bash
git clone https://github.com/laveeshchauhan26-cmd/Next-Word-Predictor.git
```

**2. Navigate to the project directory**

```bash
cd Next-Word-Predictor
```

**3. Create a virtual environment**

```bash
python -m venv .venv
```

**4. Activate the environment (Windows)**

```bash
.venv\Scripts\activate
```

**5. Install dependencies**

```bash
pip install -r requirements.txt
```

**6. Run the application**

If your application uses Streamlit:

```bash
streamlit run app.py
```

## Model Files

| File | Description |
|---|---|
| `lstm_model.h5` | Trained LSTM deep learning model |
| `tokenizer.pkl` | Saved tokenizer for text preprocessing |
| `max_len.pkl` | Saved maximum sequence length |

## Learning Outcomes

- Understanding Recurrent Neural Networks.
- Working with LSTM architectures.
- Text preprocessing and tokenization.
- Sequence padding and prediction.
- Loading and using trained deep learning models.
- Building an end-to-end NLP application.

## Future Improvements

- Predict multiple next words.
- Improve prediction accuracy using larger datasets.
- Experiment with advanced NLP architectures.
- Deploy the application online.

## Author

**Laveesh Kumar**

Aspiring AI/ML Engineer

GitHub: https://github.com/laveeshchauhan26-cmd


