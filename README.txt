Darin Johnson
Student ID: 001216025
4/16/2023
WGU Capstone Project C964


Welcome to the Vehicle Trade-In Forecaster! This User Guide is also available in the Task 2 write up included in the submission.

User Guide

Environment Setup:
1.	Download and install Python 3.10+.

2.	Download and install the latest version of Miniconda.
-		https://docs.conda.io/en/latest/miniconda.html

3.	Create an empty project folder somewhere on your drive and name it accordingly(avoid using spaces when naming).

4.	Open Miniconda from the Windows search bar and navigate to the folder you created using the Miniconda command prompt.

5.	Once you are navigated to the folder, type in the following command and press enter:
a.		conda create --prefix ./env pandas numpy matplotlib scikit-learn jupyter
i.			Type y and press enter when prompted. 
ii.			May take a few minutes to complete.

6.	Unzip and extract the files sent via submission and navigate to the project folder, place the Data folder and the .ipynb file in the same directory as the env folder.

7.	Using Miniconda navigate to the project folder. Once there, type the following command and press enter:
a.		conda activate (drive:\Your file path here\env) 
i.			Should look something like this conda activate r:\WGUCapstone\env

8.	Type ‘jupyter notebook’ and press enter
a.		A browser should open displaying your project directory.
9.	Your environment is now set up!

How to Use:
1.	Open the .ipynb folder by clicking on it. A new tab should open displaying the Jupyter Notebook file. 

2.	Press the Restart and Run All Cells button (>>) located at the top of the navigation bar. 

3.	Confirm by pressing the Restart and Run All Cells button (>>)
a.		The button will run all cells in the notebook, this may take a few minutes to complete.
b.		Optionally: You can choose to run each cell individually (consecutively) using Shift+Tab. 

4.	Once complete navigate to the bottom of the Jupyter Notebook page, there you will see a User Interface where you can enter details about your desired vehicle.

5.	Populate each label and drop down with the desired details and press the Predict! Button.

6.	A predicted dollar amount and a histogram highlighting the distribution of the dataset and where the predicted vehicle value falls in with the rest. 

•	NOTE: A couple of minor bugs exist:
o		Dropdowns are not currently dependent on each other, for city and model open the dropdown and start typing desired value to locate the appropriate option. 
o		The graph that gets created after prediction will not be replaced every time predict button is pressed, either rerun the final cell after each prediction or scroll to see the latest histogram.
