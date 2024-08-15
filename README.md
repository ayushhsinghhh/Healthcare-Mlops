create env

```bash
python -m env health
```
activate env

```bash
health\Scripts\activate
```

Install the requirements

```bash
pip install -r requirements.txt
```

Download the dataset from kaggle
https://www.kaggle.com/datasets/akshaydattat raykhare/diabetes-dataset

```bash
git init
```
```bash
dvc init
```
```bash
dvc add data_given\diabetes.csv
```
```bash
git add .
```
```bash
git commit -m "first commit"
```
Online updates for readmne
```bash
git add . git add . ; git commit -m "Update Readme"
```
```bash
git remote add origin https://github.com/ayushhsinghhh/Healthcare-Mlops.git
git branch -M main 
git push -u origin main
```