## Як відкрити в Positron

1. Відкрити папку `lab$` у Positron.
2. У ноутбуці обрати kernel `Python (lab$)`.
3. Перевірити інтерпретатор:

```python
import sys
sys.executable
```

Очікувано: шлях до `.../miniconda3/envs/lab1/...`.

## Корисні команди

```bash
conda activate lab1
conda env export -n lab1 --from-history > environment.yml
conda env create -f environment.yml
```
