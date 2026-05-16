# Transformer From Scratch using PyTorch

Built a Transformer architecture completely from scratch using PyTorch.

---

## Features

- Multi-Head Self Attention
- Encoder-Decoder Architecture
- Positional Embeddings
- Masking
- Feed Forward Networks
- Sentence Example Inference

---

## Concepts Used

- Queries, Keys, Values
- Self Attention
- Multi Head Attention
- Layer Normalization
- Residual Connections
- Positional Encoding

---

## Example

Input Sentence:

```text
<SOS> i love transformers <EOS>
```

Target Sentence:

```text
<SOS> transformers are awesome <EOS>
```

Example Prediction (untrained model):

```text
learning are transformers awesome
```

---

## Tech Stack

- Python
- PyTorch
- Jupyter Notebook

---

## Run Locally

Install dependencies:

```bash
pip install torch
```

Run notebook:

```bash
jupyter notebook
```

---

## Project Structure

```text
Transformer-from-scratch/
│
├── Transformers.ipynb
├── README.md
└── requirements.txt
```

---

## Future Improvements

- Add training loop
- Train on real dataset
- Add tokenizer
- Add beam search decoding
- Add visualization for attention maps
