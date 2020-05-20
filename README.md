#################### INSTALL PYTHON ENV #################

# CREATE FOLDER
mkdir ~/covid
cd ~/covid

# CREATE VIRTUAL ENV
virtualenv covid_env

# ACTIVATE ENV
source covid_env/bin/activate

# INCLUDE DATASETS
mkdir data
testset.csv + trainset.csv >> ./data/

# INSTALL PACKAGES
pip install jupyter

# START NOTEBOOK
jupyter notebook