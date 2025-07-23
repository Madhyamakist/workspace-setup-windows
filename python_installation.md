# Windows Python Setup 

## Purpose
- Installing the latest stable Python version on Windows
- Creating a virtual environment

---

## Requirements
- Windows 8 or 10 or 11
- Internet connection
- Visual Studio Code (recommended)

---

## Setup Steps

### 1. Install Python

- Go to [Python Downloads](https://www.python.org/downloads/)
- Download recent stable version of Python file and click to install it
- On the first install screen, check the box that says "Add Python to PATH". This automatically adds Python and its Scripts folder to your PATH variable.
- GO to Windows PowerShell, and enter `python --version` and `pip --version` to check the installation.


### 1. Creating virtual environment

- To create a virtual environment named "test", go to Windows PowerShell and enter

```bash
python -m venv test
```
-  To activate the environment
```bash
test\Scripts\activate
```
