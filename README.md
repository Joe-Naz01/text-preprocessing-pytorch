# Text Preprocessing with PyTorch & TorchText

**Problem.** Raw text must be cleaned and transformed before deep learning models can use it. This project demonstrates preprocessing steps using PyTorch and TorchText.

**Data.** Example passages of text (custom samples embedded in the notebook).

**Approach.**
- Tokenization with `torchtext`'s `get_tokenizer`.
- Stopword removal and stemming (NLTK).
- Vocabulary building and bag-of-words representation.
- Created a text preprocessing pipeline as a foundation for downstream NLP models.

**Results.**
- Generated cleaned tokens and vocabulary frequency distributions.
- Produced bag-of-words vectors for sample texts.
- Established a reusable preprocessing workflow for future deep learning tasks.

**What I Learned.**
- How to combine PyTorch, TorchText, and NLTK for NLP preprocessing.
- Importance of tokenization, stopword removal, and stemming.
- Bag-of-words limitations and why pipelines matter for scaling.

## Quick Start
```bash
git clone https://github.com/Joe-Naz01/text-preprocessing-pytorch.git
cd text-preprocessing-pytorch
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
