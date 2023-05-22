# Python-Programming

This Repository includes basic python for data science notebooks. Content is as follow;

Module 1 Basics of Python

Module 2 Data Types and Data Structures

Module 3 Data Frames

Module 4 Data Manipulation

Module 5 Outlier Detection

Module 6 Missing Value Imputation

Module 7 Visualization

Assignments


# Python Installation

We highly recommend using anaconda for installing python. Click here to go to Anaconda's download page. Make sure to download Python 3.6 version. If you are on a windows machine:

Open the executable after download is complete and follow instructions.
Once installation is complete, open Anaconda prompt from the start menu. This will open a terminal with python enabled.
If you are on a linux machine:

Open a terminal and navigate to the directory where Anaconda was downloaded.

Change the permission to the downloaded file so that it can be executed. So if the downloaded file name is Anaconda3-5.1.0-Linux-x86_64.sh, then use the following command:

chmod a+x Anaconda3-5.1.0-Linux-x86_64.sh

Now, run the installation script using ./Anaconda3-5.1.0-Linux-x86_64.sh, and follow installation instructions in the terminal.

Once you have installed python, create a new python environment will all the requirements using the following command:

conda env create -f environment.yml
After the new environment is setup, activate it using (windows)

activate machine_learning
or if you are on a linux machine

source activate machine_learning 
Now we have our python environment all set up, we can start working on the assignments. To do so, navigate to the directory where the assignments were installed, and launch the jupyter notebook from the terminal using the command

jupyter notebook
This should automatically open a tab in the default browser.

