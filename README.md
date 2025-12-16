# Open-Science-Quest-Introduction

A short, hands-on walkthrough of synthetic regression, open-science concepts, and Jupyter notebooks. Use the instructions below to create an isolated Python environment in VS Code or PyCharm, install dependencies, and run the tutorial notebook.

## Contents
- `open_science_synthetic_regression_tutorial_v2.ipynb`: the guided notebook with code and concept exercises.
- `requirements.txt`: pinned dependencies for the tutorial.

## Prerequisites
- Python 3.10+ installed locally.
- VS Code (with the Python and Jupyter extensions) **or** PyCharm Community/Professional.

## Create a virtual environment

### Option A: VS Code
1. Open this folder in VS Code.
2. Open the built-in terminal (`Ctrl+\`` or `Cmd+\`` on macOS).
3. Create a virtual environment:
   ```bash
   python -m venv .venv
   ```
4. Activate it:
   - **Windows (PowerShell):** `./.venv/Scripts/Activate.ps1`
   - **macOS/Linux (bash/zsh):** `source .venv/bin/activate`
5. In VS Code, select the interpreter: press `Ctrl+Shift+P` → "Python: Select Interpreter" → choose `.venv`.

### Option B: PyCharm
1. Open the project folder in PyCharm.
2. Go to `File` → `Settings` (`PyCharm` → `Preferences` on macOS) → `Project` → `Python Interpreter`.
3. Click the gear icon → `Add...` → `Existing environment`.
4. Browse to the `.venv` created with `python -m venv .venv` (or click `New environment` to create it) and select the Python executable inside `.venv`.
5. Apply the changes so PyCharm uses the project environment.

## Install dependencies
With the virtual environment activated (in the VS Code terminal or PyCharm's built-in terminal), run:
```bash
pip install -r requirements.txt
```

## Open and run the notebook
1. Start Jupyter from the terminal in the project folder:
   ```bash
   jupyter notebook
   ```
2. In the browser tab that opens, click `open_science_synthetic_regression_tutorial_v2.ipynb`.
3. Run cells sequentially with **Shift+Enter**. The VS Code Notebook UI or the Jupyter web UI both support this shortcut.
4. Work through the exercises at the end—each one is scoped to reproducibility, reproduction, robustness, or generalization.

## Tips
- If a kernel prompt asks which interpreter to use, select the `.venv` environment you created.
- Restart the kernel (Jupyter: `Kernel` → `Restart & Run All`) if imports or variables get out of sync.
