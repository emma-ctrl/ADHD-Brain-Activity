# ADHD-Brain-Activity
Prediction of sex and ADHD diagnosis using functional brain imaging data of children, their socio-demographics, emotional and parenting information 

## Setting up

Create conda environment:
```bash
conda create -n adhd-brain python=3.9
conda activate adhd-brain
```

Clone repo:
```bash
git clone git@github.com:emma-ctrl/ADHD-Brain-Activity-Patterns.git
cd ADHD-Brain-Activity-Patterns
```

## Repo structure

```
.
├── data                    # Raw and preprocessed datasets
│   ├── APQ                # APQ questionnaire data (43 rows, 2 columns)
│   ├── Dictionary         # Data dictionary (37 rows, 6 columns)
│   ├── EHQ               # EHQ assessment data (16 rows, 2 columns)
│   ├── Instrument_Description  # Measurement descriptions (8 rows, 2 columns)
│   └── SDQ               # SDQ questionnaire data (34 rows, 2 columns)
├── notebooks              # Jupyter notebooks for EDA and modeling
├── src                    # Scripts and source files
├── test                   # Automated tests
└── README.md             # Project documentation
```

## Data Dictionary

The project includes multiple data files:
- APQ (Attention Pattern Questionnaire): Contains participant responses to attention-related questions
- EHQ (Environmental History Questionnaire): Records environmental factors
- SDQ (Symptom Description Questionnaire): Documents ADHD symptom manifestations
- Instrument_Description: Provides details about measurement tools and methods used

## Getting Started

1. Set up the conda environment using the commands above
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Navigate to the notebooks directory to explore the data analysis

## Project Overview

This project analyzes brain activity patterns in individuals with ADHD, incorporating multiple assessment tools and questionnaires to provide a comprehensive understanding of attention patterns and environmental factors affecting ADHD manifestation.
