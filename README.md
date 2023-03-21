# Horndeski

## Setup (Only run once)

First run the following

    export VENV_PATH=~/VirtualEnv/horn_project
    python3 -m venv $VENV_PATH
    source ~/VirtualEnv/horn_project/bin/activate
    pip install -U pip setuptools
    pip install poetry

Enter the repository directory

    cd horn_project

And install the necessary packages

    poetry install

## Actual work

Run

    source ~/VirtualEnv/horn_project/bin/activate

Enter directory 

    cd horn_project

To run a `python3` code run

    python3 main.py

## To Do List

- Understand each parameter for Horndeski specific case.
- Go to [https://github.com/miguelzuma/hi_class_public/blob/hi_class/python/classy.pyx](https://github.com/miguelzuma/hi_class_public/blob/hi_class/python/classy.pyx), and understand functions `raw_cl`, `lensed_cl`, etc. what do they return? it's a dictionary, but physically what does the `tt`, `te`, etc. stands for.
