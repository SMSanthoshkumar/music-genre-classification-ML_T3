# music-genre-classification-ML_T3

Music Genre Classification system using Deep Learning that analyzes audio files, extracts Mel Spectrogram features, and predicts music genres through an interactive Streamlit-based web interface.

## Project Overview
This project is designed to classify music genres automatically using Deep Learning techniques. The system processes audio files, extracts Mel Spectrogram features, and predicts the genre of the uploaded song through a Streamlit-based web application.

## Features
- Upload audio files for prediction
- Extract Mel Spectrogram features
- Deep Learning based genre classification
- Interactive Streamlit web interface
- Fast and accurate music genre prediction

## Genres Supported
- Blues
- Classical
- Country
- Disco
- HipHop
- Jazz
- Metal
- Pop
- Reggae
- Rock

## 🎼 Genres Covered

Hip-Hop · Rock · Reggae · Jazz · Classical · Electronic · Pop · Metal · Blues · Country

## 📊 Parameters Used

| Parameter | Description |
|---|---|
| **Mel-Spectrogram** | Visual energy pattern across time and frequency |
| **MFCC** | Mel-Frequency Cepstral Coefficients — timbre fingerprint |
| **Spectral Centroid** | Brightness of sound (Hz) |
| **Dominant Frequency** | Core frequency range of the genre (Hz) |
| **Tempo / BPM** | Rhythmic speed range |
| **Chroma Features** | Key, harmony, and chord type |
| **Spectral Rolloff** | Frequency below which most energy is concentrated (Hz) |

## 📁 Sheets

- **Genre Classification** — Qualitative descriptions of all 7 parameters per genre
- **Numerical Ranges** — Exact min/max values; enter your song's Tempo & Spectral Centroid in the yellow cells to auto-match a genre
- **Feature Charts** — Bar charts comparing Tempo and Spectral Centroid ranges across all 10 genres

## ⚡ How to Use

1. Extract audio features from your song using a library like `librosa` (Python)
2. Open the **Numerical Ranges** sheet
3. Enter your song's **Tempo (BPM)** and **Spectral Centroid (Hz)** in the yellow input cells
4. The **AUTO GENRE MATCH** column will highlight the closest genre with ✅

## Performance
1.Training Accuracy
    99.22% accuracy
2.Testing Accuracy
    90.31% accuracy

## 📌 Example Ranges

| Genre | Tempo (BPM) | Spectral Centroid (Hz) | Dominant Freq (Hz) |
|---|---|---|---|
| Hip-Hop | 70 – 110 | 800 – 2,500 | 60 – 4,000 |
| Rock | 100 – 160 | 2,000 – 4,500 | 80 – 8,000 |
| Electronic | 120 – 160 | 1,500 – 6,000 | 30 – 18,000 |
| Metal | 120 – 280 | 3,000 – 7,000 | 60 – 16,000 |
| Classical | 40 – 180 | 1,000 – 5,000 | 40 – 16,000 |

## Technologies Used
- Python
- TensorFlow / Keras
- Librosa
- NumPy
- Pandas
- Matplotlib
- Streamlit

## Dataset Used
GTZAN Genre Classification Dataset

## Project Workflow
1. Upload audio file
2. Preprocess audio signal
3. Generate Mel Spectrogram
4. Extract audio features
5. Predict music genre using Deep Learning model
6. Display predicted genre

## Real World Applications

The concepts used in this Music Genre Classification project can be applied in many real-world domains where signal or wave pattern analysis is important.

- **Space Research:** Classifying celestial objects using cosmic and radio wave patterns.
- **Underwater Sonar Systems:** Detecting submarines or marine objects through sonar signals.
- **Healthcare:** 
  - **ECG** for heart activity analysis and disease detection.
  - **EEG** for brain signal analysis and neurological disorder detection.

This project demonstrates how deep learning can intelligently analyze waveform-based data across multiple industries.

## Folder Structure

music-genre-classification-ML_T3/
│
├── dataset/
├── models/
├── app/
├── static/
├── templates/
├── README.md
├── requirements.txt
└── app.py

## Team members 
1. Team lead - Sanjay 23BIT095
2. Data Engineer - Ram 23BIT080
3. ML Engineer - Santhoshkumar 23BIT096
4. Quality analyst - Rohith 23BIT086
5. Deployment Engineer - Mukesh 23BiT063
