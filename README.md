# car-dealership-tool
**car-dealership-app** is a web application developed using django framework. This system offers user-friendly interface to manage car/bike inventory.
---
## Installation:
    - Create Python Virtual Environment: 
        `python -m venv .venv`

## Activate Virtual Environment:
    - In cmd.exe
        `.venv\Scripts\activate.bat`
    - In PowerShell
        `.venv\Scripts\Activate.ps1`
    - Linux and MacOS
        `source .venv/bin/activate`

## Install requirements 
    `pip3 install -r requirements.txt`

## Create Required DB Schema
    `python3 manage.py migrate`

##  Start server
    `python3 manage.py runserver`

## Deactivate the Python venv
    `deactivate`
