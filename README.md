# -Speaker-Recognition-using-LSTM-and-MFCC-Features

📌 Project Overview
This project focuses on identifying speakers from audio clips using MFCC feature extraction and an LSTM-based neural network. The dataset comprises ~80 minutes of audio, featuring voices from 6 students (primary recordings) and 2 celebrities (audio extracted from YouTube). The model effectively learns voice patterns and achieves strong performance on unseen audio samples.

🎯 Key Features
Audio Collection & Processing: 8 voice recordings (~10 mins each), segmented into manageable chunks using pydub.

Feature Extraction: Mel-Frequency Cepstral Coefficients (MFCCs) extracted via librosa to represent voice signatures.

Deep Learning Architecture: Built a Sequential LSTM model in Python using TensorFlow/Keras.

Performance: Achieved 91% accuracy and 91% weighted F1 score in speaker classification.

Evaluation & Visualization: Assessed model with a confusion matrix and tracked training vs. validation loss curves.

🛠️ Tech Stack
Python

Pydub

Librosa

NumPy / Pandas

TensorFlow / Keras

Matplotlib / Seaborn

🚀 Results
Accuracy: 91%

F1 Score (Weighted): 91%

Reliable speaker prediction from unseen voice samples
