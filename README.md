# datafun-06-eda

This project is meant to show the ability to create an exploratory data analysis project using GitHub, Git, Jupyter, pandas, Seaborn, and other popular data anlytics tols. These tools will be used to pusblish a custom EDA project that tells a data story and visually present findings in a clear and engaging manner.

# Environment Setup
``` shell
py -m venv .venv
.\.venv\Scripts\activate
```

# Install Dependencies, Updgrade Pip, and Freeze requirements.txt
``` shell
py -m pip install jupyterlab
py -m pip install pandas
py -m pip install pyarrow
py -m pip install matplotlib
py -m pip install seaborn
py -m pip install --upgrade pip
py -m pip freeze > requirements.txt
```

# Add to gitignore
``` shell
.venv/
.vscode/
*~
.ipynb_checkpoints/
*.ipynb_meta/
```
