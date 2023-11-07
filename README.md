git init

dvc init

dvc add data_given/wine-quality.csv

git add .

git commit -m "first commit"


dvc repro

dvc metrics show