# ohbm-handson-test

reproducing the awesome publication.

1. "code" includes python scripts
2. "data" includes thickness data from 259 subjects

 
# install the required python packages with pip:

```	
pip install -r requirements.txt
```

# clone and install the brainstat:

```
git clone https://github.com/MICA-MNI/BrainStat.git
cd BrainStat
python3 setup.py build
python3 setup.py install --user
```

# creating a virtual environment with pip:
```
pip install virtualenv #install the package
virtualenv --python=python3 mypythonenv #create a new virtual environment
source mypythonenv/bin/activate #activate the virtual environment
```

# now install your packages with pip and do the analysis
	
deactivate #deactivate the virtual environment


# running the code
navigate to the "code" directory firstly and run the "analysis_01.py" script.

```
$ cd code
$ python3 analysis_01.py
```

# running on cloud:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sheyma/ohbm-handson-test/HEAD)

