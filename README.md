# ML_lab
# Machine Learning Lab Environment Setup (ml_env)

#1. Prerequisites

Make sure Python and Git are available:

python3 --version

git --version

#2. Clone the Repository

git clone https://github.com/shabbeersh/ML_lab.git

cd ML_lab

#3. Install Required Libraries

Upgrade pip:

python -m pip install --upgrade pip

#4. create an environment named ml_env:

python -m venv ml_env

activate created environment:

source ~/ml_env/bin/activate

$5. Install all required libraries: (inside ml_env)

pip install -r requirements.txt

#6. Register the environment in Jupyter Notebooks

python -m ipykernel install --user --name=ml_env --display-name "Python 3.11 (ml_env)

#7 Start Jupyter Notebook

jupyter notebook

Create a new notebook and select:

New → Python (ml_env)

For an existing notebook:

Kernel → Change Kernel → Python (ml_env)
