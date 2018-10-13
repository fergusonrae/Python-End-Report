# Python End Report

This repo was created to hold the final report for my Python independent study at the Milwaukee School of Engineering.

The final report was created as a Jupyter Notebook. It is made to be easy to read without interaction. You can do this in browser by clicking the PythonEndReport1.ipynb link in the repo.

However, if you would prefer to run the code in the notebook, the easiest way to run this notebook in your browser is through conda.

### Install miniconda
https://conda.io/miniconda.html

### Create a virtual environment
Mac Terminal or Windows Anaconda Prompt
```
$ conda create -n python_report
```

### Activate it
Mac Terminal
```
$ source activate python_report
```

Windows Anaconda Prompt
```
$ activate python_report
```

### Install packages
```
(python_report) $ conda install pip
(python_report) $ pip install -r requirements.txt
```


### Run it
```
(python_report)$ jupyter notebook
```
This will open the active directory in your browser. Navigate to the directory with the repo and select 'Image Processing Hands On.ipynb'. This will open the notebook.

## When finished

Head back to the command line and push CTRL-C. This will close the notebook. Then, close the browser tabs that were opened.

### Close the virtual environment
Mac Terminal
```
(python_report)$ source deactivate
```

Windows Anaconda Prompt
```
(python_report)$ deactivate
```
