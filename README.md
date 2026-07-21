```bash
!python -m src.train \
    --root /content/sketchy/Sketchy \
    --dataset sketchy_1 \
    --epochs 5 \
    --workers 6
```

With the same `--seed`, `--workers 4`, `--workers 5`, and other worker counts
produce the same batch order, positive photos, and augmentations. The worker
count only affects data-loading throughput.
