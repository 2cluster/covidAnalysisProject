# INSTALL PYTHON ENV

#### CREATE FOLDER
mkdir ~/covid
cd ~/covid

#### CREATE VIRTUAL ENV
virtualenv covid_env

#### ACTIVATE ENV
source covid_env/bin/activate

#### INCLUDE DATASETS
mkdir data
testset.csv + trainset.csv >> ./data/

#### INSTALL PACKAGES
pip install jupyter

#### START NOTEBOOK
<<<<<<< HEAD
jupyter notebook
=======
jupyter notebook
>>>>>>> c78282da8ad40a67083a69ebd5af99639f1f9807
