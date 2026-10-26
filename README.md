# Flow Matching Tutorial 
---

## Prerequisites

Install `uv` if you don't have it:

```bash
pip3 install uv
```

## Set up

Clone the repo, then install dependencies:

```bash
uv sync
```

## Run

1. Open `tutorial.ipynb` in your Jupyter environment (VS Code, Jupyter Lab, ...).
2. Select the kernel:
   - **VS Code**: in "Select kernel" (top-right) pick the project's `.venv`. It's detected automatically.
   - **Jupyter Lab / Notebook**: register the kernel once, then pick `flow-matching-uv` from the list:

     ```bash
     uv run python -m ipykernel install --user --name flow-matching-uv
     ```
---

## Read through the notebook and run the cells one by one.