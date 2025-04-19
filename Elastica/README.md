# Elastica Installation & Setup

[GitHub](https://github.com/GazzolaLab/PyElastica)
[Docs](https://www.cosseratrod)
[Tutorial](https://mybinder.org/v2/gh/GazzolaLab/PyElastica/master?filepath=examples%2FBinder%2F0_PyElastica_Tutorials_Overview.ipynb)

## Ubuntu

1. Install python3 
`sudo apt-get install python3`

2. Create a virtual environment 
`python3 -m venv elasticavenv`

3. Activate virtual enviornment 
`source elasticavenv/bin/activate`

4. Clone example repo
`git clone git@github.com:GazzolaLab/PyElastica.git`

5. Install requirements 
`pip install "pyelastica[examples,docs]"`

6. Run soft robot with cma optimizer example 
`python3 ContinuumSnakeCase/continuum_snake.py`

## Windows

1. [Install VSCode](https://code.visualstudio.com/) (Allows for easy management of python virtual environments)

2. [Install GitHub Desktop](https://desktop.github.com/download/) (Allows for easy cloning of repositories)

3. [Install Python 3.10](https://www.python.org/downloads/release/python-31010/)

4. [Install Git](https://git-scm.com/downloads/win)

### Run Example

1. Open GitHub Desktop

2. Click on "File > Clone repository"

3. Clone by URL: "https://github.com/tbreimer14/soft-robotic-simulator-guide.git"

4. Click "Open in Visual Studio Code"

5. Open the Command Palette (Ctrl + Shift + P)

6. Search for the "Python: Create Environment" command

7. Select ".venv"

8. Choose "Python 3.10.0 64-bit"

9. Open the terminal (Ctrl + `)

10. Run `pip install PyElastica`

11. Select `ContinuumSnakeCase/continuum_snake.py` and run using the run button in the upper right corner.








