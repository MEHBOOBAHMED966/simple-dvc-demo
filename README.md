craete new env


 '''bash
conda create -n wineq python=3.8.9 -y
'''

activate env
'''bash
conda activate wineq
''''
create reqirements file
'''bash
pip install -r requirement.txt
'''


download the data

git init

dvc init

dvc add given_data/winequality.csv

git add .

git commit -m "first commit"
