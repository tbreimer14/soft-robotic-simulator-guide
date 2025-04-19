# EvoGym Installation & Setup

[GitHub](https://github.com/EvolutionGym/evogym)
[Docs](https://evolutiongym.github.io/documentation)

## Ubuntu

### Install Python 3.10.12 (Building From Source)

Skip this step if you already have Python 3.10 installed.

1. Install Required Packages
`sudo apt update`
`sudo apt -y build-dep python3`
`sudo apt -y install gdb lcov libbz2-dev libffi-dev libgdbm-dev libgdbm-compat-dev liblzma-dev libncurses5-dev libreadline6-dev libsqlite3-dev libssl-dev lzma lzma-dev tk-dev uuid-dev zlib1g-dev`
`
2. Download & Extract Python 3.10.12
`cd /usr/src`
`sudo wget https://www.python.org/ftp/python/3.10.12/Python-3.10.12.tgz`
`sudo tar xzf Python-3.10.12.tgz`

3. Build
`cd Python-3.10.12`
`./configure --enable-optimizations`
`make -s`
`sudo make altinstall`

4. Check version
`python3.10 -V`

### Install EvoGym

1. Install required packages
`sudo apt-get install xorg-dev libglu1-mesa-dev`

2. Create a virtual environment 
`python3.10 -m venv evogymvenv`

3. Activate virtual enviornment
`source evogymvenv/bin/activate`

4. Clone repo for examples
`git clone https://github.com/EvolutionGym/evogym.git`

5. Install EvoGym
`pip install evogym --upgrade`

6. Install cmaes
`pip install cmaes`

### Run Examples

1. Run a test example
`cd evogym/tutorials`
`python3 visualize_simple_env.py`

2. Run a CMA-ES demo
`cd cmaes-demo`
`python3 run.py`

## Windows

1. [Install VSCode](https://code.visualstudio.com/) (Allows for easy management of python virtual environments)

2. [Install GitHub Desktop](https://desktop.github.com/download/) (Allows for easy cloning of repositories)

3. [Install Python 3.10](https://www.python.org/downloads/release/python-31010/)

4. [Install Git](https://git-scm.com/downloads/win)

### Run Example

#### Basic CMA-ES Demo

1. Open GitHub Desktop

2. Click on "File > Clone repository"

3. Clone by URL: "https://github.com/tbreimer14/soft-robotic-simulator-guide.git"

4. Click "Open in Visual Studio Code"

5. Open the Command Palette (Ctrl + Shift + P)

6. Search for the "Python: Create Environment" command

7. Choose ".venv"

8. Choose "Python 3.10.0 64-bit"

9. Select Install "requirements.txt"

12. Select `cmaes-demo/run.py` and run using the run button in the upper right corner.





