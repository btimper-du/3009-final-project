# 3009-final-project

This repository contains the code and notebooks for our COMP-3009 final project. Below are the minimal steps teammates should follow to run the project locally and open the main notebook, `stock_preds.ipynb`.

## Quick start (macOS / zsh)

Note: the commands below show the flow on my Mac (zsh). Creating and activating a virtual environment may differ on other operating systems or shells (for example, PowerShell or CMD on Windows). If you're not using macOS/zsh, follow the platform-appropriate virtual environment instructions.

1. Create and activate a virtual environment (recommended):

```bash
# create a venv named .venv using python3
python3 -m venv .venv
# activate the venv (zsh)
source .venv/bin/activate
```

2. Upgrade pip and install project requirements:

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

3. Start Jupyter Notebook and open the main notebook in your browser:

```bash
jupyter notebook
```

When the notebook UI opens in your browser, open `stock_preds.ipynb` from the file list.

4. When finished, deactivate the virtual environment:

```bash
deactivate
```

## Notes
- The steps above assume you have Python 3 installed and that `python3` points to the desired interpreter. We recommend Python 3.10+.
- If you prefer conda, you can create an environment with `conda create -n 3009 python=3.10` and then `conda activate 3009` before installing requirements.
- If `jupyter` is not present in `requirements.txt`, install it with `pip install jupyter`.

## Troubleshooting
- If activation fails, check the venv path: `.venv/bin/activate` should exist after creating the venv.
- If package installation fails, try creating a fresh venv or upgrading pip/setuptools/wheel.
- If the notebook doesn't open automatically, copy the URL printed in terminal (it contains a token) into your browser.

---
Last updated: 2025-11-04

