# DiffTaiChi Installation & Setup

[GitHub](https://github.com/taichi-dev/difftaichi)
[Docs](https://docs.taichi-lang.org/docs/hello_world) (TaiChi Language)

## Ubuntu

1. Install python3 
`sudo apt-get install python3`

2. Create a virtual environment 
`python3 -m venv .difftaichivenv`

3. Activate virtual enviornment 
`source .difftaichivenv/bin/activate`

4. Clone example repo 
`git clone https://github.com/taichi-dev/difftaichi.git`

5. Enter directory 
`cd difftaichi`

6. Install requirements 
`pip3 install -r requirements.txt`

7. Run soft robot example 
`python3 examples/diffmpm.py`

## Windows

1. [Install VSCode](https://code.visualstudio.com/) (Allows for easy management of python virtual environments)

2. [Install GitHub Desktop](https://desktop.github.com/download/) (Allows for easy cloning of repositories)

3. [Install Python 3.10](https://www.python.org/downloads/release/python-31010/)

4. [Install Git](https://git-scm.com/downloads/win)

### Run Example

1. Open GitHub Desktop

2. Click on "File > Clone repository"

3. Clone by URL: "https://github.com/taichi-dev/difftaichi.git"

4. Click "Open in Visual Studio Code"

5. Open the Command Palette (Ctrl + Shift + P)

6. Search for the "Python: Create Environment" command

7. Choose ".venv"

8. Choose "Python 3.10.0 64-bit"

9. Select Install "requirements.txt"

10. Select `examples/diffmpm.py` and run using the run button in the upper right corner.

