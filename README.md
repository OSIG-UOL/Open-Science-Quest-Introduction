# Open-Science-Quest-Introduction

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OSIG-UOL/Open-Science-Quest-Introduction/main)

A short, hands-on walkthrough of **synthetic regression**, **open-science concepts**, and **Jupyter notebooks**.

---

## 🚀 Quick start (recommended): Run via Binder

The easiest way to use this repository is through **Binder**:

1. Click the **Binder badge** at the top of this page.
2. Wait ~1–2 minutes for the environment to start (first launch may take a little longer).
3. Open `open_science_synthetic_regression_tutorial_v2.ipynb`
4. Run cells with **Shift + Enter** and work through the tutorial.

---

## 📦 Contents
- `open_science_synthetic_regression_tutorial_v2.ipynb`  
  The guided notebook with code and concept exercises
- `requirements.txt`  
  Pinned dependencies used by Binder and local setups

---

## 💻 Local installation (advanced / offline use)

If you want to run the tutorial locally (e.g. offline or for development), follow the steps below.

### Prerequisites
- Python **3.10+**
- VS Code (with Python & Jupyter extensions) **or** PyCharm

### Create a virtual environment

#### Option A: VS Code
1. Open this folder in VS Code.
2. Open the built-in terminal (`Ctrl+\`` or `Cmd+\`` on macOS).
3. Create a virtual environment:
   ```bash
   python -m venv .venv
4. Activate it:

   * **Windows (PowerShell):** `./.venv/Scripts/Activate.ps1`
   * **macOS/Linux:** `source .venv/bin/activate`
5. Select the interpreter:
   `Ctrl+Shift+P` → *Python: Select Interpreter* → `.venv`


#### Option B: PyCharm

1. Open the project folder.
2. Go to `File` → `Settings` → `Project` → `Python Interpreter`.
3. Click the gear icon → `Add...`
4. Choose:

   * **Existing environment** → select `.venv`, or
   * **New environment** to create one
5. Apply changes.


### Install dependencies

With the virtual environment activated:

```bash
pip install -r requirements.txt
```

### Open and run the notebook

1. Start Jupyter:

   ```bash
   jupyter notebook
   ```
2. Open `open_science_synthetic_regression_tutorial_v2.ipynb`
3. Run cells sequentially with **Shift + Enter**
4. Complete the exercises on:

   * reproducibility
   * reproduction
   * robustness
   * generalization

### Tips

* If asked for a kernel, select the `.venv` environment
* Restart the kernel if imports or variables get out of sync
