# Emotion Recognition from Physiological Signals (GameEMO Dataset)

This project aims to explore and build models for emotion recognition using physiological signals (ECG, EDA, EMG) from the [GameEMO dataset](https://www.kaggle.com/datasets/sigfest/database-for-emotion-recognition-system-gameemo).

## Project Structure

```
├── data/                 # Raw and processed data (Not tracked by Git)
│   └── GAMEEMO/          # Extracted dataset files
├── notebooks/            # Jupyter notebooks for exploration, analysis, and modeling
│   └── 01_eda.ipynb      # Exploratory Data Analysis
├── src/                  # Source code for data processing, feature extraction, models etc.
│   └── __init__.py
├── .gitignore            # Specifies intentionally untracked files that Git should ignore
├── LICENSE               # Project license information
├── README.md             # This file
└── requirements.txt      # Python package dependencies
```

## Setup

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
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

4.  **Download the Dataset:**
    *   Download the GameEMO dataset from [Kaggle](https://www.kaggle.com/datasets/sigfest/database-for-emotion-recognition-system-gameemo).
    *   Extract the contents into the `data/GAMEEMO/` directory within the project root. The structure should look like `data/GAMEEMO/S01/`, `data/GAMEEMO/S02/`, etc.

## Usage

*   Navigate to the `notebooks/` directory.
*   Run Jupyter Lab:
    ```bash
    jupyter lab
    ```
*   Open and run the notebooks (e.g., `01_eda.ipynb`) to explore the data and model development process.

## Contributing

[Optional: Add guidelines for contributing if applicable]

## License

[Specify License, e.g., This project is licensed under the MIT License - see the LICENSE file for details.]
