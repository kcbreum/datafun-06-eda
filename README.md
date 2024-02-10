# datafun-06-eda

## Project Description
This project is meant to show the ability to create an exploratory data analysis project using GitHub, Git, Jupyter, pandas, Seaborn, and other popular data anlytics tols. These tools will be used to pusblish a custom EDA project that tells a data story and visually present findings in a clear and engaging manner.

## Project Setup

### Create Virtual Enviornment
``` shell
py -m venv .venv
py -m .\.venv\Scripts\activate
```

### Install Dependencies and Upgrade Pip
``` shell
py -m pip install jupyterlab
py -m pip install pandas
py -m pip install pyarrow
py -m pip install matplotlib
py -m pip install seaborn
py -m pip install --upgrade pip
```

### Freeze Requirements
``` shell
py -m pip freeze > requirements.txt
```

### Add to gitignore
``` shell
.venv/
.vscode/
*~
.ipynb_checkpoints/
*.ipynb_meta/
```
## Git Add and Commit
``` shell
git add .
git commit -m "update README"
git push origin main
```
