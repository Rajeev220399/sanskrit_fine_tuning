# Sanskrit Text Generation using LSTM

A deep learning project that generates **Sanskrit text sequences** using **TensorFlow/Keras LSTM networks** with Unicode-aware NLP preprocessing and character-level sequence modeling.

---

## Project Overview

This project demonstrates how **Recurrent Neural Networks (RNNs)** and **Long Short-Term Memory (LSTM)** models can learn patterns from Sanskrit text and generate new Sanskrit-style character sequences.

The notebook includes:

* Sanskrit text preprocessing
* Unicode character handling
* Character-to-index mapping
* Sequence generation using sliding windows
* LSTM-based language modeling
* Text generation from trained sequences

---

## Features

* Sanskrit text preprocessing pipeline
* Character-level sequence modeling
* LSTM neural network for next-character prediction
* Unicode support for Indic scripts
* TensorFlow/Keras implementation
* Jupyter Notebook based experimentation

---

## Tech Stack

| Technology       | Purpose                 |
| ---------------- | ----------------------- |
| Python           | Programming language    |
| TensorFlow       | Deep learning framework |
| Keras            | Neural network API      |
| NumPy            | Numerical computation   |
| Pandas           | Data processing         |
| Matplotlib       | Visualization           |
| Jupyter Notebook | Development environment |

---

## Model Architecture

```text
Input Sequence
      ↓
Embedding Layer
      ↓
LSTM Layer
      ↓
Dense Layer
      ↓
Softmax Output
```

The model predicts the **next Sanskrit character** given a sequence of previous characters.

---

## Repository Structure

```text
sanskrit-text-generation-lstm/
│
├── notebooks/
│   └── sanskrit.ipynb
├── data/
│   └── sanskrit_corpus.txt
├── models/
│   └── lstm_sanskrit_model.h5
├── outputs/
│   └── generated_samples.txt
├── requirements.txt
├── .gitignore
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/sanskrit-text-generation-lstm.git
cd sanskrit-text-generation-lstm
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Start Jupyter Notebook:

```bash
jupyter notebook notebooks/sanskrit.ipynb
```

Run all notebook cells to:

1. Load and preprocess the Sanskrit corpus
2. Train the LSTM model
3. Generate Sanskrit text samples

---

## Example Workflow

```python
# Load data
text = load_corpus()

# Preprocess
X, y = create_sequences(text)

# Train model
model.fit(X, y)

# Generate text
generate_text(model, seed_text, length=200)
```

---

## Project Highlights

* Built a **character-level Sanskrit language model**
* Implemented **Unicode-aware preprocessing** for Indic scripts
* Trained an **LSTM network for sequence prediction**
* Applied **Generative AI concepts** using recurrent neural networks
* Structured the project for **future production deployment**

---

## Future Improvements

* Transformer-based Sanskrit text generation
* IndicNLP tokenizer integration
* Fine-tuning on classical Sanskrit literature
* Streamlit web application
* REST API deployment using FastAPI

---

## Requirements

Create a `requirements.txt` file with:

```txt
tensorflow
numpy
pandas
matplotlib
jupyter
scikit-learn
```

---

## GitHub Topics

Add these topics to improve repository visibility:

```text
tensorflow keras lstm nlp text-generation sanskrit deep-learning python generative-ai machine-learning
```

## License

This project is licensed under the **MIT License**. Feel free to use, modify, and share it for educational and research purposes.
