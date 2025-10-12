# Movie-Recommender

A Python-based movie recommendation system utilizing content-based filtering to suggest movies similar to a given title.

## Table of Contents
- [Features](#features)
- [System Architecture / Workflow](#system-architecture--workflow)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- 
## Features
- Content-based movie recommendations using cosine similarity
- Built with Python and Jupyter Notebook
- Utilizes the TMDB 5000 Movie Dataset
- Simple and easy-to-use interface

## System Architecture / Workflow
1. **Data Loading** — Load the TMDB 5000 Movie Dataset.
2. **Data Preprocessing** — Clean and prepare the data for analysis.
3. **Feature Extraction** — Extract relevant features such as genres, keywords, and descriptions.
4. **Similarity Calculation** — Compute cosine similarity between movies based on extracted features.
5. **Recommendation Generation** — Provide a list of recommended movies based on a given input movie.

## Prerequisites
- Python 3.6+
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Other dependencies listed in `requirements.txt`

## Installation
```bash
# 1. Clone the repository
git clone https://github.com/amnaarriyas/Movie-Recommender.git
cd Movie-Recommender

# 2. (Optional) Create a virtual environment
python3 -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate      # Windows

# 3. Install dependencies
pip install -r requirements.txt
