## EMSC4033/EMSC8033 - Computational Geosciences: Problem-solving, Logical Thinking and Programming; semester 1 2022
# EMSC4033-2022-Project

# About the repository

To anyone who clicks in and wants to make a distribution map for organisms, welcome! The contents of this repository are there to guide you to make a simple distribution map. Enter the repository and click the folder named EMSC-4033-project, you should see two folders one called **Jupyter Notebook(s) (&Code)**, the other is called **project**. 

**Project folder**

Inside the **Project** folder, there are two files called **ProjectPlanner.md** and **Project report.ipynb**. The planner file is about expectations and preparation for this map-making work and the report file includes the instruction and reflection.

**Jupyter Notebook(s) (&Code) folder**

As its name suggests, it contains Jupyter Notebooks of the mapmaker, function and tests. 
Inside it, we have the mapmaker file, **Map.ipynb** and a test file **Run_tests.ipynb**. The source folders are **assets** and **tests**, which contain functions and tests for these functions respectively.

**Map.ipynb and Run_tests.ipynb files**

To run the mapmaker and the corresponding tests, open **Map.ipynb** and **Run_tests.ipynb** respectively. Simply run **Map.ipynb** and you will produce a map. And running **Run_tests.ipynb** will show you whether the written tests for the functions have passed, and if not, what errors have occurred.

**assets folder**

There are three files in this folder. **Platypus_dataframe.csv** is the organism distribution data file autogenerated by our mapmaking code. **dependencies_map.py** is used for importing all the packages we needed. And **functions_map.py** consists of a function written to request distribution data and plot the map. These assets support the running of **Map.ipynb** files mentioned above.

**tests folder**

You can open the tests folder to access **test_functions_map.py**. This contains a test function written to examine our functions in the ** functions map** file under certain conditions to make sure these functions work as we expected. They are predominantly pytest based. They support the running of the ** Run_tests.ipynb ** file mentioned above.

**Recommended procedure for users**

Read files in the **Project** first to get an idea about what this project is about and follow instructions from the report file to run codes in the **Jupyter Notebook(s) (&Code) folder**.

