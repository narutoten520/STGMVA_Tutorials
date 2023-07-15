.. STGMVA documentation master file, created by
   sphinx-quickstart on Fri Jul 14 20:17:30 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Installation
============

The STGMVA package is developed based on the Pytorch_pyG framework and can be implemented on both GPU and CPU. 
We recommend running the package on GPU. Please ensure that pytorch and CUDNN are installed correctly. To run STGMVA, all dependencies included in the file 'requirementa.txt' need to be installed. We provide two ways to install the package of STGMVA.

Please note that the current STGMVA version offers full support of Linux operating system. Further version for other operating systems would be released soon.

1. Python
---------------------

Dowloading the package from https://github.com/narutoten520/STGMVA

.. code-block:: python

   pip install STGMVA
   
   or

   git clone https://github.com/narutoten520/STGMVA.git
   
   cd STGMVA
   
   python setup.py build
   
   python setup.py install --user

2. Anaconda
------------
For convenience, we suggest using a separate conda environment for running STGMVA. Please ensure annaconda3 or miniconda is installed.

Create conda environment and install STGMVA package.

.. code-block:: python

   #create an environment called STGMVA
   conda create -n STGMVA python=3.9
   
   #activate your environment
   conda activate STGMVA
   
   #install package
   
   pip install STGMVA
   
   or 
   
   git clone https://github.com/narutoten520/STGMVA.git
   
   cd STGMVA
   
   python setup.py build
   
   python setup.py install --user
   
   #To use the environment in jupyter notebook, add python kernel for this environment.

   pip install ipykernel

   python -m ipykernel install --user --name=STGMVA
   
