# About

This repo stores code used to teach the usage of the spaCy package by the [Advanced NLP with spaCy](https://course.spacy.io/en/) course.

The notebooks for each chapter can be found in the `src/notebooks/` folder.

# Installing on local machine using conda with CUDA support

To install spaCy see https://spacy.io/usage

The instructions below install spaCy with GPU support and trained pipe lines for English, German and Spanish

```
conda install -c conda-forge spacy
conda install -c conda-forge cupy
python -m spacy download en_core_web_sm
python -m spacy download de_core_news_sm
python -m spacy download es_core_news_sm
```

To use similarity functionality on `Doc`, `Token` and `Span` objects. Install `en_core_web_md` and `en_core_web_lg`
as they include word vectors.
```
python -m spacy download de_core_news_md
python -m spacy download de_core_news_lg
```

