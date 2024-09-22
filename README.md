# 706_DE_Individual_Project
This is a project scaffold for Python
- requirements.txt
- MAKEFILE
- github actions
- devcontainer

# Assignment Requirements
*  Jupyter Notebook with:
** Cells that perform descriptive statistics using Polars or Panda
** Tested by using nbval plugin for pytest
* Makefile with the following:
** Run all tests (must test notebook and script and lib)
** Formats code with Python Black
** Lints code with Ruff
** Installs code via: pip install -r requirements.txt
* test_script.py to test script
* test_lib.py to test library
* Pinned requirements.txt
* GitHub Actions performs all four Makefile commands with badges for each one in the README.md