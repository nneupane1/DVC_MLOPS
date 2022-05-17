create env
```bash
conda create -n wineq python=3.9 -y
```

activate env
```bash
conda activate wineq
```

create a req file
```bash
pip install -r requirements.txt
```

create the data_given folder and load the downloaded data from:

https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec

git init
```bash
git init
```

dvc init
```bash
dvc init
```

```bash
dvc add data_given/winequality.csv
```

``` bash 
git add .
```

```bash
git commit -n "First Commit"
```

```bash
git commit -m "Update README.md"
```

```bash
git remote add origin https://github.com/nneupane1/DVC_MLOPS.git
git branch -M main
git push origin main
``` 

tox command -
```bash 
tox
```

for rebuilding -
```bash
tox -r 
```

pytest command
```bash
pytest -v
```

setup commands -
```bash
pip install -e .
```

build your own package commands-
```bash
python setup.py sdist bdist_wheel
```




