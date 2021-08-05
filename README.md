# Final-year-project


## Prerequisite:

Python 3.8 installed and running.


## Installation:
```
git clone https://github.com/S-P-RAJAT/final-year-project.git
python3 -m venv venv
. venv/bin/activate
python3 -m pip install --upgrade pip
python3 -m pip install -r requirements.txt
```

## Execution:


### Running the front-end:

```
cd front-end/
export FLASK_APP=ui
export FLASK_ENV=development
flask run
```
### Running the model:
```
cd code/
python3 PrOCTOR.py
python3 randomForest.py
```
