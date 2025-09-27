🎤 Speech Emotion Recognition for Children Before Surgery (CNN + LSTM)
📌 Overview

This project focuses on Speech Emotion Recognition (SER) for children in a pre-surgical environment.
The goal is to automatically detect and classify the emotional state of a child (such as happy, sad, anxious, neutral) from voice recordings using deep learning models (CNN + LSTM).

By recognizing emotional states, healthcare professionals can:

Provide better emotional support to children,

Reduce surgical anxiety,

Improve overall patient experience.

⚙️ Features

Preprocessing of raw audio signals (MFCC feature extraction).

Deep learning model combining:

Convolutional Neural Networks (CNN) → for local feature extraction.

Long Short-Term Memory (LSTM) networks → for temporal sequence learning.

Multi-class classification of emotions.

Evaluation metrics: Accuracy, Precision, Recall, F1-Score.

🗂️ Dataset

Speech samples of children recorded before surgery.

Each audio sample is labeled with the corresponding emotion class.

Preprocessing includes:

Noise reduction,

MFCC feature extraction,

Normalization.

(Due to privacy concerns, dataset is not included. Replace with your dataset details or reference if available.)

🏗️ Model Architecture

Input Layer – MFCC features from speech signals.

CNN Layers – Extract high-level acoustic features.

LSTM Layers – Capture sequential temporal dependencies.

Dense Layer – Fully connected classifier.

Softmax Output – Predict emotion category.

🚀 Installation

Clone the repo and install dependencies:

git clone https://github.com/your-username/speech-emotion-recognition.git
cd speech-emotion-recognition
pip install -r requirements.txt

▶️ Usage

Place your dataset in the data/ directory.

Extract MFCC features:

python preprocess.py


Train the model:

python train.py


Evaluate the model:

python evaluate.py

📊 Results

Achieved XX% accuracy on the test dataset.

Model performs best in detecting [insert strongest class].

Confusion matrix and classification report provided for analysis.

🔮 Future Improvements

Expand dataset size and diversity.

Explore transformer-based architectures.

Real-time deployment in hospital environments.

📜 License

This project is licensed under the MIT License – see the LICENSE
 file for details.
