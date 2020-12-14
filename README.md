# Tasks-2020-Machine-Learning-and-Statistics
My submission for the Tasks 2020 assessment for Machine Learning and Statistics module 2020.

## Author
John Dunne G00273895

## About this Repository
This repository contains one single jupyter notebook called Tasks.ipynb which contains my solutions to four tasks that were assigned throughout the semester. Each task is contained within its own section of the notebook with the references I called upon for each task listed at the end of each section. 

The assignment brief is contained in this repository in a document called assessment.pdf

The four tasks are detailed below:

1. October 5th, 2020: Write a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places.Your code should not depend on any module from the standard library or otherwise. You should research the task first and include references and a description of your algorithm.

2. November 2nd, 2020: The Chi-squared test for independence is a statistical hypothesis test like a t-test. It is used to analyse whether two categorical variables are independent. The Wikipedia article gives the table below as an example [4], stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats to verify this value and calculate the associated p value. You should include a short note with references justifying your analysis in a markdown cell.

3. November 16th, 2020: The standard deviation of an array of numbers x is calculated using numpy as np.sqrt(np.sum((x - np.mean(x))**2)/len(x)) . However, Microsoft Excel has two different versions of the standard deviation calculation, STDEV.P and STDEV.S . The STDEV.P function performs the above calculation but in the STDEV.S calculation the division is by len(x)-1 rather than len(x) . Research these Excel functions, writing a note in a Markdown cell about the difference between them. Then use numpy to perform a simulation demonstrating that the STDEV.S calculation is a better estimate for the standard deviation of a population when performed on a sample. Note that part of this task is to figure out the terminology in the previous sentence.

4. November 30th, 2020: Use scikit-learn to apply k-means clustering to Fisher’s famous Iris data set. You will easily obtain a copy of the data set online. Explain in a Markdown cell how your code works and how accurate it might be, and then explain how your model could be used to make predictions of species of iris.

## Difficulty displaying jupyter notebook on Github website
Sometimes jupyter notebooks do not load on the Github website. If this happens you can copy and paste the URL of the notebook and paste in the below website which will display the notebook: https://nbviewer.jupyter.org/

I have included the URL of my Tasks.ipynb notebook here also for convenience: https://github.com/johndunne2019/Tasks-2020-Machine-Learning-and-Statistics/blob/main/Tasks.ipynb

## How to download this repository
1. Go to GitHub.
2. Go to my repository: https://github.com/johndunne2019/Fundamentals-of-Data-Analysis-Project-2019
3. Click the Code button which is colored green.
4. Click on HTTPS and copy the link that is shown. 
5. Open the command line on your machine, navigate to the directory where you would like to clone the repository down to.
6. Enter the command: git clone followed by the URL of the repository.
7. The repository will be cloned down to your current working directory. 
8. You will need to navigate to this folder location on the command line in order to run the program.
9. Details on how to view my jupyter notebook are described in the next section below.

## How to run the jupyter notebook
1. On the command line navigate to the folder location where the repository has been downloaded and saved to using the cd change directory command.
2. Type jupyter notebook on the command line and press enter
3. After a short wait jupyter notebook will open in your web browser. 
4. Open the Tasks.ipynb notebook in the browser and the notebook containing the code and comments that I wrote for this assignment will be displayed.
5. if you want to run the code in any cell hold down the shift key and press enter and the command will run and the output wil be displayed in the next cell. 
6. To change between edit and read mode at any time press the ESC key.
7. If you wish t run the entire notebook click Kernel in the toolbar at the top of the screen and then click Resstart and run all. The notebook will refresh and all code cells will be executed from top to bottom. 
8. When you have finished viewing the jupyter notebook close the web browser and return to the command line. Press Ctrl + C on the command line to kill the program.