# 🎙️ Voice Classification System

This project was built for our Introduction to AI class. It is a machine learning pipeline that can identify a speaker based on a short audio clip. 

## 🧠 How it Works
1. **Feature Extraction:** We use `librosa` to extract Mel-Frequency Cepstral Coefficients (MFCCs) from raw `.wav` audio files. This creates a unique numerical "fingerprint" for each voice.
2. **Model Training:** We trained a Random Forest Classifier using `scikit-learn` to recognize the patterns in these fingerprints.
3. **User Interface:** We deployed the model locally using `Gradio` so users can record their voice in real-time and see the prediction.

## 🛠️ Tech Stack
* **Python** (Core language)
* **Librosa** (Audio processing)
* **Scikit-Learn** (Machine Learning model)
* **Pandas & NumPy** (Data manipulation)
* **Gradio** (Web UI)

## 🚀 How to Run Locally
1. Clone this repository.
2. Install the required libraries: `pip install -r requirements.txt`
3. Run the Gradio app: `python app.py`
4. Open the provided local URL in your browser, click record, and speak!
