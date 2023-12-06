# How to Setup Your Python Environment for Machine Learning

It can be difficult to install a Python machine learning environment on some devices. Python itself must be installed first and then there are many packages to be installed, and it can be confusing for beginners.

Here, I present how I set up my own Python machine learning IDE using Anaconda. You can follow the same to install and code in Python.

I will demonstrate the installation instructions on Windows, so you may see some Windows dialogs and file extensions. However, these instructions may also be suitable for MAC OS and Linux platforms. 

# Overview
We will cover the following steps:

1. Download and Install Anaconda
2. Start and update Anaconda

# 1. Download and install Anaconda
Anaconda is a free and easy-to-use environment for scientific Python.

* Download the Anaconda Python package for the appropriate OS (Windows/MAC/Linux) from [Anaconda webpage](https://www.anaconda.com/download). The file is about 1 GB.
* For installation, follow the instructions [here](https://docs.anaconda.com/free/anaconda/install/).

# 2. Start and update Anaconda
You should confirm that your Anaconda python environment is up to date.

Anaconda comes with a set of graphical tools which you can find in the Anaconda Navigator. You can start the Anaconda Navigator GUI by opening it. You can learn more about the Navigator [here](https://docs.continuum.io/free/navigator/)

![image](https://github.com/coursesAM/APL405W24/assets/109568856/80ef2ac3-13c7-469e-bb60-961307346c9e)

You can use the Anaconda Navigator to open graphical environments like Spyder or Jupyter, however, for now, I recommend starting with Anaconda command line environment called **conda**.

**Conda** is simple and fast and you can quickly check if your environment is installed and working correctly.

* Open an Anaconda prompt
* check if conda is installed correctly, by typing:
```
conda -V
```
You should see the following (or something similar):

![image](https://github.com/coursesAM/APL405W24/assets/109568856/bacae894-63dd-42d5-83a1-f75409e96930)

* Check if python is installed properly by typing:
```
python -V
```
You should see the following (or something similar):

![image](https://github.com/coursesAM/APL405W24/assets/109568856/53c74375-f927-41d4-a42a-053671aec3eb)

If the commands do not work or they throw an error, check with the documentation for help (based on your OS/platform).

* Check if your conda environment is up-to-date, by typing:
```
conda update conda
conda update anaconda
```

* confirm the Scipy environment



  
