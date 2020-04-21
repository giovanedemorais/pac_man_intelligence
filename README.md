# Pac Man Intelligence

## Install Conda and Git
* Follow this to download and install Git [link](https://git-scm.com/).

* Follow this to download and install conda [link](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html#installing-conda-on-a-system-that-has-other-python-installations-or-packages).

## Clone repository
`````
git clone git@github.com:MatteusStranger/pac_man_intelligence.git
`````

## Run using
`````
python main.py
`````
## What you need to know

* `sample.py` create maze from randomfill
* main use this function to get string maze
* main convert string to numpy array (numeric matrix n x m)
* main add random goal and block (you can choose the number of goal and block as parameter)
* main process maze random map with random goal, block and start position
* `randomfill` is a external folder used in this project (we use `wall.py`)

## Credits
* Maze generator: Used `randomfill` from  https://github.com/shaunlebron/pacman-mazegen
* Search method: Inspired by https://github.com/aimacode/aima-python/blob/master/search.ipynb