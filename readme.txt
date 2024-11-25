This tutorial is meant to be executed in command prompt terminal.

######################## Zip file contents overview and various package descriptions/requirements ########################


File Type         : File Name

overall zip file  : vitz_john_finaltermproj.zip
train data set    : vitz_john_finaltermproj_train_set.csv
test data set     : vitz_john_finaltermproj_test_set.csv
python executable : vitz_john_finaltermproj.py executable
jupyter notebook  : vitz_john_finaltermproj.ipynb noteboook

Added After Submission Deadline due to rushing (Doesn't count):

report pdf file (same as jupyter notebook file) : vitz_john_finaltermproj.pdf


The python script : vitz_john_finaltermproj.py was tested in the following versions:

Tested Python Version(s):

Python 3.10.6 (command terminal)
Python 3.10.12 (jupyter)


This python script requires the following packages in the virtual environment:

Built In Packages:

string (same as python version)
re 2.2.1

Required Packages for Download (Instructions on install in step 4):

pandas 2.2.2
numpy 1.26.4
scikit-learn 1.5.2
torch 2.5.1 / torch 2.5.1+cu121
nltk 3.9.1

##########################################################################################################################


############ Instructions for running the .py source file utilizing command prompt ############ 


############ Step 1: Extract and Place the .zip File

Download and extract the vitz_john_finaltermproj.zip folder to your desired file location. 
Copy the absolute file path of the folder, as you will need it for the next steps.


############ Step 2: Opening Command Prompt

Open command prompt through typing cmd.exe into the search bar
You need to use the 'cd' command to access the file folder through the copied file path:


cd <the absolute filepath of the file folder>


replace '<the absolute filepath of the file folder>' with your copy pasted file path


############ Step 3: Creating a Python Virtual Environment

Copy paste the line of code below to create a virtual python environment within the folder:

python -m venv venv


Copy paste this script to activate the virtual environment scripts:

venv\Scripts\activate.bat


############ Extra: Detecting Python Version

Tested Python Version(s):

Python 3.10.6 (command terminal)
Python 3.10.12 (jupyter)

I used Python 3.10.6 to run the code in the command terminal, and 3.10.12 to write the code in jupyter. 
To check your python version, copy and paste the following code:

python --version

This can be useful in case there are any package incompatibilities.

############ Step 4: Installing Package Dependencies

Used in Google Colab/Jupyter Notebook/Command Prompt Terminal:

Packages are arranged as follows:

Package name | Package Version # Website
==================================================================
pandas       | 2.2.2           # https://pandas.pydata.org/
numpy        | 1.26.4          # https://numpy.org/
matplotlib   | 3.8.0           # https://matplotlib.org/
scikit-learn | 1.5.2           # https://scikit-learn.org/stable/
torch        | 2.5.1           # https://pytorch.org/
nltk         | 3.9.1           # https://www.nltk.org/
==================================================================

Note: This project does not use cuda, so Google Colab's torch 2.5.1+cu121 is not necessary, base torch 2.5.1 fine.


To install the necessary versions of the required packages, please copy paste these commands into command prompt:

pip install pandas==2.2.2
pip install numpy==1.26.4
pip install matplotlib==3.8.0
pip install scikit-learn==1.5.2
pip install torch==2.5.1
pip install nltk==3.9.1


############ Running The Source Code

Copy and paste the following command into command prompt to begin

python vitz_john_final_term_proj.py
##########################################################################################################################
