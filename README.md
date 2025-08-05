
# Jupyter Notebook Installation Guide (Windows)

This guide provides step-by-step instructions to install **Jupyter Notebook** on your local Windows system.

---

## Method 1: Install Jupyter Notebook using pip (Python Package Manager)

### Prerequisites:
- Python 3.x must be installed.
- Ensure **Python is added to PATH** during installation.

### Steps:
1. **Download and Install Python**  
   - Visit: https://www.python.org/downloads/  
   - Download the latest Python version and install it.
   - During installation, make sure to **check "Add Python to PATH"**.

2. **Open Command Prompt (CMD)**
   - Press **Win + R**, type `cmd`, and hit Enter.

3. **Upgrade pip (Optional)**
   ```bash
   python -m pip install --upgrade pip
   ```

4. **Install Jupyter Notebook**
   ```bash
   pip install notebook
   ```

5. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
   - This will open Jupyter Notebook in your default browser at: http://localhost:8888/tree

5. **If its showing error while Launch Jupyter Notebook **
   -Try running Jupyter directly using Python:
   ```bash
   python -m notebook
   ```
   - This should open Jupyter Notebook in your browser, bypassing the PATH problem.: 

---

## Method 2: Install Jupyter Notebook using Anaconda (Beginner Friendly)

### Prerequisites:
- No need to install Python separately. Anaconda comes with Python, Jupyter, and other data science libraries pre-installed.

### Steps:
1. **Download Anaconda**
   - Visit: https://www.anaconda.com/products/distribution
   - Download the **Anaconda Individual Edition** for Windows.

2. **Install Anaconda**
   - Run the downloaded installer.
   - Proceed with default options (No need to manually add to PATH).

3. **Launch Jupyter Notebook via Anaconda Navigator**
   - Open **Anaconda Navigator** from Start Menu.
   - Click on **Launch** under **Jupyter Notebook** section.
   - This will open Jupyter Notebook in your default browser.

---

## Verify Installation
After installation, you can verify Jupyter version by running:
```bash
jupyter --version
```

---

## Optional:
- To install **JupyterLab (Modern UI of Jupyter)**:
   ```bash
   pip install jupyterlab
   ```

---

## Useful Commands Summary
| Command | Description |
|---------|-------------|
| `jupyter notebook` | Start Jupyter Notebook |
| `Ctrl + C` in CMD | Stop Jupyter Server |
| `pip install jupyterlab` | Install JupyterLab |

---

## Recommendation:
- For **Beginners & Data Science learners**: Use **Anaconda**.
- For **Lightweight setup (only Jupyter & Python)**: Use **pip method**.

---
