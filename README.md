# pgh-ds-automl

## Setup

[BeakerX](http://beakerx.com/documentation#tutorials-and-examples)

### Installation with Conda
It is recommended to use conda to install Jupyter and BeakerX, and to manage your Python environments. BeakerX works with Python 3.4 and above. Conda forge hosts the latest version.

```
conda create -y -n beakerx 'python>=3'
source activate beakerx
conda config --env --add pinned_packages 'openjdk>8.0.121'
conda install -y -c conda-forge ipywidgets beakerx
```

To run jupyter notebook on windows run `activate beakerx`, or `source activate beakerx` on Max or Linux.  

Next run `jupyter notebook`.  
