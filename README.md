# Next Word Predictor: Hamlet LSTM-RNN

This project is a deep learning-based web application that predicts the next word in a sequence of text. The model is a **Long Short-Term Memory (LSTM)** neural network trained on the text of William Shakespeare's *Hamlet*.

## 🛠️ Features

* **Deep Learning Model**: Utilizes an LSTM-RNN architecture for sequence prediction.
* **Natural Language Processing**: Employs word tokenization and padding to process input text.
* **Interactive Interface**: A user-friendly UI built with Streamlit for real-time word generation.
* **Early Stopping**: The model was trained with early stopping to prevent overfitting and ensure better generalization.

## Tech Stack

* **Frontend:** [Streamlit](https://streamlit.io/)
* **Machine Learning Framework:** [TensorFlow / Keras](https://www.tensorflow.org/)
* **Data Manipulation:** Pandas, NumPy
* **Preprocessing:** Scikit-Learn

## Installation & Setup

To run this project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/SidoJain/Next-Word-Prediction-LSTM-RNN.git
    ```

2. **Create a virtual environment:**

    ```bash
    python -m venv .venv
    source .venv/Script/activate
    ```

3. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Launch the app:**

    ```bash
    streamlit run app.py
    ```
