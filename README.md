# GDPR, Green Data, and EU AI Act Labs

Practice core compliance and sustainability concepts in three small Jupyter notebooks.

## Contents

- [`01_GDPR_Principles.ipynb`](01_GDPR_Principles.ipynb): actors, lawful bases, Article 5 principles, rights, plus code prompts for minimization, retention, and accountability.
- [`02_GreenData_Practices.ipynb`](02_GreenData_Practices.ipynb): rough carbon estimation, deduplication, lifecycle policy prompts, and efficiency heuristics.
- [`03_EU_AI_Act.ipynb`](03_EU_AI_Act.ipynb): risk ladder, high-risk checklist, scenario classification, and simple logging patterns for traceability.

## Setup (virtual environment)

The added [requirements file](requirements.txt) contains all libraries and dependencies we need to execute the hands-on ml notebooks.

*Note: If there are errors during environment setup, try removing the versions from the failing packages in the requirements file. M1/Apple Silicon issues.*

### **`macOS`** or `Linux` type the following commands : 

```bash
# optional if you use pyenv
pyenv local 3.11.3

python -m venv .venv
source .venv/bin/activate

python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```
### **`Windows`** type the following commands :

- Install the virtual environment and the required packages by following commands.

For `PowerShell` CLI :

```PowerShell
pyenv local 3.11.3
python -m venv .venv
.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
```

For `Git-bash` CLI :
  
```bash
pyenv local 3.11.3

python -m venv .venv
source .venv/Scripts/activate

python -m pip install --upgrade pip
pip install -r requirements.txt
```
