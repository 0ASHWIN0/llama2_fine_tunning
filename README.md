# Ollama Fine Tuning

This project is a lightweight Python starter for experimenting with fine-tuning workflows around Ollama-style models.

## Project structure

- `main.py` – entry point for the application
- `fine_tunning_code.ipynb` – notebook with exploratory code
- `pyproject.toml` – Python dependencies and project metadata

## Requirements

- Python 3.11+
- pip or uv

## Local setup

1. Create and activate a virtual environment:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```
2. Install dependencies:
   ```bash
   pip install -U pip
   pip install .
   ```
3. Run the app:
   ```bash
   python main.py
   ```

## Docker setup

Build the image:

```bash
docker build -t ollama-fine-tunning:latest .
```

Run the container:

```bash
docker run --rm ollama-fine-tunning:latest
```

## Notes

The current implementation is a simple starter script. You can expand it by adding your fine-tuning pipeline, dataset loading, model training logic, and Ollama integration.
