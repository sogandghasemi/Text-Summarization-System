#  Wikipedia Text Summarizer

## Introduction

This Python script uses the NLTK library to summarize content from Wikipedia or custom text files. It supports two summarization methods: a basic length-based approach and a cosine similarity-based method for more coherent results.

## Features

- Prompts user to enter two Wikipedia topics  
- Fetches articles and saves them as `input_text1.txt` and `input_text2.txt`  
- Summarizes using two methods:
  - **Basic Summarization** – Adds sentences until a target length is reached  
  - **Cosine Similarity Summarization** – Adds sentences based on similarity to the current summary  
- Saves summaries as:
  - `summarized_text1.txt`, `summarized_text2.txt` *(basic method)*  
  - `Second_summarized_text1.txt`, `Second_summarized_text2.txt` *(cosine similarity method)*  
- Generates a query based on the summaries  
- Allows use of custom `.txt` files instead of Wikipedia content  

## File Details

- `input_text1.txt`, `input_text2.txt`: Raw article text  
- `summarized_text1.txt`, `summarized_text2.txt`: Basic summarization output  
- `Second_summarized_text1.txt`, `Second_summarized_text2.txt`: Cosine similarity output  

## Requirements

- Python 3.x  
- `nltk`  
- `numpy`  
- `scikit-learn`  

Install dependencies with:

```bash
pip install nltk numpy scikit-learn
```

## Usage

1. Run the script:
   ```bash
   python script_name.py
   ```
2. Enter two Wikipedia topic names or use custom input files  
3. Find outputs in the generated `.txt` files  

## Conclusion

This tool is ideal for exploring and comparing text summarization techniques using Python and NLTK. Whether using Wikipedia or your own documents, it provides easy-to-read summaries through two different approaches.
