# 📚 Next Word Prediction with LSTM (Shakespeare Corpus)

This project implements a Long Short-Term Memory (LSTM) Recurrent Neural Network to **predict the next word** in a sentence based on input text. It is trained on Shakespeare’s *Hamlet* and deployed via **Streamlit** for real-time interaction.

## 🧠 Model Overview

- **Architecture**: LSTM-based RNN with embedding
- **Dataset**: Text corpus from Shakespeare's *Hamlet*
- **Output**: Predicted next word
- **Frameworks**: TensorFlow, Keras, Streamlit, NumPy

---

## 📁 Project Structure

```
LSTM_RNN/
│
├── app.py # Streamlit web app
├── hamlet.txt # Training text data
├── new_model_next_word_lstm.h5 # Trained LSTM model
├── next_word_lstm.h5 # (Optional) older model
├── tokenizer.pickle # Tokenizer used for preprocessing
├── experiemnts.ipynb # Experimentation notebook
├── requirements.txt # Python dependencies
├── runtime.txt # Python version for deployment
├── .gitignore # Excludes venv and large files
├── venv/ # Virtual environment (ignored)
└── README.md # Project documentation
```

---

## 🚀 How to Run

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/LSTM_RNN.git
cd LSTM_RNN
```

2. **Create a virtual environment**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Run the model**

You can run the full model pipeline using the notebook or Python script:

```bash
python main.py
```

Or explore training and predictions in the provided `.ipynb` files.

---

## 📊 Example

Input:
"Fran. You come most carefully vpon your"
Output:
houre

---

## 📦 Dependencies

- `tensorflow`
- `keras`
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `jupyter`
- `nltk`

See `requirements.txt` for full list.

---

## 📌 Notes

- The `.h5` model files are saved versions of trained models.
- Virtual environment (`venv/`) is excluded from version control using `.gitignore`.
- This is a basic RNN version — consider upgrading to LSTM or GRU for better performance.

---


