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


