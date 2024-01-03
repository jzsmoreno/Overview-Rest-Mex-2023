# Overview-Rest-Mex-2023
This repository presents a possible solution and results from the Rest-Mex task at IberLEF 2023.

## Project structure

The project is structured as follows:

    ├── notebooks
    │   ├── data
    │   │   ├── raw
    │   │   │   ├── .gitignore
    │   │   │   └── Readme.txt
    │   │   └── README.md
    │   ├── images
    │   ├── saved_model
    │   ├── eda.ipynb
    │   ├── ner.ipynb
    │   └── test.ipynb
    ├── .gitignore
    ├── 6572-6067-1-PB1.pdf
    ├── LICENSE
    ├── README.md
    └── requirements.txt

## Setup

To install the dependencies, you can simply follow this steps.

Clone the project repository:
```bash
git clone https://github.com/jzsmoreno/Overview-Rest-Mex-2023.git
```

To create and activate the virtual environment, follow these steps:

**Using `conda`**

```bash
$ conda create -n test python=3.10

# Activate the virtual environment:
$ conda activate test

# To deactivate (when you're done):
(test)$ conda deactivate
```

**Using `virtualenv`**

```bash
# In this case I'm supposing that your latest python3 version is 3.10
$ virtualenv test --python=python3

# Activate the virtual environment:
$ source test/bin/activate

# To deactivate (when you're done):
(test)$ deactivate
```

To install the requirements using `pip`, once the virtual environment is active:
```bash
(test)$ pip install -r requirements.txt
```