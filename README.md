# voice-cognitive-decline
  This project focuses on building a proof-of-concept pipeline to detect early indicators of cognitive decline using raw voice data samples.The goal is to analyze speech    
  patterns and extract features that may signal cognitive stress or impairment, employing NLP and audio feature extraction techniques.

Key Features to Extract :-
- Pauses per sentence
- Hesitation markers (e.g., "uh," "um")
- Word recall issues (e.g., substitutions, lost words)
- Speech rate and pitch variability
- Naming & Word-Association Tasks
- Sentence Completion

Methodology :-
- Preprocessing: Clean and normalize audio data, convert speech to text (if needed).
- Feature Extraction: Derive linguistic and acoustic features from the audio.
- Modeling: Apply unsupervised techniques such as clustering, similarity scoring, or anomaly detection.
- Evaluation: Analyze feature trends and identify outliers or risk indicators.

## Installation

1. Clone this repository or upload the files to Google Colab
2. Install required packages:
   
        pip install librosa numpy pandas matplotlib whisper scikit-learn

