# Bias mitigation & fairness metrics [INFO381]

This project demonstrates the use of IBMs AIF360 toolkit for a semester assignment in a AI course at the University of Bergen. 

See: [https://github.com/IBM/AIF360](https://github.com/IBM/AIF360)

## Getting Started

Follow these instructions to setup a virtual environment and install all the prerequisites to run the project. 

### Prerequisites

Initialize a virtual environment for Python3

```
# Using Python3's built in virtualenv
python3 -m venv ./.venv

# Using virtualenv 
virtualenv mypython ./.venv

# Activate env

For Windows
.venv/Scripts/activate.bat

For Unix
source ./.venv/bin/activate
```
Install dependencies

```
pip3 install -r requirements.txt
```

Install kernel

```
ipython kernel install --user --name=.venv
```

##### Even though AIF360 is installed as a dependency, you might need the full package:

```
git clone https://github.com/IBM/AIF360.git

cd AIF360

pip install .
```

### Problems and fixes
#### Ubuntu
When installing requirements in Ubuntu, change numpy version in requirements to numpy==1.16.3

## Authors

* Tor H. Aasheim
* Knut T. Hufthammer
* Sølve Ånneland
* Håvard Brynjulfsen
