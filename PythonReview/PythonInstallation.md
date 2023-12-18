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
* Check if conda is installed correctly, by typing:
```
conda -V
```
You should see the following (or something similar):

![image](https://github.com/coursesAM/APL405W24/assets/109568856/bacae894-63dd-42d5-83a1-f75409e96930)

* Check if Python is installed properly by typing:
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

* Check if required libraries are installed or not
There are certain key libraries that you would require for machine learning: SciPy, NumPy, Matplotlib, Pandas, Statsmodels, and Scikit-learn.

You can type "python" and type the following commands in the anaconda prompt directly. 

![image](https://github.com/coursesAM/APL405W24/assets/109568856/7312f298-af43-44f9-8a1a-8df0b2ae1e77)

<img src="https://github.com/coursesAM/APL405W24/assets/109568856/ae6a58b1-47a2-4201-b386-4b633bd144d5" width="30%" height="30%">

Alternatively, I recommend opening a text editor and copy-pasting the following script into your editor. 
```python
# scipy
import scipy
print('scipy: %s' % scipy.__version__)
# numpy
import numpy
print('numpy: %s' % numpy.__version__)
# matplotlib
import matplotlib
print('matplotlib: %s' % matplotlib.__version__)
# pandas
import pandas
print('pandas: %s' % pandas.__version__)
# statsmodels
import statsmodels
print('statsmodels: %s' % statsmodels.__version__)
# scikit-learn
import sklearn
print('sklearn: %s' % sklearn.__version__)
```
Save the script as a file with a name (say): *versions.py*

On the Anaconda prompt, change your directory to where you saved the script, and type:
```
python versions.py
```
and you should see the output like the following:

![image](https://github.com/coursesAM/APL405W24/assets/109568856/4660d600-5324-41d7-b008-6d8eba5ab29b)


# Update libraries to the latest version

You can update a specific library by using the conda command; below is an example of updating the scikit-learn to the latest version.

For example, at the Anaconda prompt, you type:
```
conda update scikit-learn
```
Alternatively, you can update a library to a specific version by typing:
```
conda install -c anaconda scikit-learn=<insert_version_number>
```
After installation, you can double-check by re-running the *versions.py* script.

# Install PyTorch deep learning library

In this step, you will install Python libraries used for deep learning, specifically PyTorch.

PyTorch is a complete library that can train a deep learning model as well as run a model in inference mode and supports using GPU for faster training and inference.

**NOTE**: I recommend using PyTorch for deep learning, although you can also use TensorFlow. You would not need both! 

* Create a separate conda environment for your PyTorch installation, as it will allow you to manage its dependencies independently from the base Python installation. This will ensure a clean and isolated workspace for your deep learning projects.

  To create a new Conda environment, type the following command, replacing `<env_name>` with a descriptive name for your environment (e.g. `pytorch-cpu-python-3-11`).

  ```
  conda create --name pytorch-cpu-python-3-11 python=3.11
  ```
  This will create a `pytorch-cpu-python-3-11` environment.
  
![image](https://github.com/coursesAM/APL405W24/assets/109568856/d4d27880-8fab-4554-bd90-ac1dd429f0a7)

 Note that you have to mention the Python version that you want to install in this new environment.  
 
 Conda will install all essential packages in the new environment (after you give permission). 
 
 Upon finishing, you will be able to find the new environment in the Anaconda Navigator (if you wish to see it)
 
 ![image](https://github.com/coursesAM/APL405W24/assets/109568856/d0106b8f-ea2a-42c7-b361-0d63e6af856e)

You can activate the newly created environment by typing

```
conda activate pytorch-cpu-python-3-11
```

 ![image](https://github.com/coursesAM/APL405W24/assets/109568856/9462e2ef-43a2-4a1a-9de9-0a33dd47f09a)

Now you need to install PyTorch in this new environment. 

```
conda install pytorch torchvision torchaudio cpuonly -c pytorch
```
![image](https://github.com/coursesAM/APL405W24/assets/109568856/64aaa74e-c531-42a0-a5de-54b1c39cfa49)










  
