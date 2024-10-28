git init 

python -m dvc init 

python -m dvc add data_given/winequality.csv

git add . 

git commit -m "first commit" 

git remote add origin https://github.com/sarithamiryala/ml_project_winequality.git 

git branch _M main 

'''
git push origin main 
'''


dvc init 
dvc repro 

pytest -v 

setup command
'''
pip install -e .

''' 

