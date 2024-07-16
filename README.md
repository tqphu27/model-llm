---
license: apache-2.0
---

This is a tiny random Llama model derived from ["meta-llama/Llama-2-7b-hf"](https://huggingface.co/meta-llama/Llama-2-7b-hf).

See [make_tiny_model.py](./make_tiny_model.py) for how this was done.

This is useful for functional testing (not quality generation, since its weights are random and the tokenizer has been shrunk to 3k items)
