## Instructions for installation of packages.

$sudo pip install virtualenv

Create  virtualenv devoid of any packages in a directory called _notebook

$virtualenv --no-site-packages _notebook

$cd _notebook

$source bin/activate

$pip freeze

There should not be anythin installed.

# Install numpy,pandas,matplotlib, ipython[all] and seaborn

pip install numpy

pip install pandas

pip install matplotlib

pip install ipython[all]

pip install seaborn

Now you are good to run the notebook.