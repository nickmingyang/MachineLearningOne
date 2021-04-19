# MachineLearningOne

## Installing Virtual Enviroment

### Prerequisites
- Ensure Python 3.9 is installed in your machine  
### Instructions
- Clone this repo in the desired directory
- `cd` to the directory where you wish to save the env. To ensure that we don't accidentally upload the env to GitHub I recommend not creating the env in the same directory you cloned this git repo and having a separate directory exclusively for the env. 
- Use the following command to create the env using Python 3.9 `Python3.9 -m venv <NameOfEnviroment>`
- Go to the directory of the newly created env `cd <NameOfEnviroment>` 
- Activate the environment using the following command  `source bin/activate`. To verify the env is activated check if the name of the env is infront of the terminal prompt. `(<NameOfEnviroment>)`
- To verify your env is using Python 3.9 used `python -V`
- `cd` back to the directory containing the `requirements.txt` file and `pip install -r requirements.txt` 
- Use `pip freeze` to ensure all packages are properly installed 
### Libraries installed
- `scikit-learn==0.24.1`
- `jupyter-server==1.6`
- `scipy==1.6.2`
- `numpy==1.20.2`
- `pandas==1.2.4`
- Other libraries that are dependancies to the ones mentioned above 

