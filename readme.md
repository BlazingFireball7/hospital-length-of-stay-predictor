## How to Successfully Run Files in the Hospital Patient Length of Stay Predictor Project

Please note: These instructions are for running the project in VS code. If you are not using VS code, any or all of this project and/or these instructions may not be compatible with your code browser.

## Download the data set here
https://www.kaggle.com/datasets/bhautikmangukiya12/hospital-inpatient-discharges-dataset
add the data set into the same parent folder as the other porject files
## Before running any file, follow these steps:

Ensure python is installed on your computer. If it isn’t, then install it.
Create a virtual environment
Click select a kernel
Click select another kernel or choose an existing one if you have one you would like to use
If you chose an existing kernel you have competed step 2 
Click python environments
Select a kernel and your done with step 2 or click create a python environment
Click venv
Select a version
Search for packages and search and select pip
Finish
All module installations are included in the code but if you get an error regarding an uninstalled module or a requirement for a module name with a version of {some #} or higher then try the following:
Restart your kernel
Make sure the virtual environment is using a compatible python version with the module you are having trouble with
Try using the bellow install statement and replace the all caps characters with the proper module name 

import sys 
!{sys.executable} -m pip install MODULENAME


## Run files:

Make sure to run all files in the order they are in from top to bottom, when changing order in which you run the files the program may still work properly
Ignore the archive folder, if you try to run these you must move them from the folder and then ensure the necessary import and installation statements are there. There may not be functionality with these files.
You can now  change settings and test different things out as you'd like but it's recommended to make copies of the original files and then alter to copies to preserve the original code and ensure you always have working copies
WARNING: during testing, issues were found when running the file titled "7xg_boost.ipynb" Running this file may crash your computer. Avoiding running this file will not affect other files or any other part of the project. If you do run this file, you should save everything before hand and close all other applications

## Trouble Shooting:

Restart your kernel
Ensure you have proper file paths when reading in the data set
Make sure you have python installed and it is a compatible version
Follow step 3 again
Ensure you followed all instructions correctly
