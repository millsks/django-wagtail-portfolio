# django-wagtail-portfolio
A Python web application built on top of Django and Wagtail to show off project portfolio to incoming visitors.

## Create the required Python environment
### Install Miniforge
``` bash
wget https://github.com/conda-forge/miniforge/releases/download/24.1.2-0/Miniforge3-24.1.2-0-Linux-x86_64.sh
bash Miniforge3-24.1.2-0-Linux-x86_64.sh -b -p miniforge/py310-24120
```

### Create the conda environment
``` bash
mamba create -n django-wagtail-portfolio python=3.11 django=4.2 django-wagtail cruft
```

## Clone the django-wagtail-portfolio repository
You will clone the django-wagtail-portfolio repository to your local system.

``` bash
git clone -b develop git@github.com:millsks/django-wagtail-portfolio.git
```
