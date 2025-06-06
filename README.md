# Emotion Recognition from Physiological Signals (GameEMO Dataset)

This project aims to explore and build models for emotion recognition using physiological signals (ECG, EDA, EMG) from the [GameEMO dataset](https://www.kaggle.com/datasets/sigfest/database-for-emotion-recognition-system-gameemo).

## Project Structure

```
├── data/                 # Raw and processed data (Not tracked by Git)
│   └── GAMEEMO/          # Extracted dataset files
├── eeg_emotion_classifier.ipynb            # Jupyter notebook for exploration, analysis, and modeling
├── .gitignore            # Specifies intentionally untracked files that Git should ignore
├── LICENSE               # Project license information
├── README.md             # This file
└── requirements.txt      # Python package dependencies
```

## Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/dromaniv/emotion-recognition.git
    cd emotion-recognition
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

*   Run Jupyter Lab:
    ```bash
    jupyter lab
    ```
*   Open and run the notebooks (e.g., `eeg_emotion_classifier.ipynb`) to explore the data and model development process.