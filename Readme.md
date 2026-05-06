# Antares Management Services

Welcome to the **Antares Management Services** repository! This project is a collaborative workspace for us to build tools for processing heavy data loads efficiently.

## 🚀 Project Goal
This repository is dedicated to handling large-scale data processing. Our focus is on:
*   **Efficiency:** Using Python to handle massive datasets without crashing.
*   **Automation:** Building scripts to clean, transform, and analyze data at scale.
*   **Collaboration:** A shared space for us to track code changes and version control.

---

## 🛠 Michelle’s Setup Guide
Since you already have Git installed, follow these steps to get your environment ready in **Visual Studio Code (VS Code)**.

### 1. Clone the Project
Open your terminal and run:
```bash
git clone https://github.com
cd AntaresManagementServices
```

### 2. VS Code Recommended Extensions
To make things run smoothly, install these from the VS Code Extensions Marketplace:
*   **Python** (by Microsoft)
*   **Jupyter** (to run `.ipynb` notebook files)

### 3. Setup Virtual Environment
Run these commands in the VS Code terminal to keep your libraries organized:
```bash
# Create the environment
python -m venv venv

# Activate it (Windows)
.\venv\Scripts\activate

# Activate it (Mac/Linux)
source venv/bin/activate
```

### 4. Install Core Tools
Once activated, install the main data processing libraries:
```bash
pip install pandas numpy notebook
```

---

## 📂 Project Structure
*   `notebooks/`: Use this for messy testing and data exploration (`.ipynb` files).
*   `scripts/`: This is for our final, polished Python scripts.
*   `data/`: Where we store the datasets (Note: avoid uploading very large files to GitHub).
