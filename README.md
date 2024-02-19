# datafun-07-ml

## Project Overview
This project utilizes Python to employ a type of supervised learning - simple linear regression - to train a model.

## Project Outcomes
- Build a model
- Make predictions
- Visualize the model
- Publish insights

## Project Setup
1. Create a repository on GitHub in the browser
2. Clone the repository
```
git clone https://github.com/bncodes19/datafun-06-eda
```
3. Create the virtual environment in the project folder
``` shell
python3 -m venv .venv
```
4. Activate the virtual enivronment
``` shell
source .venv/bin/activate
```
5. List the required packages in a text file "requirements.txt". There should be one package per line. The requirements file should look like this:
```
jupyterlab
pandas
pyarrow
numpy
matplatlib
seaborn
scipy
stats
```
6. Install the requirements file in a terminal
``` shell
python3 -m pip install -r requirements.txt
```
7. Freeze the requirements
``` shell
python3 -m pip freeze > requirements.txt
```
8. Create a .gitignore file in the project folder and add folders to ignore when uploading to GitHub:
```
.venv/
.vscode/
.DS_Store
.ipynb_checkpoints/
```
9. Add, commit, and push changes to the remote repo often
```
git add .
git commit -m "commit message"
git push origin main
```