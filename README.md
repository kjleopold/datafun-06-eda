# datafun-06-eda
### Module 6 Project  
Create a custom exploratory data analysis (EDA) project using GitHub, Git, Jupyter, pandas, Seaborn and other popular data analytics tools.  
I have chosen to explore a 2024 video game sales dataset.

## Start a New Project
### 1. Project Setup  
- Create repo named datafun-04-eda in browser with a default README.md.  
- Clone repo to local  
```
git clone (paste repo URL)
```
- Create .gitignore file in root project folder  
    * Copy/pasted template from Module 4 example  
- Add requirements.txt in root project folder  
    * Copy/pasted template from Module 4 example and added pyarrow and jupyterlab  

### 2. Git add-commit-push  
Push changes from local to GitHub with clear commit message.  
```
git add .
git commit -m "Add a message with a clear and descriptive note about what you added or changed."
git push
```

## Create Virtual Environment  
### 1. Create `.venv`
```
py -m venv .venv
```
### 2. Activate Virtual Environment  
Always make sure to be in the virtual environment when installing packages and running scripts.  
```
.venv\Scripts\activate
```
### 3. Set VS Code Interpreter
* Open Command Palette: `Ctrl+Shift+P`
* Search "Python: Select Interpreter"
* Chose local .venv option  

## External Dependencies 
### Install necessary dependecies for the project using requirements.txt file.  

Known dependencies for this project at the start:  
* jupyterlab
* pandas
* pyarrow
* matplotlib
* seaborn
```
py -m pip install --upgrade pip setuptools wheel
py -m pip install -r requirements.txt
```

## Create Jupyter Notebook  
### 1. Enter `jupyter lab` in terminal
### 2. Click Python 3 button under "Notebook" section
### 3. Right click notebook tab to rename
### 4. Make sure the file type is `.ipynb`.
### 5. Make sure the correct kernel is set
* Click on `Select Kernel`
* Select `Python Environments`
* Choose the recommended `.venv` option

## Select a Dataset, Provide a Link and a Description
* Data Source: [https://www.kaggle.com/]  
* Dataset: [https://www.kaggle.com/datasets/willianoliveiragibin/video-game-sales-analyze]  
* Description: This dataset shows data for video game sales for titles released through 2020.  

## Exploratory Data Analysis
* Data acquisition
* Initial data inspection
* Initial descriptive statistics
* Initial data distribution for numerical columns
* Initial data distribution for categorical columns
* Initial data transformation and feature engineering
* Initial visualizations
* Initial storytelling and presentation