# datafun-06-eda
### Module 6 Project  
Create a custom exploratory data analysis (EDA) project using GitHub, Git, Jupyter, pandas, Seaborn and other popular data analytics tools.

## Install and Run the Project
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

### 3. Create Virtual Environment  
```
py -m venv .venv
```

### 4. Activate Virtual Environment  
Always make sure to be in the virtual environment when installing packages and running scripts.  
```
.venv\Scripts\activate
```

### 5. Install Dependencies  
Install necessary dependecies for the project.  

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

### 6. Set VS Code Interpreter  
    * Open Command Palette: `Ctrl+Shift+P`  
    * Search "Python: Select Interpreter"  
    * Chose local .venv option  

### 7. Create Jupyter Notebook  
    * Enter `jupyter lab` in terminal  
    * Click Python 3 button under "Notebook" section  
    * Right click notebook tab to rename  
    * `.ipynb` file type.  
    * Make sure the correct kernel is set  
        * Click on `Select Kernel`  
        * Select `Python Environments`  
        * Choose the recommended `.venv` option  