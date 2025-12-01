# GDPR, Green Data, and EU AI Act Labs

Practice core compliance and sustainability concepts in three small Jupyter notebooks.

## Contents
- `01_GDPR_Principles.ipynb` : actors, lawful bases, Article 5 principles, rights, and code prompts for minimization, retention, and accountability.
- `02_GreenData_Practices.ipynb` : carbon estimation, deduplication, lifecycle policy prompts, and efficiency heuristics.
- `03_EU_AI_Act.ipynb` : risk ladder, high-risk checklist, scenario classification, and logging patterns for traceability.

## Set up your Environment

Please make sure you have forked the repo and set up a new virtual environment. For this purpose you can use the following commands:

The added [requirements file](requirements.txt) contains all libraries and dependencies we need to execute the hands-on ml notebooks.

*Note: If there are errors during environment setup, try removing the versions from the failing packages in the requirements file. M1/Apple Silicon issues.*

### **`macOS`** or `Linux` type the following commands : 

- Install the virtual environment and the required packages by following commands:

```BASH
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
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
  
```BASH
pyenv local 3.11.3
python -m venv .venv
source .venv/Scripts/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```
**`Note:`**
If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:

```Bash
python.exe -m pip install --upgrade pip
```
