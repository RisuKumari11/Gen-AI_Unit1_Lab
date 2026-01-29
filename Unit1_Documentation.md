## Key Concepts Understood
- BERT and RoBERTa are encoder-only transformer models designed for language understanding.
- BART is an encoder–decoder model suitable for text generation tasks.
- Text generation requires autoregressive decoding, which encoder-only models lack.
- Masked Language Modeling (MLM) is the primary training objective of BERT and RoBERTa.
- Model performance depends on architectural suitability to the task, not just model size.

## Solution Implemented
- A Jupyter Notebook was created using the Hugging Face `transformers` library.
- Three tasks were evaluated: Text Generation, Fill-Mask, and Question Answering.
- All three models (BERT, RoBERTa, and BART) were tested using the `pipeline` API.
- BERT and RoBERTa failed at text generation but performed well in fill-mask tasks.
- BART generated coherent text but showed weak performance in extractive QA.
- Results were summarized in an observation table with architectural explanations.
