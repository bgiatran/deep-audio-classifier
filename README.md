# Deep Audio Classifier: Capuchin Bird Call Detection

This project implements a deep learning pipeline to classify audio signals, specifically distinguishing between Capuchin bird calls and other environmental sounds. It was created as a beginner-friendly introduction to bioacoustics and deep learning in audio.

> Built using TensorFlow, Librosa, and a Conv1D-based neural network to analyze spectrograms and recognize distinct vocal patterns.

---

## Project Overview

Capuchin birds produce unique audio signatures in the wild. Detecting their calls has applications in:

- Wildlife monitoring 
- Conservation efforts 
- Automated biodiversity sensing 

This notebook demonstrates:
- Audio preprocessing with Mel-spectrograms
- Feature extraction using `librosa`
- Model training with TensorFlow
- Evaluation of classification performance
- Predictions on new unseen audio files

---

## Tech Stack

| Tool        | Purpose                                  |
|-------------|-------------------------------------------|
| Python      | Programming Language                      |
| TensorFlow  | Deep Learning Framework                   |
| Librosa     | Audio processing & feature extraction     |
| NumPy/Pandas| Data manipulation                         |
| Matplotlib  | Visualizations                            |
| Jupyter     | Interactive environment for prototyping   |

---

## Features Implemented

- Audio loader and waveform visualizer
- Mel spectrogram extractor
- Custom data preprocessing pipeline
- Binary classification model
- Test predictions on unseen files

---

## Future Improvements
- Add multi-class classification (other bird species)
- Improve robustness with data augumentation
- Deploy model as a Streamlit app for real-time classification
- Integrate spectogram caching to reduce runtime

## Dataset Disclaimer

⚠️ The audio files used in this notebook were too large to include directly in the GitHub repository or this workspace.

- You can download the Capuchin Bird Calls dataset from **[Kaggle](https://www.kaggle.com/datasets/)**.
- Make sure your local folder structure matches the expected `audio/` folder layout for the code to run correctly.

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/bgiatran/deep-audio-classifier.git
cd deep-audio-classifier
