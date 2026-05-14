# X-Culture Analysis

Python Scripts for Mixed-Methods Analysis of X-Culture Data
A comprehensive Python toolkit for qualitative data analysis using VADER, NLTK, LSM, and custom lexicon-based approaches. Designed for seamless execution in Google Colab and local macOS environments.

## Overview

This project provides:
- **Sentiment Analysis**: VADER and NLTK-based text analysis
- **Lexicon-based Analysis**: LIWC, LSM, and custom dictionaries
- **Data Processing**: Google Drive integration for data management
- **Multi-environment Support**: Works identically in Colab and local Python

## Quick Start

### Google Colab
```python
!git clone https://github.com/jamiebridel/x-culture-analysis.git
%cd x-culture-analysis
!pip install -r requirements.txt

from google.colab import drive
drive.mount('/content/drive')

from src.preprocessing import data_loader
from src.analysis import vader_analysis
