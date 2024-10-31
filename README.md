# PROG8431
Data Analysis Mathematics, Algorithms and Modeling

### Dataset Reference
[Kaggle Reference Dataset](https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions)

### Prompt Reference
[ChatGPT Prompt](https://chatgpt.com/share/b01801a0-5371-4e0e-bfee-1355002bac6c)

### Project and environment setup

1. Move to project directory "PROG8431" where you have cloned the project
2. Create virtual environment with name **"venvPROG8431"**
    - Make sure ```python --version``` is set to **12.3.6** in your system
    - ```python -m venv venvPROG8431```
3. Activate environment
    - ```.\venvPROG8431\Scripts\Activate.ps1```
    - In case you are using visual studio code, Choose the environment from menu as active environment
4. Install packages mentioned in **"requirements.txt"**
    - ```pip install -r requirements.txt```
5. Select **"venvPROG8431"** environment in your IDE
6. Create folder named **"Dataset"** in your project directory
7. Move all files downloaded from Kaggle dataset in the "Dataset" Directory
8. Open "Workshop1.ipynb" and run first program snippet. 
9. It should display top 5 rows from file "RAW_recipe.csv"


### Update Requirements.txt file once installing new packages

```pip freeze > requirements.txt```
