## Installation Requirements

**Environment**: Python 3.9

To install the required packages, run:

```
pip install -r requirements.txt
```

Since the project uses SpaCy for data preprocessing, you'll need to install the English model as well. Run this command in your terminal:

```
python -m spacy download en_core_web_sm
```

## Main Files

There are two primary Jupyter notebooks to run:

1. `test.ipynb`: This notebook demonstrates the entire process of generating answers using the LLM (gpt-4o-mini and the fine-tuned model).
2. `evaluate.ipynb`: This notebook details the evaluation process, comparing the performance of the fine-tuned model with the baseline model (gpt-4o-mini).
