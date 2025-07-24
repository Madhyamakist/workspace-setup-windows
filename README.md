# Windows Dev Environment Setup for Node.js

<details>

## Purpose
Set up your Node.js development environment on a new Windows machine using `nvm-windows`

---

## Requirements
- Windows 10 or 11
- Internet connection
- [nvm-windows](https://github.com/coreybutler/nvm-windows/releases)
- Visual Studio Code (recommended)

---
- Run `python --version` to check active python version
## Setup Steps

### 1. Install nvm-windows
- Download the latest `nvm-setup.exe` from the [releases page](https://github.com/coreybutler/nvm-windows/releases)
- Run the installer
- After installation, open Command Prompt or PowerShell and verify:

```bash
nvm version
```
- Once nvm is installed, you can install any Node.js version using:
```bash
nvm install X.Y.Z
```
Replace X.Y.Z with your required version.

- After installation, verify Node.js installation:

```bash
node -v
```
</details>

---


# Windows Dev Environment Setup for Python using pyenv-win
<details>

## Purpose
- Installing the latest stable Python version on Windows using pyenv-win for better version control
- Creating a virtual environment
---

## Requirements
- Windows 8 or 10 or 11
- Internet connection
- Visual Studio Code (recommended)

---

## Setup Steps

### 1. Install [pyenv-win](https://github.com/pyenv-win/pyenv-win)

- Install pyenv-win in PowerShell
```bash
Invoke-WebRequest -UseBasicParsing -Uri "https://raw.githubusercontent.com/pyenv-win/pyenv-win/master/pyenv-win/install-pyenv-win.ps1" -OutFile "./install-pyenv-win.ps1"; &"./install-pyenv-win.ps1"
```
- After installing, reopen PowerShell and run `pyenv --version` to check if installation was successful.
- Run `pyenv install -l` to check a list of Python versions supported by pyenv-win
- Run `pyenv install <version>` to install the required version as example: `pyenv install 3.12.10`
- Run `pyenv global <version>` to set a Python version as the global version
- Run `python --version` to check active python version
- Run `pyenv local <version>` to set a Python version inside your project folder.
- Run `python --version` to check active python version in project folder



### 1. Creating virtual environment

- To create a virtual environment named "test", go to Windows PowerShell and enter

```bash
python -m venv test
```
-  To activate the environment
```bash
test\Scripts\activate
```


</details>
