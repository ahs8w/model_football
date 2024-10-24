# Model Based Fantasy Football

## Environment installation instructions:

```
# use pyenv to manage python installations
brew install pyenv

# install python [if needed]
pyenv install <version>  
# set default project python version (sets .python-version file)
pyenv local <version>

# create a virtual environment (recommended)
python -m venv .venv
# activate the virtual environment 
source .venv/bin/activate
# install all dependencies for local development
pip install -r requirements.txt
```