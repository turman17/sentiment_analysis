# Sentiment Analysis Project

This project demonstrates sentiment analysis on text data using Python, combining traditional and transformer-based techniques in a Jupyter Notebook.

## Features

- Data Processing
    - Text preprocessing with [pandas](https://pandas.pydata.org/)
    - Progress tracking with `tqdm`

- Analysis Tools
    - [NLTK](https://www.nltk.org/) for tokenization and VADER sentiment analysis
    - Hugging Face transformers for sequence classification
    
- Visualization
    - [matplotlib](https://matplotlib.org/) for plotting
    - [seaborn](https://seaborn.pydata.org/) for statistical visualization

## Prerequisites

- Python 3.8+
- Virtual environment (recommended)
- [Amazon Fine Food Reviews Dataset](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)

## Setup

1. Clone the repository:
```bash
git clone https://github.com/your_username/sentiment_analysis.git
cd sentiment_analysis
```

2. Create virtual environment:
```bash
python3 -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Download NLTK data:
```python
import nltk
nltk.download(['punkt', 'vader_lexicon', 'averaged_perceptron_tagger', 'words'])
```

5. Download the [Amazon Fine Food Reviews Dataset](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews) and place it in the `data` directory.

## Usage

Start Jupyter:
```bash
jupyter notebook
```