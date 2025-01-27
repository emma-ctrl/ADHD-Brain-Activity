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

Download Dataset
https://www.kaggle.com/competitions/widsdatathon2025/data

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
