create env

'''bash
python -m env health
'''
activate env
'''bash
health\Scripts\activate
'''
Install the requirements
'''bash
pip install -r requirements.txt
'''
Download the dataset from kaggle
https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset

git init

dvc init

dvc add data_given\diabetes.csv

git add .

git commit -m "first commit"