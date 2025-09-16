
# datafun-04-eda

A small exploratory data analysis (EDA) project scaffold for the Datafun series. This repository contains notebooks, helper scripts and documentation to explore, clean, visualize, and summarise datasets used throughout the course or personal data analysis exercises.

**Goals**
- Provide a reproducible environment for EDA experiments.
- Include examples of common data cleaning and visualization workflows.
- Offer a lightweight starting point for assignment or self-study in data analysis.

**Contents**
- `requirements.txt` — packages and setup instructions for a virtual environment.
- `README.md` — this file with project overview and usage instructions.

Getting started
---------------

1. Create and activate a Python virtual environment in the project root:

	 - Windows PowerShell:

		 ```powershell
		 py -m venv .venv
		 .\.venv\Scripts\Activate
		 ```

	 - macOS / Linux:

		 ```bash
		 python3 -m venv .venv
		 source .venv/bin/activate
		 ```

2. Upgrade packaging tools and install dependencies:

	 - Windows PowerShell:

		 ```powershell
		 py -m pip install --upgrade pip setuptools wheel
		 py -m pip install --upgrade -r requirements.txt --timeout 100
		 ```

	 - macOS / Linux:

		 ```bash
		 python3 -m pip install --upgrade pip setuptools wheel
		 python3 -m pip install --upgrade -r requirements.txt --timeout 100
		 ```

Usage
-----

- Open any Jupyter notebooks in this repository using VS Code or JupyterLab. Make sure to select the `.venv` interpreter/kernel.
- Use the included scripts and notebooks as templates for your own datasets: load, clean, visualise, and report findings.

Dependencies
------------
The project includes a comprehensive `requirements.txt` with common EDA packages such as `jupyter`, `ipykernel`, `matplotlib`, and `seaborn`. Review the file and uncomment or add packages you need.

Contributing
------------

- Add notebooks and small utilities that illustrate EDA techniques.
- Keep the `requirements.txt` up-to-date with any new packages you add.
- Open an issue or submit a pull request with improvements or fixes.


