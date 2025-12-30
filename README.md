# action-example

Minimal quicksort implementation with pytest coverage, wired to run in GitHub
Actions.

## Requirements

- Python 3.12+
- uv (or install dependencies another way)

## Setup

```bash
uv sync
```

## Run tests

```bash
uv run pytest tests/
```

## Usage

```python
from action_example import quick_sort

print(quick_sort([3, 1, 2]))
```
