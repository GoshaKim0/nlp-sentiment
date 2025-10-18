# NLP Sentiment Analysis

Binary sentiment classification of IMDB movie reviews using TF-IDF and Logistic Regression.

## Setup
python -m venv .venv  
.\.venv\Scripts\activate  
pip install -r requirements.txt

## Download Data
python scripts/download_imdb.py

## Train Models
python src/train.py

## Run Inference
python src/infer.py --text "I loved this movie!" --text "This was boring."

## Files
- src/ — training and inference scripts  
- scripts/ — dataset downloader  
- results/ — metrics, confusion matrices, and saved model
