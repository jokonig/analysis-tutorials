# O2AT - Third edition - Machine Learning primer

Welcome to the O2AT ML tutorial. Today we will have a look at how to train Boosted Decision Trees (BDTs) in Python and how to export and use a ML model in O2Physics analyses.

Before we start some preliminary steps are needed. Follow them hereafter!

## SWAN setup

We will run this tutorial on CERN SWAN, so click here

[![Open in SWAN](https://swanserver.web.cern.ch/swanserver/images/badge_swan_white_150.png)](https://cern.ch/swanserver/cgi-bin/go?projurl=https://github.com/AliceO2Group/analysis-tutorials.git)

to go to SWAN and automatically download this repository.

To have the right environment configure SWAN in this way:

- **Software stack**: 102b
- **Environment script**: /eos/user/a/alicesk/O2AT_ML_3/setup.sh

You should have this setup

<img src="swan_cfg.png" alt= “swan_conf” width="50%">

## Tutorials

The tutorials will be given using [Jupyter](https://jupyter.org/) Notebooks.

### BDT classification

For this tutorial open the `DsBDTrun3.ipynb` notebook in the folder `analysis-tutorials/o2at-3/machineLearning/BDTClassification`.

### O2Physics

Info TOBEADDED

---

## "Power-user" setup

If you feel experienced enough and you want to run the tutorials on your PC, the following instructions will help you to setup the needed Python environment and to launch the Jupyter notebooks. These instructions are also helpful in case you would like to start your ML project.

1. Clone this repository

```bash
git clone https://github.com/AliceO2Group/analysis-tutorials.git
```

2. Create a Python environment in your home directory

```bash
python3 -m venv ~/.virtualenvs/O2AT3_ML
```

3. Activate the Python environment (you will have to do it each time you want to run this code)

```bash
source ~/.virtualenvs/O2AT3_ML/bin/activate
```

4. Install the required packages (it could take some time depending on your connection)

```bash
pip3 install --upgrade pip setuptools
pip3 install notebook hipe4ml hipe4ml_converter
```

5. Lauch the Jupyter server (from the tutorial repository folder)This is a placeholder.
