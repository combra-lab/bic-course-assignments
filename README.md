# CS425/525 Assignments（Spring 2023)

## 0x00

This repository contains the assignments for the course CS425/525 Brain Inspired Computing.

To run the assignments, you will need to setup a programming environment. The basic requirements are listed below:

- Python 3.7 or higher
- Numpy, Scipy, Matplotlib, Jupyter Notebook/lab
- PyTorch 1.2 or higher (Cuda compatibility is **not** required)

There are **two** ways to set up an environment with the basic requirements:

## iLab Machine (perfered)

### Register for a CS computing account

We strongly recommend you to use the ilab machines for the purpose of running the assignments. All students registered for CS 425/525 have access to the ilab machine through the CS computing account. If you do not have a CS computing account, please read the following webpage and follow the instructions to get a CS account: https://resources.cs.rutgers.edu/docs/new-users/getting-started/.

### Connect to the iLab machine

- With your CS account enabled, simply go to: https://weblogin.cs.rutgers.edu. Login through your CS account credentials. And click on any of the ilab machines to continue. You can check the avaliablity of iLab machines by https://report.cs.rutgers.edu/nagiosnotes/iLab-machines.html
  More details here: https://resources.cs.rutgers.edu/docs/using-cs-weblogin-to-access-ilab-machines/

- Once you are connected to the ilab machine, open a terminal and config the environment by the following command:
  `echo "export PATH=\$PATH:/koko/system/anaconda/bin" >> ~/.bashrc && source ~/.bashrc`.
- You can check the result by `cat ~/.bashrc`, if `export PATH=\$PATH:/koko/system/anaconda/bin` locates at the last line of the file, then everthing for configuration is good. You will not need to find and switch to the `activate` script from now on.

- Switch to the environment prefix **(python37)** by `source activate python37`.

- Once you have activated the environment, go to **the directory where your assignment file resides** and run jupyter lab using: `jupyter lab`.
  This will open Jupyter lab in a browser, and you will be able to access your assignment file, edit it, and run it.

Note: If you are using ilab machines, be aware of your storage quota for different directories. The storage options that the CS department provides you with are listed here : https://resources.cs.rutgers.edu/docs/file-storage/storage-technology-options/

## Local machine

We strongly recommend you to use ilab using the method described above, and we are here to help if you have any issues connecting to ilab. However, if you want to setup the programming environment on your own local machine, you will need to first create an anaconda environment (https://www.anaconda.com/products/individual). Then activate the conda environment and install Pytorch (https://pytorch.org/). All other required packages come preinstalled with anaconda distribution.

Activate the environment, go to the directory where your assignment file resides and run jupyter lab using: `jupyter lab`
This will open Jupyter lab in a browser, and you will be able to access your assignment file, edit it, and run it.

## Running the Assignments

Simply download the assignment files and follow the steps outlined in the easy way or difficult way.
