# Week 7 – Generative AI Programming Practical

This program loads GPT-2 using Hugging Face Transformers, displays the top-5
next-token candidates and their probabilities for four prompts, and saves the
results to `week7_probability_results.csv`.

## Files
- `main.py` – Python program
- `requirements.txt` – required Python packages

## Run on Windows

Open a terminal in this folder and run:

```bash
python -m pip install -r requirements.txt
python main.py
```

The first run downloads the GPT-2 model from Hugging Face, so an internet
connection is required. The generated CSV file will be saved in this folder.

If PyTorch installation fails on your system, install the appropriate PyTorch
build from https://pytorch.org/get-started/locally/ and then run the requirements
installation again.
