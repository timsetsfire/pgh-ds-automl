# pgh-ds-automl

## Setup

[BeakerX](http://beakerx.com/documentation#tutorials-and-examples)

### Installation with Conda
It is recommended to use conda to install Jupyter and BeakerX, and to manage your Python environments. BeakerX works with Python 3.4 and above. Conda forge hosts the latest version.

```
conda create -y -n beakerx 'python>=3'
source activate beakerx
conda config --env --add pinned_packages 'openjdk=8.0.152'
conda install -y -c conda-forge ipywidgets beakerx
```

To run jupyter notebook on windows run `activate beakerx`, or `source activate beakerx` on Max or Linux.  

Next run `jupyter notebook`.  

### Notebooks

* Scala in 10 minutes - quick intro to scala.  Maybe more like 30 minutes, but this will get you up and running in Scala pretty quick.  
* Spark Test - check that spark runs on your machine.  
* Spark and TransmogrifAI Shell V2 - this is the main notebook for PGH Datascience Meetup.  