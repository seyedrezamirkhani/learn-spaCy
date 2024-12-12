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
