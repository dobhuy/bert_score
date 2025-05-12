# BERTScore - Finetune for Vietnamse BERT models (e.g PhoBERT, viT5, BARTPho)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-red.svg)](#python)
[![PyPI version bert-score](https://badge.fury.io/py/bert-score.svg)](https://pypi.python.org/pypi/bert-score/) [![Downloads](https://pepy.tech/badge/bert-score)](https://pepy.tech/project/bert-score) [![Downloads](https://pepy.tech/badge/bert-score/month)](https://pepy.tech/project/bert-score) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black) 


Automatic Evaluation Metric described in the paper [BERTScore: Evaluating Text Generation with BERT](https://arxiv.org/abs/1904.09675) (ICLR 2020). We now support about 130 models (see this [spreadsheet](https://docs.google.com/spreadsheets/d/1RKOVpselB98Nnh_EOC4A2BYn8_201tmPODpNWu4w7xI/edit?usp=sharing) for their correlations with human evaluation). Currently, the best model is `microsoft/deberta-xlarge-mnli`, please consider using it instead of the default `roberta-large` in order to have the best correlation with human evaluation.

#### News:
<!-- - Features to appear in the next version (currently in the master branch): -->
- Finetune BERT_score to use Vietnamese LM model 
  - Vietnamese models include: PhoBERT, viT5, BARTPho, ViSoBERT, ...
