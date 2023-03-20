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

To run a `python3` code run

    python3 main.py