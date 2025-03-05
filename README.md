# OPUS Corpora for Multilingual Chatbot

This repository contains links to the OPUS corpora used for training a multilingual chatbot.

## 📂 Dataset Links

| Dataset | Description | Download Link |
|---------|------------|---------------|
| OPUS OpenSubtitles | Arabic to English Subtitle translations | [Download ZIP](https://object.pouta.csc.fi/OPUS-OpenSubtitles/v2018/moses/ar-en.txt.zip) |
| OPUS OpenSubtitles | English to Arabic Subtitle translations | [Download ZIP](https://object.pouta.csc.fi/OPUS-OpenSubtitles/v2018/moses/ar-en.txt.zip) |
| OPUS OpenSubtitles | Spanish to English Subtitle translations | [Download ZIP](https://object.pouta.csc.fi/OPUS-OpenSubtitles/v2018/moses/en-es.txt.zip) |
| OPUS OpenSubtitles | English to Spanish Subtitle translations | [Download ZIP](https://object.pouta.csc.fi/OPUS-OpenSubtitles/v2018/moses/en-es.txt.zip) |
| OPUS OpenSubtitles | French to English Subtitle translations | [Download ZIP](https://object.pouta.csc.fi/OPUS-OpenSubtitles/v2018/moses/en-fr.txt.zip) |
| OPUS OpenSubtitles | English to French Subtitle translations | [Download ZIP](https://object.pouta.csc.fi/OPUS-OpenSubtitles/v2018/moses/en-fr.txt.zip) |
| OPUS OpenSubtitles | Japanese to English Subtitle translations | [Download ZIP](https://object.pouta.csc.fi/OPUS-OpenSubtitles/v2018/moses/en-ja.txt.zip) |
| OPUS OpenSubtitles | English to Japanese Subtitle translations | [Download ZIP](https://object.pouta.csc.fi/OPUS-OpenSubtitles/v2018/moses/en-ja.txt.zip) |


## 📜 How to Use
1. Clone this repo:
   ```bash
   git clone https://github.com/malorieiovino/subtitles.git

## 📥 Download & Extract Data in Jupyter
To programmatically download a dataset in Python:
```python
import urllib.request
import zipfile

url = "https://your-download-link-here"
output_file = "dataset.zip"

# Download the file
urllib.request.urlretrieve(url, output_file)

# Extract
with zipfile.ZipFile(output_file, "r") as zip_ref:
    zip_ref.extractall("data/")
