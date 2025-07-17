# Creating the environment 

** conda create -p ./venv python=3.12 **
- p ./venv → creates the environment in a folder named venv in your current directory.
- python=3.12 → installs Python 3.12

- ipykernel 

# Creating the Virtual environment 
- There are three ways
- 1. Using the conda command -> conda create -p ./venv python=3.12
- 2. python -m venv myvenv ->  source foldername/bin/activate
-  3.  virtualenv -p python3 virtual_env ->  source virtual_env/bin/activate

** Note **
- create seperate environment for every project.