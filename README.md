# crua_edu

## Install the requirements packages

environment: python 3.9

```
pip install -r requirements.txt
```

since using the SpaCy to preprocess the data for evaluation

You may need to type this in your terminal to install the English Model

```python -m spacy download en_core_web_sm```

There are mainly two files to run:"test.ipynb" and "evaluate.ipynb"

* "test.ipynb" indicate that all the process foe generating answers from LLM(gpt-4o-mini and Fine Tunned Model)
* "evaluate.ipynb" shows all process of estimate the performance of two models: Fine Tunned Model and base-line model(gpt-4o-mini)
