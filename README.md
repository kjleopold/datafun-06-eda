# datafun-06-eda
## Module 6 Project
Create a custom exploratory data analysis (EDA) project using GitHub, Git, Jupyter, pandas, Seaborn and other popular data analytics tools.

## Install and Run the Project
### 1. Project Setup  
- Create repo named datafun-04-eda  

- Clone repo to local  
    ```
    git clone (paste repo URL)
    ```  

- Create .gitignore file in root project folder  
    * Copy/pasted template from Module 4 example  

- Add requirements.txt in root project folder  
    * Copy/pasted template from Module 4 example  

- Git add-commit-push  
    ```
    git add .
    git commit -m "Meaningful comment added"
    git push
    ```

- Create Virtual environment  
    ```
    py -m venv .venv
    ```

### 2. Repeatable Workflow  
- Pull latest changes from GitHub if necessary
    ```
    git pull
    ```

- Activate Virtual Environment
    ```
    .venv\Scripts\activate
    ``` 

- Install Dependencies
    ```
    py -m pip install --upgrade pip setuptools wheel
    py -m pip install -r requirements.txt
    ```

- Set VS Code Interpreter
    * Open Command Palette: `Ctrl+Shift+P`
    * Search "Python: Select Interpreter"
    * Chose local .venv option

- Create Jupyter Notebook
    * Enter `jupyter lab` in terminal
    * Click Python 3 button under "Notebook" section
    * Right click notebook tab to rename
    * `.ipynb` file type.
    * Make sure the correct kernel is set