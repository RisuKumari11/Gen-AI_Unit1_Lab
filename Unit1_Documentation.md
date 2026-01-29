Key Concepts Understood

BERT and RoBERTa are encoder-only transformer models designed for language understanding tasks.

BART is an encoder–decoder model suited for text generation.

Text generation requires autoregressive decoding, which encoder-only models lack.

Masked Language Modeling (MLM) is the core training objective of BERT and RoBERTa.

Model performance depends strongly on architectural compatibility with the task.

Solution Implemented

A Jupyter Notebook was created using the Hugging Face transformers library.

Three tasks were tested: Text Generation, Fill-Mask, and Question Answering.

All three models (BERT, RoBERTa, BART) were evaluated using the pipeline API.

BERT and RoBERTa failed at text generation but succeeded in fill-mask tasks.

BART generated fluent text but performed poorly in extractive QA.

Results were documented in an observation table highlighting architectural reasons.
