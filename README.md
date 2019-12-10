# ML-Information
AI and Machine Learning setup and resources

## MLNotes.docx: 
Notes on Data Science and Machine Learning for beginners. Includes references to online DataSets, resources and tutorials

## Keras Preprocessing: 
Functions for loading, converting, and saving image data. Notes: on Keras installation dependencies
The functions are in [utils.py](https://github.com/keras-team/keras/blob/master/keras/preprocessing/image.py) and exposed in [image.py](https://github.com/keras-team/keras-preprocessing/blob/master/keras_preprocessing/image/utils.py).

Keras image preprocessing libraries requires installation of [Pillow Library](https://pillow.readthedocs.io/en/stable/installation.html).

## ML environment:
There are multiple ways to develop and run machine learning models using a Windows 10 PC:
### 1. Use a VM (virtual machine) to run a Linux Desktop. 
Adam Geitgey preconfigured a VM with the most popular tools you will need, including:
* Python 3.5
* OpenCV 3.2 with Python 3 bindings
* dlib 19.9 with Python 3 bindings
* TensorFlow 1.5 for Python 3
* Keras 2 for Python 3
* face_recognition for Python 3 (for playing around with face recognition)
* PyCharm Community Edition already set up and ready to go for all these libraries
* Convenient code examples ready to run, right on the desktop!

Use this link for instructions on how to install and setup this VM:https://medium.com/@ageitgey/try-deep-learning-in-python-now-with-a-fully-pre-configured-vm-1d97d4c3e9b

Important information (cached): 
* Environment: http://ml.cdyne.com/Deep_Learning_Ubuntu_16.04_16-bit_2018_update.tar.gz
* VMware: http://www.vmware.com/products/player/playerpro-evaluation.html
* The username is ‘deeplearning’ and the password is ‘deeplearning’.

### 2. Cloud hosted using AWS with an AMI 
[Amazon Machine Image:](https://aws.amazon.com/marketplace/pp/B01EYKBEQ0/ref=_ptnr_wp_blog_post). Designed for developers as well as those eager to get started with the TensorFlow Deep Learning Framework.
Develop with Python using Jupyter Notebook. Udacity assignments for Deep Learning with TensorFlow are pre-installed.
Feature List:
  * Ubuntu 14 Linux
  * Nvidia Drivers
  * Cuda 7.5 Toolkit
  * cuDNN 5.1
  * TensorFlow 1.1.0
  * TFLearn
  * TensorBoard
  * Keras
  * Magenta
  * scikit-learn
  * Python 2 & 3
  * Hyperas
  * PyCuda
  * Pandas
  * NumPy
  * SciPy
  * Matplotlib
  * h5py
  * Enum34
  * SymPy
  * OpenCV
  * Jupyter to leverage Nvidia GPU as well as CPU instances.  
  
### 3. Local development environment using Powershell and Python (incomplete)
 Anaconda Windows (untested): https://www.anaconda.com/, https://docs.anaconda.com/anaconda/install/windows/
  * Python 2.7: https://repo.anaconda.com/archive/Anaconda2-2019.03-Windows-x86_64.exe
  * Python 3.7: https://repo.anaconda.com/archive/Anaconda3-2019.03-Windows-x86_64.exe
 Anaconda featues:
  * Conda - https://conda.io/en/latest/
  * scikit-learn - https://scikit-learn.org/stable/
  * TensorFlow - https://www.tensorflow.org/
  * Theano - https://pypi.org/project/Theano/
  * Dask - https://dask.org/
  * NumPy - http://www.numpy.org/
  * pandas - https://pandas.pydata.org/
  * Numba - http://numba.pydata.org/
  * Matplotlib - https://matplotlib.org/
  * Bokeh - https://bokeh.pydata.org/en/latest/
  * Datashader - http://datashader.org/
  * Holoviews - http://holoviews.org/
  
  
 ### 4. Direct download 
  Install [Python] (https://www.python.org/downloads/)
  
  To use TFLearn you must install Curses however, Windows 10 is not supported. The workaround is to use windows-curses: https://pypi.org/project/windows-curses/
  
  Install using powershell command: pip install windows-curses
  
