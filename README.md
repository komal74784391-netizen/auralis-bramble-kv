# Bramble

Official implementation of **Bramble: KV-Cache Compression via Low-Rank Sketches**.

## Installation

```bash
pip install -r requirements.txt
```

## Repository structure

```
src/compress.py
src/cache.py
train.py
eval.py
requirements.txt
```

## Training

Run `python train.py --config configs/default.yaml` to reproduce the main results.
Checkpoints and logs are written to `runs/`.

## Evaluation

Run `python eval.py --checkpoint runs/latest` to reproduce the benchmark tables.

## Citation

```bibtex
@inproceedings{misc,
  title = {Bramble: KV-Cache Compression via Low-Rank Sketches},
  booktitle = {Proceedings of the corresponding venue},
  year = {2025}
}
```
