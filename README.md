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

dvc init

dvc add data_given/winequality.csv

git add .

git commit -n "First Commit"

