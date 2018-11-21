Anaconda packages management demo

------------------------------------------------------------

install anaconda from terminal, graphical interface installer
https://www.anaconda.com/download/#macos

create conda virtual environment
$ conda create -name virtual_environment_name python=3.6

install relevant packages, exported from conda virtual environment by

create packages for environment
$ conda list -e > requirements.txt

install packages
$ conda install, numpy, matplotlib, tensorflow, keras, ...
or
$ conda install --yes --file requirements.txt

get virtual environment interpreter location
$ source activate virtual_environment_name
$ which python

--------------------------------------------------------

PyCharm use Anaconda virtual environment

New Project -> Scientific -> expand Project Interpreter -> choose existing interpreter -> browse to virtual environment lcoation ()

can use virtual environment libraries

run main.py for python interpreter testing
run models/binary_classification_demo.py for virtual environment's package testing

--------------------------------------------------------
