# Multi-resolution-Attention
Dynamic merging of embeddings to robustly capture long-term and short-term dependencies in tranformers.

## Data
To prepare shakespear char (very small), run
`python data/shakespeare_char/prepare.py`.

To download openwebtext (13GB), run
`python nanogpt/data/openwebtext/prepare.py`.
This requires `pip install datasets==3.6.0` (see https://github.com/huggingface/datasets/issues/7693#issuecomment-3103380232)
